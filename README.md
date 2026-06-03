<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IBOK - إيبوك</title>
    <style>
        :root {
            --primary-color: #1e5631; /* لون بنك الخرطوم المميز */
            --secondary-color: #a3cd3b;
            --telegram-color: #2CA5E0; /* لون التلجرام الرسمي */
            --text-dark: #333333;
            --bg-light: #f4f7f6;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-light);
            color: var(--text-dark);
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        .container {
            background-color: #ffffff;
            padding: 2.5rem;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
            text-align: center;
            max-width: 450px;
            width: 90%;
            border-top: 5px solid var(--primary-color);
        }

        .logo {
            font-size: 3rem;
            font-weight: bold;
            color: var(--primary-color);
            margin-bottom: 0.5rem;
        }

        .subtitle {
            font-size: 1.1rem;
            color: #666;
            margin-bottom: 2rem;
        }

        .status-card {
            background-color: #e8f5e9;
            border: 1px solid #c8e6c9;
            padding: 1rem;
            border-radius: 8px;
            margin-bottom: 2rem;
        }

        .status-text {
            color: #2e7d32;
            font-weight: 600;
            margin: 0;
        }

        /* تنسيق زر التلجرام */
        .btn-telegram {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            background-color: var(--telegram-color);
            color: #ffffff;
            text-decoration: none;
            padding: 0.8rem 2rem;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.1rem;
            transition: background-color 0.3s ease, transform 0.2s ease;
            box-shadow: 0 4px 15px rgba(44, 165, 224, 0.4);
        }

        .btn-telegram:hover {
            background-color: #2494cb;
            transform: translateY(-2px);
        }

        .btn-telegram:active {
            transform: translateY(0);
        }

        .footer {
            margin-top: 2.5rem;
            font-size: 0.85rem;
            color: #999;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="logo">إيبوك</div>
        <div class="subtitle">واجهة تطبيق بنك الخرطوم (BOK) المحدثة</div>
        
        <div class="status-card">
            <p class="status-text">المشروع قيد التطوير والتحسين المستمر</p>
        </div>

        <!-- زر التلجرام المرتبط بحسابك -->
        <a href="https://t.me/acssesbl" class="btn-telegram" target="_blank">
            تواصل معي عبر تلجرام 🚀
        </a>

        <div class="footer">
            &copy; 2026 جميع الحقوق محفوظة لـ إيبوك
        </div>
    </div>

</body>
</html>
