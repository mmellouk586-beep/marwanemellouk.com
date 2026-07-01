
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>البورتفوليو الشخصي | Rick</title>
    <style>
        /* إعدادات الخط والخلفية العامة */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #1e222b; /* خلفية رمادية داكنة تناسب طابع الأمن السيبراني */
            color: #f8f9fa;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        /* حاوية البورتفوليو الرئيسية */
        .portfolio-container {
            text-align: center;
            background-color: #282c34; /* درجة رمادية متناسقة مع واجهة العرض */
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            max-width: 500px;
            width: 90%;
            border: 1px solid #3f4451;
        }

        /* الصورة الدائرية المدمجة في الأعلى */
        .profile-img {
            width: 160px;
            height: 160px;
            border-radius: 50%; /* لجعل الصورة دائرية تماماً */
            object-fit: cover;
            border: 4px solid #2ea44f; /* إطار أخضر متناسق مع لون الصورة */
            margin-bottom: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.4);
        }

        /* اسم الشخص كبير */
        .programmer-name {
            font-size: 42px; /* حجم كبير للاسم */
            font-weight: bold;
            color: #2ea44f; /* اللون الأخضر المطابق للصورة */
            margin: 0 0 20px 0;
            letter-spacing: 1px;
        }

        /* البطاقة التعريفية */
        .bio-card p {
            font-size: 16px;
            line-height: 1.6;
            color: #abb2bf;
            margin-bottom: 25px;
        }

        /* زر GitHub الأخضر */
        .btn {
            display: inline-block;
            background-color: #2ea44f;
            color: #ffffff;
            padding: 12px 35px;
            border-radius: 8px; /* زوايا منحنية قليلاً متناسقة مع العرض */
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        .btn:hover {
            background-color: #22863a;
            transform: translateY(-2px);
        }
    </style>
</head>
<body>

    <div class="portfolio-container">
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR42mNk+M9QDwADhgGAWjR9awAAAABJRU5ErkJggg==" alt="Rick Profile" class="profile-img" id="embedded-img">
        
        <h1 class="programmer-name">Rick</h1>

        <div class="bio-card">
            <p>
                مرحباً، أنا باحث أمن سيبراني متخصص في اختبار الاختراق واكتشاف الثغرات الأمنية (Bug Bounty). أعمل على تحليل الأنظمة، واكتشاف نقاط الضعف البرمجية، وحماية الشبكات من التهديدات السيبرانية المعقدة. شغفي هو جعل العالم الرقمي مكاناً أكثر أماناً.
            </p>
            <a href="https://github.com" target="_blank" class="btn">تابعني على GitHub</a>
        </div>
    </div>

    <script>
        // كود تحويل الصورة الخاصة بك بدقة عالية لتعمل مباشرة
        document.getElementById('embedded-img').src = "data:image/png;base64,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";
    </script>
</body>
</html>
