<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>حسام عبد الحميد الحمد</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        h1 {
            color: #333;
            margin-top: 50px;
        }
        form {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            display: inline-block;
            margin-top: 20px;
        }
        input[type="text"], input[type="password"] {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <h1>حسام عبد الحميد الحمد</h1>
    <form id="registrationForm">
        <input type="text" id="username" placeholder="اسم المستخدم" required><br>
        <input type="password" id="password" placeholder="كلمة المرور" required><br>
        <button type="button" onclick="submitForm()">إرسال</button>
    </form>

    <script>
        function submitForm() {
            const username = document.getElementById('username').value;
            const password = document.getElementById('password').value;

            if (username && password) {
                alert(تم تسجيل المستخدم: ${username});
            } else {
                alert('يرجى إدخال اسم المستخدم وكلمة المرور');
            }
        }
    </script>
</body>
</html>