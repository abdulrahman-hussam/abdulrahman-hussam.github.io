<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EERI HTI Student Chapter</title>
    <style>
        :root {
            --primary-blue: #1A2B4C;
            --accent-red: #992827;
            --bg-light: #F8F9FA;
            --text-dark: #212529;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bg-light);
            color: var(--text-dark);
        }
        header {
            background-color: var(--primary-blue);
            color: white;
            padding: 1.5rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 4px solid var(--accent-red);
        }
        header h1 {
            margin: 0;
            font-size: 1.5rem;
        }
        .hero {
            text-align: center;
            padding: 4rem 2rem;
            background: linear-gradient(135deg, var(--primary-blue) 0%, #0D172A 100%);
            color: white;
        }
        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 0 auto 2rem auto;
            opacity: 0.9;
        }
        .btn-primary {
            background-color: var(--accent-red);
            color: white;
            padding: 0.8rem 1.8rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s ease;
        }
        .btn-primary:hover {
            background-color: #7A201F;
        }
        .container {
            max-width: 1100px;
            margin: 3rem auto;
            padding: 0 1.5rem;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .card {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            border-top: 3px solid var(--accent-red);
        }
        footer {
            background-color: var(--primary-blue);
            color: white;
            text-align: center;
            padding: 1.5rem;
            margin-top: 4rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>EERI HTI Student Chapter</h1>
        <nav><strong>Season 27</strong></nav>
    </header>

    <section class="hero">
        <h2>Building Resilience, Engineering the Future</h2>
        <p>المؤتمر والفرع الطلابي الرسمي للمعهد التكنولوجي العالي للجمعية الأمريكية لبحوث الهندسة الزلزالية (EERI).</p>
        <a href="#about" class="btn-primary">استكشف الشابتر</a>
    </section>

    <div class="container" id="about">
        <div class="grid">
            <div class="card">
                <h3>عن الشابتر</h3>
                <p>نهدف إلى تنمية مهارات طلاب الهندسة المدنية والإنشائية في مجالات التحليل الإنشائي والتصميم الزلزالي من خلال الورش والمسابقات العلمية.</p>
            </div>
            <div class="card">
                <h3>معرض الإنجازات</h3>
                <p>توثيق لمشاركات الشابتر المتميزة في المسابقات المحلية والدولية، وتصميم نماذج خشب البالسا واختبارها على أجهزة المحاكاة الزلزالية.</p>
            </div>
            <div class="card">
                <h3>الانضمام إلينا</h3>
                <p>تابعنا للاطلاع على مواعيد فتح باب التقديم (Recruitment) والورش التدريبية القادمة خلال العام الدراسي.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 EERI HTI Student Chapter - All Rights Reserved</p>
    </footer>

</body>
</html>
