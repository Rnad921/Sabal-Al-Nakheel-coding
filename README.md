# Sabal-Al-Nakheel
 "سبل النخيل" هي منصة تكنولوجية تهدف إلى تطوير قطاع التمور باستخدام تقنيات الذكاء الاصطناعي والحلول التكنولوجية المتقدمة. تعمل المنصة على أتمتة عمليات الحصاد والتصنيع من خلال روبوتات متطورة وتقنيات حديثة للفرز والجودة، مما يسهم في تقليل التكاليف، وتحسين كفاءة الإنتاج، وضمان أعلى مستويات الجودة في المنتجات النهائية.
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منصة سبل النخيل</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Cairo', sans-serif;
            margin: 0;
            padding: 0;
            direction: rtl;
            background-color: #f9f5e3;
            color: #4b3621;
        }

        header {
            background-color: #4b3621;
            color: #f9f5e3;
            padding: 20px;
            text-align: center;
            font-size: 24px;
        }

        .logo {
            font-size: 36px;
            font-weight: bold;
        }

        nav a {
            color: #f9f5e3;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .language-switch button {
            background-color: #4b3621;
            border: none;
            color: #f9f5e3;
            padding: 10px;
            margin: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        .language-switch button:hover {
            background-color: #6b4f3b;
        }

        .content {
            padding: 40px 20px;
            text-align: center;
        }

        .services {
            display: flex;
            justify-content: space-around;
            margin-top: 40px;
            padding: 20px;
            background-color: #f4efe3;
        }

        .service-box {
            background-color: #ffffff;
            border: 1px solid #e0d9c8;
            border-radius: 10px;
            padding: 20px;
            width: 30%;
            text-align: center;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .login-box {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            margin: 40px auto;
        }

        .login-box input[type="text"], .login-box input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }

        .login-box button {
            background-color: #4b3621;
            color: #f9f5e3;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 18px;
            width: 100%;
        }

        footer {
            background-color: #4b3621;
            color: #f9f5e3;
            padding: 10px;
            text-align: center;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="logo">مرحباً بكم في سبل النخيل🌴</div>
        <nav>
            <a href="#home">الرئيسية</a>
            <a href="#services">خدماتنا</a>
            <a href="#about">عن المنصة</a>
            <a href="#contact">اتصل بنا</a>
        </nav>

        <!-- Language Switch Buttons -->
        <div class="language-switch">
            <button onclick="switchLanguage('ar')">العربية</button>
            <button onclick="switchLanguage('en')">English</button>
            <button onclick="switchLanguage('fr')">Français</button>
            <button onclick="switchLanguage('bn')">বাংলা</button>
            <button onclick="switchLanguage('hi')">हिन्दी</button>
        </div>
    </header>

    <!-- Main Content -->
    <div class="content">
        <h1 id="main-title"></h1>
        <p id="main-description"></p>

        <!-- Services Section -->
        <div class="services" id="services">
            <div class="service-box">
                <h3 id="service1-title"></h3>
                <p id="service1-description"></p>
            </div>
            
            <div class="service-box">
                <h3 id="service3-title"></h3>
                <p id="service3-description"></p>
            </div>
        </div>

        <!-- Login Form -->
        <div class="login-box">
            <h2 id="login-title"></h2>
            <form>
                <input type="text" id="username" placeholder="اسم المستخدم" required>
                <input type="password" id="password" placeholder="كلمة المرور" required>
                <button type="submit">دخول</button>
            </form>
        </div>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>جميع الحقوق محفوظة © 2024 - منصة سبل النخيل</p>
    </footer>

         <!-- JavaScript to Switch Languages -->
    <script>
        const translations = {
            ar: {
                mainTitle: "مرحباً بكم في سبل النخيل",
                mainDescription: "نقدم حلولًا متقدمة لتحسين سلسلة الإمداد الخاصة بالتمور من خلال الذكاء الاصطناعي والحلول التكنولوجية المتطورة.",
                service1Title: "الأتمتة الذكية في الحصاد",
                service1Description: "نعتمد على الروبوتات المزودة بالذكاء الاصطناعي لتحديد التمور الناضجة وجمعها دون تدخل بشري.",
                service3Title: "التصنيع والابتكار",
                service3Description: "نقدم تقنيات متقدمة لتحسين عملية التصنيع والفرز، ما يساعد في رفع جودة المنتجات النهائية.",
                loginTitle: "تسجيل الدخول",
                usernamePlaceholder: "اسم المستخدم",
                passwordPlaceholder: "كلمة المرور",
                loginButton: "دخول"
            },
            en: {
                mainTitle: "Welcome to Sabal Al-Nakheel",
                mainDescription: "We offer advanced solutions to improve the date supply chain through AI and cutting-edge technological solutions.",
                service1Title: "Smart Automation in Harvesting",
                service1Description: "We rely on AI-powered robots to identify and collect ripe dates without human intervention.",
                service3Title: "Manufacturing and Innovation",
                service3Description: "We offer advanced technologies to improve the manufacturing and sorting process, helping raise the quality of final products.",
                loginTitle: "Login",
                usernamePlaceholder: "Username",
                passwordPlaceholder: "Password",
                loginButton: "Login"
            },
            fr: {
                mainTitle: "Bienvenue à Sabal Al-Nakheel",
                mainDescription: "Nous proposons des solutions avancées pour améliorer la chaîne d'approvisionnement des dattes grâce à l'IA et des solutions technologiques de pointe.",
                service1Title: "Automatisation intelligente de la récolte",
                service1Description: "Nous utilisons des robots alimentés par l'IA pour identifier et récolter les dattes mûres sans intervention humaine.",
                service3Title: "Fabrication et Innovation",
                service3Description: "Nous proposons des technologies avancées pour améliorer le processus de fabrication et de tri, ce qui permet d'améliorer la qualité des produits finaux.",
                loginTitle: "Connexion",
                usernamePlaceholder: "Nom d'utilisateur",
                passwordPlaceholder: "Mot de passe",
                loginButton: "Connexion"
            },
            bn: {
                mainTitle: "সাবল আল-নাখিল এ স্বাগতম",
                mainDescription: "আমরা AI এবং অত্যাধুনিক প্রযুক্তিগত সমাধানের মাধ্যমে খেজুর সরবরাহ শৃঙ্খল উন্নত করতে উন্নত সমাধান সরবরাহ করি।",
                service1Title: "ফসল কাটায় স্মার্ট অটোমেশন",
                service1Description: "আমরা AI-চালিত রোবটগুলির উপর নির্ভর করি যা পাকা খেজুর সনাক্ত এবং সংগ্রহ করতে সক্ষম।",
                service3Title: "উত্পাদন এবং উদ্ভাবন",
                service3Description: "আমরা উত্পাদন এবং বাছাই প্রক্রিয়া উন্নত করার জন্য উন্নত প্রযুক্তি অফার করি, যা চূড়ান্ত পণ্যের গুণমান বাড়াতে সহায়ক।",
                loginTitle: "লগইন",
                usernamePlaceholder: "ব্যবহারকারীর নাম",
                passwordPlaceholder: "পাসওয়ার্ড",
                loginButton: "লগইন"
            },
            hi: {
                mainTitle: "सबाल अल-नखील में आपका स्वागत है",
                mainDescription: "हम एआई और अत्याधुनिक तकनीकी समाधानों के माध्यम से खजूर आपूर्ति श्रृंखला में सुधार के लिए उन्नत समाधान प्रदान करते हैं।",
                service1Title: "स्मार्ट ऑटोमेशन फसल में",
                service1Description: "हम एआई-संचालित रोबोटों पर निर्भर करते हैं जो बिना मानव हस्तक्षेप के पके खजूर की पहचान और एकत्र करते हैं।",
                service3Title: "विनिर्माण और नवाचार",
                service3Description: "हम विनिर्माण और छंटाई प्रक्रिया में सुधार के लिए उन्नत तकनीक की पेशकश करते हैं, जो अंतिम उत्पादों की गुणवत्ता बढ़ाने में मदद करती है।",
                loginTitle: "लॉगिन करें",
                usernamePlaceholder: "उपयोगकर्ता नाम",
                passwordPlaceholder: "पासवर्ड",
                loginButton: "लॉगिन करें"
            }
        };

        function switchLanguage(lang) {
            document.getElementById('main-title').textContent = translations[lang].mainTitle;
            document.getElementById('main-description').textContent = translations[lang].mainDescription;
            document.getElementById('service1-title').textContent = translations[lang].service1Title;
            document.getElementById('service1-description').textContent = translations[lang].service1Description;
            document.getElementById('service3-title').textContent = translations[lang].service3Title;
            document.getElementById('service3-description').textContent = translations[lang].service3Description;
            document.getElementById('login-title').textContent = translations[lang].loginTitle;
            document.getElementById('username').placeholder = translations[lang].usernamePlaceholder;
            document.getElementById('password').placeholder = translations[lang].passwordPlaceholder;
            document.querySelector('button[type="submit"]').textContent = translations[lang].loginButton;
        }

        // Set default language to Arabic (ar)
        window.onload = function() {
            switchLanguage('ar');
        };
    </script>

</body>
</html>
