
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بوابة السفراء جامعة آل البيت</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to right, #45a247, #283c86); /* الألوان المستوحاة من منصة نحن */
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
            color: white;
            text-align: center;
        }

        h1 {
            margin-bottom: 20px;
            font-size: 2.5em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .form-container {
            background: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.2);
            max-width: 600px;
            width: 100%;
            margin: 0 auto;
            display: none; /* إخفاء النموذج بشكل افتراضي */
        }

        iframe {
            width: 100%;
            height: 600px;
            border: none;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        .note {
            font-size: 1.1em;
            margin: 10px 0;
            color: #333;
        }

        .submit-button {
            background-color: #45a247; /* لون الزر */
            color: white;
            border: none;
            border-radius: 5px;
            padding: 15px 25px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s ease;
            width: 100%;
            margin-top: 10px;
        }

        .submit-button:hover {
            background-color: #388e3c; /* ظل أغمق عند التمرير */
        }

        .start-button {
            background-color: #ffffff;
            color: #45a247; /* لون الزر */
            border: none;
            border-radius: 5px;
            padding: 15px 25px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .start-button:hover {
            background-color: #e0e0e0;
        }

        .logo {
            width: 150px; /* تحديد عرض الشعار */
            margin-bottom: 20px; /* مسافة تحت الشعار */
        }

        .footer-logo {
            width: 100px; /* تحديد عرض الشعار السفلي */
            margin-top: 20px; /* مسافة فوق الشعار السفلي */
        }
    </style>
</head>
<body>
    <img src="https://assets.onecompiler.app/42wttk5ev/42wttjqj4/logo%20(2).png" alt="شعار الجامعة" class="logo"> <!-- الشعار العلوي -->
    <h1>بوابة السفراء جامعة آل البيت</h1>
    <button class="start-button" onclick="showForm()">ابدأ الدخول للبوابة</button> <!-- زر لبدء التعبئة -->

    <div class="form-container" id="formContainer"> <!-- إضافة id للنموذج -->
        <iframe src="https://docs.google.com/forms/d/e/1FAIpQLScVfhqYoq_YsgKPmuGJ2LIOSIhRC46UH8aWsKDEUlvofo7qqw/viewform?embedded=true" frameborder="0">جارٍ التحميل…</iframe>
        <p class="note">ملاحظة: سيتم الدخول بعد إكمال تعبئة البيانات.</p>
        <button class="submit-button" onclick="submitForm()">الدخول</button>
    </div>

    <img src="https://assets.onecompiler.app/42wttk5ev/42wttjqj4/22%20(3).png" alt="شعار إضافي" class="footer-logo"> <!-- الشعار السفلي -->

    <script>
        function showForm() {
            document.getElementById('formContainer').style.display = 'block'; // إظهار النموذج
        }

        function submitForm() {
            window.location.href = "https://fa893.github.io/Volunteer-Ambassadors/"; // الانتقال للموقع بعد الضغط على "إرسال"
        }
    </script>
</body>
</html>
