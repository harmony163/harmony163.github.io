<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>پرتال سلامت و زیست‌شناسی</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Tahoma, sans-serif;
            background: #f0f4f8;
            color: #2d3748;
            line-height: 1.8;
        }
        a {
            text-decoration: none;
            color: #2b6cb0;
        }
        .container {
            max-width: 1000px;
            margin: auto;
            padding: 15px;
        }
        header {
            background: #2c3e50;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        header h1 {
            font-size: 1.8em;
        }
        nav {
            background: #34495e;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #ecf0f1;
            margin: 0 10px;
            font-size: 0.95em;
            display: inline-block;
            padding: 5px 10px;
        }
        nav a:hover {
            background: #2c3e50;
            border-radius: 5px;
        }
        .hero {
            background: #2980b9;
            color: white;
            padding: 50px 20px;
            text-align: center;
        }
        .hero h2 {
            font-size: 2em;
            margin-bottom: 10px;
        }
        .section {
            background: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        .section h2 {
            border-right: 4px solid #2980b9;
            padding-right: 10px;
            margin-bottom: 15px;
            color: #1a202c;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }
        .card {
            background: #f7fafc;
            padding: 15px;
            border-radius: 8px;
            border: 1px solid #e2e8f0;
        }
        .card h3 {
            color: #2d3748;
            margin-bottom: 5px;
        }
        .tag {
            display: inline-block;
            background: #bee3f8;
            color: #2b6cb0;
            padding: 2px 10px;
            border-radius: 10px;
            font-size: 0.8em;
            margin: 3px 0;
        }
        .btn {
            display: block;
            width: 200px;
            margin: 20px auto;
            background: #2980b9;
            color: white;
            padding: 10px;
            text-align: center;
            border-radius: 25px;
            font-weight: bold;
        }
        .btn:hover {
            background: #1a5276;
        }
        .pillar {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }
        .pillar-item {
            background: #edf2f7;
            padding: 10px 15px;
            border-radius: 8px;
            flex: 1 1 180px;
            text-align: center;
            border-right: 3px solid #2980b9;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #2c3e50;
            color: #bdc3c7;
            margin-top: 30px;
        }
        @media (max-width: 600px) {
            header h1 {
                font-size: 1.4em;
            }
            .hero h2 {
                font-size: 1.5em;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>🧬 زیست‌آگاهی | سلامت و دانش</h1>
    </header>

    <nav>
        <a href="#biology">زیست‌شناسی</a>
        <a href="#disease">بیماری‌ها</a>
        <a href="#treatment">درمان و دارو</a>
        <a href="#traditional">طب سنتی</a>
        <section class="hero">
        <h2>🔬 مرجع تخصصی سلامت</h2>
        <p>از سلول تا بالین – زیست‌شناسی مولکولی، بیماری‌ها، داروها، طب سنتی و پرستاری</p>
    </section>

    <div class="container">

        <!-- زیست‌شناسی -->
        <section id="biology" class="section">
            <h2>🧪 زیست‌شناسی سلولی و مولکولی</h2>
            <div class="grid">
                <div class="card">
                    <h3>غشای سلولی</h3>
                    <span class="tag">سلول</span>
                    <p>دولایه فسفولیپیدی با پروتئین‌های غشایی برای انتقال مواد و سیگنال‌دهی</p>
                </div>
                <div class="card">
                    <h3>همانندسازی DNA</h3>
                    <span class="tag">ژنتیک</span>
                    <p>فرایند نیمه‌حفاظتی با آنزیم DNA پلیمراز و سیستم ترمیم خطا</p>
                </div>
                <div class="card">
                    <h3>آپوپتوز</h3>
                    <span class="tag">سلول</span>
                    <p>مرگ برنامه‌ریزی شده سلول برای حذف سلول‌های آسیب‌دیده</p>
                </div>
                <div class="card">
                    <h3>مسیرهای سیگنالینگ</h3>
                    <span class="tag">مولکول</span>
                    <p>MAPK، Wnt، PI3K – هدف بسیاری از داروهای ضد سرطان</p>
                </div>
            </div>
        </section>

        <!-- بیماری‌ها -->
        <section id="disease" class="section">
            <h2>🦠 بیماری‌ها</h2>
            <div class="grid">
                <div class="card">
                    <h3>دیابت نوع 2</h3>
                    <span class="tag">متابولیک</span>
                    <p>مقاومت به انسولین – درمان با متفورمین، رژیم و ورزش</p>
                </div>
                <div class="card">
                    <h3>سرطان ریه</h3>
                    <span class="tag">انکولوژی</span>
                    <p>جهش در EGFR، KRAS – درمان با داروهای هدفمند و ایمونوتراپی</p>
                </div>
                <div class="card">
                    <h3>آلزایمر</h3>
                    <span class="tag">اعصاب</span>
                    <p>تجمع آمیلوئید بتا – درمان علامتی با دونپزیل</p>
                </div>
                <div class="card">
                    <h3>COVID-19</h3>
                    <span class="tag">عفونی</span>
                    <p>کروناویروس – واکسن mRNA و داروی پکسلووید</p>
                </div>
            </div>
        </section>

        <!-- درمان و دارو -->
        <section id="treatment" class="section">
            <h2>💊 درمان و داروها</h2>
            <div class="pillar">
                <div class="pillar-item">
                    <h4>آنتی‌بیوتیک‌ها</h4>
                    <p>آموکسی‌سیلین، سیپروفلوکساسین</p>
                </div>
                <div class="pillar-item">
                    <h4>ضدالتهاب‌ها</h4>
                    <p>ایبوپروفن، کورتیکواستروئید</p>
                </div>
                <div class="pillar-item">
                    <h4>شیمی‌درمانی</h4>
                    <p>سیس‌پلاتین، وین‌کریستین</p>
                </div>
                <div class="pillar-item">
                    <h4>داروهای هدفمند</h4>
                    <p>ایماتینیب، تراستوزوماب</p>
                </div>
            </div>
        </section>

        <!-- طب سنتی -->
        <section id="traditional" class="section">
            <h2>🌿 طب سنتی و گیاهی</h2>
            <div class="grid">
                <div class="card">
                    <h3>زنجبیل</h3>
                    <span class="tag">ضدالتهاب</span>
                    <p>جینجرول – کاهش تهوع و درد مفاصل</p>
                </div>
                <div class="card">
                    <h3>زردچوبه</h3>
                    <span class="tag">آنتی‌اکسیدان</span>
                    <p>کورکومین – مهار التهاب و رشد تومور</p>
                </div>
                <div class="card">
                    <h3>خارمریم</h3>
                    <span class="tag">کبد</span>
                    <p>سیلیمارین – محافظ کبد در کبد چرب</p>
                </div>
                <div class="card">
                    <h3>سنبل‌الطیب</h3>
                    <span class="tag">آرامبخش</span>
                    <p>کاهش اضطراب و بهبود خواب</p>
                </div>
            </div>
        </section>

        <!-- پرستاری -->
        <section id="nursing" class="section">
            <h2>👩‍⚕️ پرستاری</h2>
            <div class="grid">
                <div class="card">
                    <h3>زخم فشاری</h3>
                    <span class="tag">مراقبت</span>
                    <p>تغییر پوزیشن هر 2 ساعت و پانسمان مدرن</p>
                </div>
                <div class="card">
                    <h3>مدیریت درد</h3>
                    <span class="tag">درد</span>
                    <p>مسکن‌ها بر اساس نردبان WHO</p>
                </div>
                <div class="card">
                    <h3>تهویه مکانیکی</h3>
                    <span class="tag">ICU</span>
                    <p>مراقبت از بیماران با ونتیلاتور</p>
                </div>
                <div class="card">
                    <h3>گزارش SOAP</h3>
                    <span class="tag">مستندسازی</span>
                    <p>ثبت وضعیت بیمار به روش استاندارد</p>
                </div>
            </div>
        </section>

        <!-- تماس -->
        <section id="contact" class="section" style="text-align:center;">
            <h2>📬 تماس</h2>
            <p>ایمیل: info@zistaghahi.ir</p>
            <p>تلگرام | اینستاگرام | لینکدین</p>
            <a href="mailto:info@zistaghahi.ir" class="btn">ارسال پیام</a>
        </section>

    </div>

    <footer>
        <p>© ۱۴۰۴ زیست‌آگاهی | مطالب با استناد علمی</p>
    </footer>

</body>
</html>

        <a href="#nursing">پرستاری</a>
        <a href="#contact">تماس</a>
    </nav>
