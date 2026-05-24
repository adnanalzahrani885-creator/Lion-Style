<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صالون موضه اسد للحلاقة | LION STYLE</title>
    <style>
        /* الألوان: أسود وفخامة الذهبي */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #e0e0e0;
        }
        header {
            background-color: #0a0a0a;
            color: #d4af37; 
            padding: 25px;
            text-align: center;
            border-bottom: 2px solid #d4af37;
        }
        header h1 { margin: 0; font-size: 2.2rem; font-weight: bold; }
        header p { margin: 5px 0 0; color: #aaa; letter-spacing: 1px; font-size: 1.4rem; font-weight: bold; }
        
        nav {
            background-color: #1a1a1a;
            text-align: center;
            padding: 12px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: 0.3s;
        }
        nav a:hover { color: #d4af37; }

        /* الواجهة الترحيبية */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://unsplash.com') no-repeat center center/cover;
            height: 350px;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
        }
        .hero h2 { font-size: 2.5rem; margin: 0; color: #d4af37; }
        .hero p { font-size: 1.2rem; margin-top: 10px; color: #ddd; }

        .container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
        }
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2rem;
            color: #d4af37;
        }
        
        /* قسم الخدمات */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }
        .service-card {
            background: #1e1e1e;
            border-radius: 8px;
            border: 1px solid #333;
            padding: 20px;
            text-align: center;
            transition: 0.3s;
        }
        .service-card:hover {
            border-color: #d4af37;
            transform: translateY(-5px);
        }
        .service-card h3 { margin: 10px 0; color: #fff; }
        .service-card p { color: #aaa; font-size: 0.95rem; }
        
        /* أزرار الحجز والتواصل */
        .btn-booking {
            display: inline-block;
            background-color: #25D366;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 25px;
            margin-top: 15px;
            font-weight: bold;
            transition: 0.3s;
        }
        .btn-booking:hover { background-color: #20ba5a; }

        /* قسم معلومات الصالون والخريطة */
        .info-section {
            background-color: #1a1a1a;
            padding: 30px;
            border-radius: 8px;
            margin-top: 5px;
            text-align: center;
            border: 1px solid #333;
        }
        .info-section p { margin: 10px 0; font-size: 1.1rem; }
        
        .time-box {
            background: #222;
            padding: 15px;
            border-radius: 6px;
            margin: 15px auto;
            max-width: 500px;
            border-right: 4px solid #d4af37;
            text-align: right;
        }
        .time-box h4 { margin: 0 0 10px 0; color: #d4af37; }

        .map-container {
            margin-top: 25px;
            border-radius: 8px;
            overflow: hidden;
            border: 1px solid #d4af37;
        }

        footer {
            background-color: #0a0a0a;
            color: #888;
            text-align: center;
            padding: 20px;
            margin-top: 60px;
            border-top: 1px solid #222;
        }
    </style>
</head>
<body>

    <!-- اسم الصالون والشعار النصي المحدث بالاسم المفضل -->
    <header>
        <h1>صالون موضه اسد</h1>
        <p>✨ LION STYLE ✨</p>
    </header>

    <!-- روابط التنقل السريع -->
    <nav>
        <a href="#home">الرئيسية</a>
        <a href="#services">خدماتنا</a>
        <a href="#about">موقعنا ومواعيدنا</a>
    </nav>

    <!-- الواجهة الرئيسية للموقع -->
    <section class="hero" id="home">
        <h2>احصل على القصة التي تبرز شخصيتك</h2>
        <p>دقة في الأداء، عصرية في الموضة، وعناية تليق بك</p>
        <!-- رابط الحجز المباشر بالواتساب الخاص بك -->
        <a href="https://wa.meً%20صالون%20أسد،%20أريد%20حجز%20موعد%20للحلاقة" class="btn-booking" target="_blank">اضغط هنا للاستفسار والحجز عبر واتساب</a>
    </section>

    <!-- قسم الخدمات المتاحة -->
    <div class="container" id="services">
        <h2 class="section-title">خدماتنا المتميزة</h2>
        <div class="services-grid">
            
            <!-- الخدمة 1 -->
            <div class="service-card">
                <h3>قص وتصفيف الشعر</h3>
                <p>أحدث قصات الشعر العالمية والموضة العصرية التي تناسب ملامحك.</p>
            </div>

            <!-- الخدمة 2 -->
            <div class="service-card">
                <h3>حلاقة وتحديد الذقن</h3>
                <p>تحديد احترافي للذقن باستخدام أفضل أدوات العناية والترطيب.</p>
            </div>

            <!-- الخدمة 3 -->
            <div class="service-card">
                <h3>العناية بالبشرة والوجه</h3>
                <p>تنظيف عميق، ماسكات طبيعية، وحمام بخار لإنعاش بشرتك وإعادة حيويتها.</p>
            </div>

        </div>
    </div>

    <!-- قسم مواعيد العمل وموقع الصالون -->
    <div class="container" id="about">
        <div class="info-section">
            <h2 style="color: #d4af37; margin-top: 0;">مرحباً بكم في LION STYLE</h2>
            <p>📍 **الموقع**: الرياض - حي الحزم - طريق ديراب الفرعي</p>
            <p>📞 **للتواصل المباشر**: 0501007991</p>
            
            <!-- صندوق أوقات العمل المحدث -->
            <div class="time-box">
                <h4>⏰ أوقات العمل الرسمية:</h4>
                <p>• **السبت إلى الخميس**: من الساعة 11:00 صباحاً وحتى 5:00 صباحاً</p>
                <p>• **يوم الجمعة**: من الساعة 12:30 مساءً وحتى 5:00 صباحاً</p>
            </div>
            
            <!-- خريطة توضيحية لحي الحزم طريق ديراب -->
            <div class="map-container">
                <iframe src="https://google.com" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
        </div>
    </div>

    <!-- أسفل الموقع -->
    <footer>
        <p>جميع الحقوق محفوظة © 2026 | صالون موضه اسد - LION STYLE</p>
    </footer>

</body>
</html>
