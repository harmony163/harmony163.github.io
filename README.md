<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سایت شخصی من</title>
    <style>
        /* ===== استایل کلی ===== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Vazir', Tahoma, sans-serif;
            background: #f8fafc;
            color: #2d3748;
            line-height: 1.8;
        }
        a {
            text-decoration: none;
            color: #2563eb;
        }
        .container {
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }

        /* ===== منوی بالای سایت ===== */
        header {
            background: #ffffff;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 30px;
            max-width: 1000px;
            margin: auto;
            flex-wrap: wrap;
        }
        .logo {
            font-size: 1.4em;
            font-weight: bold;
            color: #2563eb;
        }
        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        .nav-links a {
            color: #4a5568;
            font-weight: 500;
            transition: color 0.2s;
        }
        .nav-links a:hover {
            color: #2563eb;
        }

        /* ===== بخش معرفی (Hero) ===== */
        .hero {
            background: linear-gradient(135deg, #2563eb, #7c3aed);
            color: white;
            padding: 80px 20px;
            text-align: center;
        }
        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2em;
            opacity: 0.9;
        }

        /* ===== بخش درباره من ===== */
        .section {
            background: white;
            margin: 30px 0;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.04);
        }
        .section h2 {
            color: #1e293b;
            border-right: 4px solid #2563eb;
            padding-right: 12px;
            margin-bottom: 20px;
            font-size: 1.6em;
        }
        .about-content {
            display: flex;
            gap: 30px;
            align-items: center;
            flex-wrap: wrap;
        }
        .about-text {
            flex: 1;
            min-width: 250px;
        }

        /* ===== مهارت‌ها ===== */
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }
        .skill-tag {
            background: #e0e7ff;
            color: #3730a3;
            padding: 6px 16px;
            border-radius: 20px;
            font-size: 0.9em;
            font-weight: bold;
        }

        /* ===== نمونه‌کارها ===== */
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .portfolio-card {
            background: #f8fafc;
            border-radius: 10px;
            padding: 20px;
            border: 1px solid #e2e8f0;
            transition: transform 0.2s, box-shadow 0.2s;
        }
        .portfolio-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(0,0,0,0.08);
        }
        .portfolio-card h3 {
            color: #1e293b;
            margin-bottom: 5px;
        }
        .portfolio-card p {/* ===== وبلاگ ===== */
        .blog-post {
            padding: 15px;
            border-bottom: 1px solid #e2e8f0;
        }
        .blog-post:last-child {
            border-bottom: none;
        }
        .blog-post h3 {
            margin-bottom: 5px;
        }
        .blog-post h3 a {
            color: #1e293b;
        }
        .blog-post .date {
            font-size: 0.85em;
            color: #718096;
        }

        /* ===== تماس ===== */
        .contact-btn {
            display: inline-block;
            background: #2563eb;
            color: white;
            padding: 10px 25px;
            border-radius: 25px;
            margin-top: 15px;
            transition: background 0.2s;
        }
        .contact-btn:hover {
            background: #1d4ed8;
        }

        /* ===== فوتر ===== */
        footer {
            text-align: center;
            padding: 25px;
            background: #1e293b;
            color: #cbd5e1;
            margin-top: 40px;
        }
        footer a {
            color: #93c5fd;
        }

        /* ===== ریسپانسیو (موبایل) ===== */
        @media (max-width: 600px) {
            nav {
                flex-direction: column;
                gap: 10px;
            }
            .hero h1 {
                font-size: 1.8em;
            }
        }
    </style>
</head>
<body>

    <!-- منوی بالای سایت -->
    <header>
        <nav>
            <div class="logo">🚀 نام شما</div>
            <ul class="nav-links">
                <li><a href="#about">درباره من</a></li>
                <li><a href="#portfolio">نمونه‌کارها</a></li>
                <li><a href="#blog">وبلاگ</a></li>
                <li><a href="#contact">تماس</a></li>
            </ul>
        </nav>
    </header>

    <!-- بخش معرفی اصلی -->
    <section class="hero">
        <h1>سلام! من [نام شما] هستم</h1>
        <p>طراح، برنامه‌نویس و علاقه‌مند به [حوزه شما]</p>
    </section>

    <div class="container">

        <!-- درباره من -->
        <section id="about" class="section">
            <h2>👨‍💻 درباره من</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>
                        اینجا یک متن کوتاه درباره خودتان بنویسید. مثلاً تحصیلات، علاقه‌مندی‌ها،
                        یا داستان شروع کارتان. این بخش مهم‌ترین جایی است که مخاطب با شما آشنا می‌شود.
                    </p>
                    <p>
                        می‌توانید دوستانه و صمیمی بنویسید تا حس اعتماد ایجاد کند.
                    </p>
                </div>
                <div class="skills">
                    <span class="skill-tag">HTML</span>
                    <span class="skill-tag">CSS</span>
                    <span class="skill-tag">Python</span>
                    <span class="skill-tag">طراحی</span>
                    <span class="skill-tag">فتوشاپ</span>
                </div>
            </div>
        </section>

        <!-- رزومه و نمونه‌کارها -->
        <section id="portfolio" class="section">
            <h2>💼 نمونه‌کارها</h2>
            <div class="portfolio-grid">
                <div class="portfolio-card">
                    <h3>پروژه اول</h3>
                    <p>توضیح کوتاهی درباره این پروژه بنویسید و نتیچه یا لینک آن را قرار دهید.</p>
                </div>
                <div class="portfolio-card">
                    <h3>پروژه دوم</h3>
                    <p>توضیح کوتاهی درباره این پروژه بنویسید و نتیچه یا لینک آن را قرار دهید.</p>
                </div>
                <div class="portfolio-card">
                    <h3>پروژه سوم</h3>
                    <p>توضیح کوتاهی درباره این پروژه بنویسید و نتیچه یا لینک آن را قرار دهید.</p>
                </div>
            </div>
        </section>

        <!-- وبلاگ -->
        <section id="blog" class="section"><h2>✍️ وبلاگ</h2>
            <div class="blog-post">
                <h3><a href="#">عنوان اولین پست وبلاگ</a></h3>
                <div class="date">۱۴۰۳/۰۵/۲۰</div>
                <p>چند خط اول پست برای جذب مخاطب...</p>
            </div>
            <div class="blog-post">
                <h3><a href="#">عنوان دومین پست وبلاگ</a></h3>
                <div class="date">۱۴۰۳/۰۵/۱۵</div>
                <p>خلاصه کوتاهی از این مطلب...</p>
            </div>
            <div class="blog-post">
                <h3><a href="#">عنوان سومین پست وبلاگ</a></h3>
                <div class="date">۱۴۰۳/۰۵/۰۸</div>
                <p>چرا شروع کردم؟ این پست درباره انگیزه من است...</p>
            </div>
        </section>

        <!-- تماس و معرفی کسب‌وکار -->
        <section id="contact" class="section">
            <h2>📞 تماس با من</h2>
            <p>می‌توانید برای همکاری، پروژه، یا هر سوالی با من در ارتباط باشید.</p>
            <a href="mailto:your@email.com" class="contact-btn">ارسال ایمیل</a>
            <p style="margin-top: 15px;">
                <a href="#">اینستاگرام</a> | 
                <a href="#">لینکدین</a> | 
                <a href="#">تلگرام</a>
            </p>
        </section>

    </div>

    <!-- فوتر -->
    <footer>
        <p>© ۱۴۰۳ [نام شما] | ساخته شده با ❤️</p>
    </footer>

</body>
</html>
            font-size: 0.9em;
            color: #4a5568;
        }
