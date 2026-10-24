<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>خطوة للمُقبل | عيادة التغذية العلاجية - أخصائية التغذية إسراء المقبل</title>
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700;800&family=Amiri:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
    
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        :root {
            --sage-dark: #2d4a3e;
            --sage-primary: #52796f;
            --sage-medium: #84a59d;
            --sage-light: #f2f5f3;
            --sage-soft: #e8efe9;
            --gold-accent: #c5a059;
            --gold-hover: #b08d46;
            --text-dark: #222222;
            --text-muted: #555555;
            --bg-white: #ffffff;
            --shadow-soft: 0 10px 30px rgba(0, 0, 0, 0.05);
            --shadow-hover: 0 15px 35px rgba(82, 121, 111, 0.15);
            --radius-main: 16px;
            --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Tajawal', sans-serif;
            background-color: var(--sage-light);
            color: var(--text-dark);
            line-height: 1.7;
            overflow-x: hidden;
        }

        /* Container */
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }

        /* Typography Helper */
        .poetry-font {
            font-family: 'Amiri', serif;
        }

        /* Header / Navbar */
        header {
            background-color: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 20px rgba(0,0,0,0.04);
            transition: var(--transition);
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }

        .logo-brand {
            display: flex;
            align-items: center;
            gap: 12px;
            text-decoration: none;
        }

        .logo-brand img {
            height: 52px;
            width: auto;
            border-radius: 50%;
            object-fit: cover;
        }

        .brand-text h1 {
            font-size: 1.4rem;
            color: var(--sage-dark);
            font-weight: 800;
            line-height: 1.2;
        }

        .brand-text span {
            font-size: 0.8rem;
            color: var(--gold-accent);
            font-weight: 500;
            display: block;
        }

        .nav-links {
            display: flex;
            gap: 25px;
            list-style: none;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--text-dark);
            font-weight: 500;
            font-size: 0.95rem;
            transition: var(--transition);
            position: relative;
        }

        .nav-links a:hover {
            color: var(--sage-primary);
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            right: 0;
            width: 0;
            height: 2px;
            background-color: var(--gold-accent);
            transition: var(--transition);
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .btn-cta {
            background: linear-gradient(135deg, var(--sage-primary), var(--sage-dark));
            color: #fff !important;
            padding: 10px 22px;
            border-radius: 30px;
            font-weight: 700;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            box-shadow: 0 4px 15px rgba(82, 121, 111, 0.3);
            transition: var(--transition);
        }

        .btn-cta:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(82, 121, 111, 0.4);
            background: linear-gradient(135deg, var(--sage-dark), var(--sage-primary));
        }

        /* Hero Section */
        .hero {
            padding: 70px 0;
            background: linear-gradient(180deg, #ffffff 0%, var(--sage-light) 100%);
            position: relative;
        }

        .hero-grid {
            display: grid;
            grid-template-columns: 1.1fr 0.9fr;
            gap: 40px;
            align-items: center;
        }

        .hero-text .tagline {
            display: inline-block;
            background-color: var(--sage-soft);
            color: var(--sage-dark);
            padding: 6px 16px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 700;
            margin-bottom: 15px;
            border: 1px solid rgba(82, 121, 111, 0.2);
        }

        .hero-text h2 {
            font-size: 2.5rem;
            color: var(--sage-dark);
            line-height: 1.3;
            margin-bottom: 20px;
            font-weight: 800;
        }

        .hero-text h2 span {
            color: var(--gold-accent);
        }

        .hero-text p {
            font-size: 1.1rem;
            color: var(--text-muted);
            margin-bottom: 30px;
        }

        .hero-btns {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }

        .btn-secondary {
            background-color: transparent;
            color: var(--sage-dark);
            border: 2px solid var(--sage-primary);
            padding: 10px 22px;
            border-radius: 30px;
            font-weight: 700;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            transition: var(--transition);
        }

        .btn-secondary:hover {
            background-color: var(--sage-soft);
            color: var(--sage-dark);
        }

        .hero-image {
            position: relative;
            text-align: center;
        }

        .profile-frame {
            width: 320px;
            height: 380px;
            margin: 0 auto;
            border-radius: 200px 200px 30px 30px;
            overflow: hidden;
            border: 8px solid var(--bg-white);
            box-shadow: var(--shadow-soft);
            position: relative;
            background-color: #ddd;
        }

        .profile-frame img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* Section Global */
        .section-padding {
            padding: 80px 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }

        .section-title h3 {
            font-size: 2rem;
            color: var(--sage-dark);
            font-weight: 800;
            margin-bottom: 10px;
        }

        .section-title p {
            color: var(--gold-accent);
            font-weight: 600;
            font-size: 1rem;
        }

        /* Bio Section */
        .bio-section {
            background-color: var(--bg-white);
        }

        .bio-card {
            background-color: var(--sage-light);
            border-radius: var(--radius-main);
            padding: 40px;
            box-shadow: var(--shadow-soft);
            border: 1px solid rgba(132, 165, 157, 0.2);
        }

        .bio-features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .feature-item {
            background: var(--bg-white);
            padding: 20px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            gap: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.02);
        }

        .feature-item i {
            font-size: 1.5rem;
            color: var(--gold-accent);
            background-color: var(--sage-soft);
            width: 50px;
            height: 50px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 50%;
        }

        .feature-item h4 {
            font-size: 1rem;
            color: var(--sage-dark);
        }

        .feature-item p {
            font-size: 0.85rem;
            color: var(--text-muted);
        }

        /* Services Section */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .service-card {
            background-color: var(--bg-white);
            padding: 35px 25px;
            border-radius: var(--radius-main);
            box-shadow: var(--shadow-soft);
            transition: var(--transition);
            border-top: 4px solid var(--sage-primary);
            position: relative;
        }

        .service-card:hover {
            transform: translateY(-8px);
            box-shadow: var(--shadow-hover);
        }

        .service-icon {
            width: 60px;
            height: 60px;
            background-color: var(--sage-soft);
            color: var(--sage-dark);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            margin-bottom: 20px;
        }

        .service-card h4 {
            font-size: 1.25rem;
            color: var(--sage-dark);
            margin-bottom: 12px;
            font-weight: 700;
        }

        .service-card p {
            color: var(--text-muted);
            font-size: 0.95rem;
            line-height: 1.6;
        }

        /* Form Section */
        .form-section {
            background-color: var(--bg-white);
        }

        .form-wrapper {
            max-width: 800px;
            margin: 0 auto;
            background-color: var(--sage-light);
            padding: 40px;
            border-radius: var(--radius-main);
            box-shadow: var(--shadow-soft);
            border: 1px solid rgba(82, 121, 111, 0.15);
        }

        .form-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        .form-group {
            display: flex;
            flex-direction: column;
            gap: 8px;
            margin-bottom: 20px;
        }

        .form-group.full-width {
            grid-column: span 2;
        }

        .form-group label {
            font-weight: 600;
            color: var(--sage-dark);
            font-size: 0.9rem;
        }

        .form-group input,
        .form-group select,
        .form-group textarea {
            padding: 12px 16px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-family: 'Tajawal', sans-serif;
            font-size: 0.95rem;
            outline: none;
            transition: var(--transition);
            background-color: var(--bg-white);
        }

        .form-group input:focus,
        .form-group select:focus,
        .form-group textarea:focus {
            border-color: var(--sage-primary);
            box-shadow: 0 0 0 3px rgba(82, 121, 111, 0.15);
        }

        .btn-submit {
            width: 100%;
            background: linear-gradient(135deg, var(--gold-accent), var(--gold-hover));
            color: #fff;
            padding: 14px;
            border: none;
            border-radius: 30px;
            font-size: 1.1rem;
            font-weight: 700;
            cursor: pointer;
            transition: var(--transition);
            box-shadow: 0 4px 15px rgba(197, 160, 89, 0.3);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .btn-submit:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(197, 160, 89, 0.4);
        }

        /* Footer */
        footer {
            background-color: var(--sage-dark);
            color: #fff;
            padding: 50px 0 20px;
        }

        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }

        .footer-about h4 {
            font-size: 1.3rem;
            color: var(--gold-accent);
            margin-bottom: 15px;
        }

        .footer-about p {
            color: #cbd5e1;
            font-size: 0.9rem;
        }

        .footer-contact h5 {
            font-size: 1.1rem;
            margin-bottom: 15px;
            color: #fff;
        }

        .footer-contact p {
            color: #cbd5e1;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 0.95rem;
        }

        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 15px;
        }

        .social-links a {
            width: 40px;
            height: 40px;
            background-color: rgba(255,255,255,0.1);
            color: #fff;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            transition: var(--transition);
        }

        .social-links a:hover {
            background-color: var(--gold-accent);
            transform: translateY(-3px);
        }

        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255,255,255,0.1);
            color: #94a3b8;
            font-size: 0.85rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }

            .hero-grid {
                grid-template-columns: 1fr;
                text-align: center;
            }

            .hero-btns {
                justify-content: center;
            }

            .profile-frame {
                width: 260px;
                height: 320px;
            }

            .form-grid {
                grid-template-columns: 1fr;
            }

            .form-group.full-width {
                grid-column: span 1;
            }
        }
    </style>
