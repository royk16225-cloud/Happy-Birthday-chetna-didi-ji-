<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Chetna Didi!</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(135deg, #fff5f7 0%, #ffe3ec 50%, #f0e6ff 100%);
            font-family: 'Poppins', sans-serif;
            color: #4a3e3d;
            min-height: 100vh;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            max-width: 900px;
            width: 100%;
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(10px);
            border-radius: 24px;
            box-shadow: 0 15px 35px rgba(230, 100, 150, 0.15);
            padding: 40px 25px;
            border: 2px solid rgba(255, 182, 193, 0.4);
            position: relative;
            overflow: hidden;
        }

        .flower-decor {
            position: absolute;
            font-size: 2.5rem;
            opacity: 0.25;
            user-select: none;
            animation: float 6s ease-in-out infinite;
        }

        .f1 { top: 15px; left: 20px; animation-delay: 0s; }
        .f2 { top: 20px; right: 25px; animation-delay: 2s; }
        .f3 { bottom: 20px; left: 20px; animation-delay: 4s; }
        .f4 { bottom: 15px; right: 25px; animation-delay: 1s; }

        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-10deg) rotate(8deg); }
        }

        header {
            text-align: center;
            margin-bottom: 35px;
        }

        h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 3.5rem;
            color: #d63384;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.05);
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1.1rem;
            color: #885053;
            letter-spacing: 1px;
            font-weight: 600;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .photo-card {
            background: #ffffff;
            padding: 12px;
            border-radius: 18px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: center;
            border: 1px solid #ffe3ec;
        }

        .photo-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 12px 25px rgba(214, 51, 132, 0.2);
        }

        .photo-card img {
            width: 100%;
            height: 320px;
            object-fit: cover;
            border-radius: 12px;
        }

        .photo-card p {
            margin-top: 10px;
            font-size: 0.9rem;
            color: #b05279;
            font-weight: 600;
        }

        .wish-box {
            background: linear-gradient(145deg, #ffffff, #fff0f5);
            padding: 30px;
            border-radius: 20px;
            border-left: 6px solid #d63384;
            box-shadow: 0 6px 18px rgba(0,0,0,0.04);
            position: relative;
        }

        .wish-title {
            font-size: 1.4rem;
            color: #d63384;
            margin-bottom: 15px;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .wish-text {
            font-size: 1.05rem;
            line-height: 1.8;
            color: #4a3e3d;
        }

        .wish-text p {
            margin-bottom: 12px;
        }

        .highlight-line {
            background-color: #ffe6ee;
            padding: 8px 14px;
            border-radius: 8px;
            color: #c2185b;
            font-weight: 600;
            display: inline-block;
            margin: 8px 0;
            border: 1px dashed #f48fb1;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 0.95rem;
            color: #885053;
            font-weight: 500;
        }

        @media (max-width: 600px) {
            h1 { font-size: 2.8rem; }
            .container { padding: 25px 15px; }
            .photo-card img { height: 280px; }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Floating Floral Icons -->
        <div class="flower-decor f1">🌷</div>
        <div class="flower-decor f2">🌸</div>
        <div class="flower-decor f3">🌺</div>
        <div class="flower-decor f4">🌷</div>

        <header>
            <h1>Happy Birthday Chetna Didi! 🌷</h1>
            <p class="subtitle">🌷 Tulips & Lilies Special Birthday Wishes 🌸</p>
        </header>

        <!-- Photo Gallery -->
        <div class="gallery">
            <div class="photo-card">
                <img src="7934.jpg" alt="Chetna Didi Photo 1">
                <p>Cool & Charming Didi ✨</p>
            </div>
            <div class="photo-card">
                <img src="7951.jpg" alt="Chetna Didi Photo 2">
                <p>Always Pretty & Elegant 🌺</p>
            </div>
            <div class="photo-card">
                <img src="7907.jpg" alt="Chetna Didi Photo 3">
                <p>Stylish & Awesome 💫</p>
            </div>
        </div>

        <!-- Birthday Message -->
        <div class="wish-box">
            <div class="wish-title">
                <span>🌷</span> Sweet Birthday Wishes For You
            </div>
            <div class="wish-text">
                <p>Happy Birthday Chetna Didi! 🥳 Aap humesha aise hi muskurati raho aur aapki life tulips aur lilies ki tarah humesha khilkhilati aur mehakti rahe!</p>
                
                <p class="highlight-line">
                    Bhagwan tujhe etna sara paisa de aur tera sapna pura ho tu teacher bane aur mere bachho ko padhaye! 👩‍🏫💰
                </p>

                <p>Aap jo bhi mehnat kar rahi ho, usme aapko bohot badi success mile. Aapki life me kabhi kisi cheez ki kami na ho aur har khushi aapke paas aaye. Party hard and enjoy your special day to the fullest! 🎂🎉✨</p>
            </div>
        </div>

        <footer>
            <p>Made with ❤️ for Chetna Didi</p>
        </footer>
    </div>

</body>
</html>
# Happy-Birthday-chetna-didi-ji-
Happy- birthday-chetna
