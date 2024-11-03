<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Abdelhalim Moaty</title>
    <style>
        /* إعدادات عامة */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #1c1cf0, #4a4aff);
            color: #fff;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* الرأس */
        header {
            text-align: center;
            padding: 50px 20px;
        }

        header h1 {
            font-size: 2.5em;
        }

        header p {
            font-size: 1.2em;
            margin-top: 10px;
        }

        /* السيرة الذاتية */
        .cv {
            background-color: rgba(255, 255, 255, 0.1);
            padding: 30px;
            margin: 40px 0;
            border-radius: 8px;
        }

        .cv h2 {
            text-align: center;
            margin-bottom: 20px;
            font-size: 2em;
            color: #ffdd57;
        }

        .cv-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }

        /* معرض الأعمال */
        .portfolio {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .portfolio-item {
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            overflow: hidden;
            position: relative;
        }

        .portfolio-item img {
            width: 100%;
            height: auto;
            display: block;
        }

        .portfolio-item .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            color: #fff;
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: 0;
            transition: opacity 0.3s;
            text-align: center;
        }

        .portfolio-item:hover .overlay {
            opacity: 1;
        }

        /* تواصل سريع */
        footer {
            text-align: center;
            padding: 20px;
            font-size: 1.2em;
        }

        footer a {
            color: #ffdd57;
            text-decoration: none;
            margin: 0 10px;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- رأس الصفحة -->
        <header>
            <h1>Abdelhalim Moaty</h1>
            <p>Graphic Designer & Media Manager</p>
        </header>

        <!-- السيرة الذاتية -->
        <section class="cv">
            <h2>السيرة الذاتية</h2>
            <div class="cv-content">
                <p>مصمم جرافيك ذو خبرة سنتين في إنشاء تصميمات عالية الجودة عبر مختلف المنصات. اكتسبت مؤخرًا مهارات في إدارة الوسائط، مما يعزز القدرة على توجيه المحتوى بما يتوافق مع استراتيجيات التسويق وتحقيق الأهداف.</p>
                <p><strong>المهارات:</strong> فوتوشوب، إلستريتر، أفترإفكت، باوربوينت، وورد</p>
            </div>
        </section>

        <!-- معرض الأعمال -->
        <section class="portfolio">
            <div class="portfolio-item">
                <img src="C:\Users\amenm\Downloads\My Designs\Medvantage\Portfolio\New Hope Blue.png" alt="New Hope Project">
                <div class="overlay">New Hope Project</div>
            </div>
            <div class="portfolio-item">
                <img src="C:\Users\amenm\Downloads\My Designs\Medvantage\Portfolio\Car Portf.png" alt="Car Meet Event Project">
                <div class="overlay">Car Meet Event Project</div>
            </div>
            <div class="portfolio-item">
                <img src="C:\Users\amenm\Downloads\My Designs\Medvantage\Portfolio\Bright Dent Portfolio.png" alt="New Hope Project">
                <div class="overlay">Bright Dent Project</div>
            <!-- أضف المزيد من المشاريع حسب الحاجة -->
        </section>

        <!-- قسم التواصل -->
        <footer>
            <p>تواصل معي عبر:</p>
            <a href="https://www.instagram.com/halimmoty/" target="_blank">Instagram</a> |
            <a href="https://www.facebook.com/Abdalhalim22/" target="_blank">Facebook</a> |
            <span>Email: halimmoty@gmail.com | </span>
            <span>Phone: +20 1099298320</span>
        </footer>
    </div>

</body>
</html>