</head>
<body>

    <!-- Header / Navbar -->
    <header>
        <div class="container nav-container">
            <a href="#" class="logo-brand">
                <img src="logo.png" alt="شعار خطوة للمقبل" onerror="this.src='https://via.placeholder.com/60?text=Logo'">
                <div class="brand-text">
                    <h1>خطوة للمُقبل</h1>
                    <span>عيادة التغذية العلاجية</span>
                </div>
            </a>

            <ul class="nav-links">
                <li><a href="#about">عن الأخصائية</a></li>
                <li><a href="#services">الخدمات العلاجية</a></li>
                <li><a href="#intake-form">استمارة المريض</a></li>
            </ul>

            <a href="https://wa.me/963932864065" class="btn-cta" target="_blank">
                <i class="fab font-awesome-icon fa-whatsapp"></i> احجز استشارتك
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container hero-grid">
            <div class="hero-text">
                <span class="tagline">🌿 خطوتك الأولى نحو صحة مستدامة</span>
                <h2>لصحةٍ تدوم.. تجعل العافية في حياتك <span>خطوة للمُقبل</span></h2>
                <p>مرحباً بك في منصتك الطبية المخصصة لبناء نمط حياة صحي متكامل، قائم على أحدث الأسس العلمية والتغذية العلاجية المحسوبة بدقة لملائمة احتياجات جسمك الفريدة.</p>
                
                <div class="hero-btns">
                    <a href="#intake-form" class="btn-cta">
                        <i class="fas fa-notes-medical"></i> تعبئة استمارة التقييم
                    </a>
                    <a href="https://wa.me/963932864065" class="btn-secondary" target="_blank">
                        <i class="fab fa-whatsapp"></i> تواصل مباشر
                    </a>
                </div>
            </div>

            <div class="hero-image">
                <div class="profile-frame">
                    <img src="profile.jpg" alt="أخصائية التغذية إسراء المقبل" onerror="this.src='https://via.placeholder.com/300x400?text=Dt.+Esraa'">
                </div>
            </div>
        </div>
    </section>

    <!-- Bio / About Section -->
    <section id="about" class="section-padding bio-section">
        <div class="container">
            <div class="section-title">
                <h3>الأخصائية إسراء منصور المقبل</h3>
                <p>خبرة أكاديمية ورعاية طبية مخصصة</p>
            </div>

            <div class="bio-card">
                <p style="font-size: 1.1rem; text-align: center; color: var(--text-dark); margin-bottom: 25px;">
                    خريجة جامعة حمص وحاصلة على دبلوم الصحة العامة. أؤمن بأن التغذية ليست حرمانًا، بل هي أسلوب حياة يصنع الفارق في صحتك البدنية والنفسية. أعمل على تقديم برامج غذائية علاجية متكاملة مصممة خصيصاً لكل حالة.
                </p>

                <div class="bio-features">
                    <div class="feature-item">
                        <i class="fas fa-user-graduate"></i>
                        <div>
                            <h4>مؤهل أكاديمي</h4>
                            <p>جامعة حمص - دبلوم الصحة العامة</p>
                        </div>
                    </div>

                    <div class="feature-item">
                        <i class="fas fa-heartpulse"></i>
                        <div>
                            <h4>تغذية علاجيّة</h4>
                            <p>خطط مخصصة لمختلف الحالات الصحية</p>
                        </div>
                    </div>

                    <div class="feature-item">
                        <i class="fas fa-sliders"></i>
                        <div>
                            <h4>متابعة مستمرة</h4>
                            <p>دعم وتحليل دوري لضمان النتائج</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="section-padding">
        <div class="container">
            <div class="section-title">
                <h3>خدماتنا العلاجية</h3>
                <p>برامج مصممة بدقة علمية لترتقي بجودة حياتك</p>
            </div>

            <div class="services-grid">
                <!-- الخدمة 1 -->
                <div class="service-card">
                    <div class="service-icon"><i class="fas fa-weight"></i></div>
                    <h4>إدارة الوزن الذكية</h4>
                    <p>أنظمة مخصصة لزيادة أو تخسيس الوزن بدون حرمان، تعتمد على حساب السعرات الحرارية والمغذيات الكبرى والصغرى حسب طبيعة جسمك.</p>
                </div>

                <!-- الخدمة 2 -->
                <div class="service-card">
                    <div class="service-icon"><i class="fas fa-notes-medical"></i></div>
                    <h4>التغذية العلاجية للأمراض</h4>
                    <p>خطط غذائية مساندة لمرضى السكري، ضغط الدم، تكيس المبيضين، القولون العصبي، وارتفاع كوليسترول الدم لتحسين التحاليل الطبية.</p>
                </div>

                <!-- الخدمة 3 -->
                <div class="service-card">
                    <div class="service-icon"><i class="fas fa-apple-whole"></i></div>
                    <h4>تغذية الحوامل والمرضعات</h4>
                    <p>برامج غذائية آمنة تلبي احتياجات الأم والجنين وضمان نمو صحي وتوفير العناصر الغذائية الأساسية طوال فترة الحمل والرضاعة.</p>
                </div>

                <!-- الخدمة 4 -->
                <div class="service-card">
                    <div class="service-icon"><i class="fas fa-child"></i></div>
                    <h4>تغذية الأطفال واليافعين</h4>
                    <p>معالجة انتقائية الطعام، وتأخر النمو، وزيادة الوزن عند الأطفال بطرق حببة ومحفزة تضمن بناء بنية جسدية سليمة.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Intake Form Section -->
    <section id="intake-form" class="section-padding form-section">
        <div class="container">
            <div class="section-title">
                <h3>استمارة التقييم التغذوي الأولية</h3>
                <p>قُم بتعبئة بياناتك ليتم تحليل حالتك وإعداد البرنامج الأنسب لك</p>
            </div>

            <div class="form-wrapper">
                <form id="clinicForm" onsubmit="sendToWhatsApp(event)">
                    <div class="form-grid">
                        <div class="form-group">
                            <label for="fullName">الاسم الكامل *</label>
                            <input type="text" id="fullName" required placeholder="مثال: أحمد خالد">
                        </div>

                        <div class="form-group">
                            <label for="age">العمر *</label>
                            <input type="number" id="age" required placeholder="مثال: 25">
                        </div>

                        <div class="form-group">
                            <label for="gender">الجنس *</label>
                            <select id="gender" required>
                                <option value="">اختر الجنس</option>
                                <option value="أنثى">أنثى</option>
                                <option value="ذكر">ذكر</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="weight">الوزن الحالي (كغ) *</label>
                            <input type="number" id="weight" step="0.1" required placeholder="مثال: 70">
                        </div>

                        <div class="form-group">
                            <label for="height">الطول (سم) *</label>
                            <input type="number" id="height" required placeholder="مثال: 165">
                        </div>

                        <div class="form-group">
                            <label for="goal">الهدف الرئيسي *</label>
                            <select id="goal" required>
                                <option value="">اختر الهدف</option>
                                <option value="خسارة الوزن">خسارة الوزن</option>
                                <option value="زيادة الوزن والكتلة العضلية">زيادة الوزن والكتلة العضلية</option>
                                <option value="تغذية علاجية لمرض أو حالة صحية">تغذية علاجية لمرض أو حالة صحية</option>
                                <option value="تحسين نمط الحياة والصحة العامة">تحسين نمط الحياة والصحة العامة</option>
                            </select>
                        </div>

                        <div class="form-group full-width">
                            <label for="medicalHistory">هل تعاني من أي أمراض مزمنة أو مشاكل صحية؟</label>
                            <textarea id="medicalHistory" rows="3" placeholder="مثال: سكري، ضغط، قصور درقية، قولون عصبي... (اتركه فارغاً إذا لا يوجد)"></textarea>
                        </div>

                        <div class="form-group full-width">
                            <label for="notes">ملاحظات إضافية أو تفضيلات غذائية</label>
                            <textarea id="notes" rows="2" placeholder="أي معلومات تحب مشاركتها مع الأخصائية..."></textarea>
                        </div>
                    </div>

                    <button type="submit" class="btn-submit">
                        <i class="fab fa-whatsapp"></i> إرسال الاستمارة إلى الأخصائية مباشرة
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-grid">
                <div class="footer-about">
                    <h4>خطوة للمُقبل</h4>
                    <p>عيادة التغذية العلاجية إشراف أخصائية التغذية إسراء منصور المقبل. هدفنا أن نكون خطوتك الأولى والواثقة نحو عافية مستدامة.</p>
                </div>

                <div class="footer-contact">
                    <h5>تواصل معنا</h5>
                    <p><i class="fas fa-phone"></i> 0932864065</p>
                    <p><i class="fab fa-whatsapp"></i> +963 932 864 065</p>
                    <p><i class="fas fa-location-dot"></i> حمص، سوريا</p>
                </div>

                <div class="footer-social">
                    <h5>تابعنا على التواصل الاجتماعي</h5>
                    <div class="social-links">
                        <a href="https://instagram.com/Dt.Esraa_Almoqbel" target="_blank" title="Instagram"><i class="fab fa-instagram"></i></a>
                        <a href="https://facebook.com" target="_blank" title="Facebook"><i class="fab fa-facebook-f"></i></a>
                        <a href="https://wa.me/963932864065" target="_blank" title="WhatsApp"><i class="fab fa-whatsapp"></i></a>
                    </div>
                </div>
            </div>

            <div class="copyright">
                <p>جميع الحقوق محفوظة © 2026 لـ عيادة خطوة للمُقبل - أخصائية التغذية إسراء المقبل</p>
            </div>
        </div>
    </footer>

    <!-- JavaScript Script -->
    <script>
        function sendToWhatsApp(e) {
            e.preventDefault();
            
            const name = document.getElementById('fullName').value;
            const age = document.getElementById('age').value;
            const gender = document.getElementById('gender').value;
            const weight = document.getElementById('weight').value;
            const height = document.getElementById('height').value;
            const goal = document.getElementById('goal').value;
            const medicalHistory = document.getElementById('medicalHistory').value || 'لا يوجد';
            const notes = document.getElementById('notes').value || 'لا يوجد';

            const phoneNumber = "963932864065";
            
            const message = `السلام عليكم أخصائية إسراء، أود إرسال استمارة تقييم جديدة من الموقع:%0A%0A` +
                            `👤 *الاسم:* ${name}%0A` +
                            `🎂 *العمر:* ${age} سنة%0A` +
                            `🚻 *الجنس:* ${gender}%0A` +
                            `⚖️ *الوزن:* ${weight} كغ%0A` +
                            `📏 *الطول:* ${height} سم%0A` +
                            `🎯 *الهدف:* ${goal}%0A` +
                            `🏥 *التاريخ الطبي:* ${medicalHistory}%0A` +
                            `📝 *ملاحظات:* ${notes}`;

            const whatsappUrl = `https://wa.me/${phoneNumber}?text=${message}`;
            window.open(whatsappUrl, '_blank');
        }
    </script>
</body>
</html>
