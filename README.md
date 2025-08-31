<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>حسين طاهر | Hussein Taher</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Amiri:wght@700&family=Cairo:wght@600&display=swap');

    body {
      margin: 0;
      font-family: 'Cairo', sans-serif;
      background: radial-gradient(circle at center, rgba(255,255,255,0.4) 0%, rgba(66,165,245,0.8) 40%, rgba(13,71,161,1) 100%);
      background-size: 200% 200%;
      animation: gradientMove 15s ease infinite;
      color: white;
      text-align: center;
      overflow-x: hidden;
    }
    @keyframes gradientMove {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }

    header {
      padding: 30px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
      position: relative;
    }

    .logo-313 {
      position: absolute;
      top: 10px;
      right: 15px;
      font-size: clamp(16px, 2vw, 22px);
      font-weight: bold;
      color: white;
      text-shadow: 0 0 8px #00bfff;
    }

    .profile-pic {
      width: clamp(90px, 15vw, 140px);
      height: clamp(90px, 15vw, 140px);
      border-radius: 50%;
      border: 4px solid white;
      box-shadow: 0 0 25px rgba(0, 191, 255, 0.9), 0 0 50px rgba(0, 191, 255, 0.5);
      animation: glow 2s infinite alternate;
      object-fit: cover;
    }
    @keyframes glow {
      from { box-shadow: 0 0 20px rgba(0, 191, 255, 0.6), 0 0 40px rgba(0, 191, 255, 0.3); }
      to { box-shadow: 0 0 35px rgba(0, 191, 255, 1), 0 0 70px rgba(0, 191, 255, 0.6); }
    }

    h1 {
      margin: 0;
      font-size: clamp(20px, 4vw, 32px);
      font-family: 'Amiri', serif;
      background: linear-gradient(90deg, #fff, #00e5ff, #fff);
      background-size: 200% auto;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: shine 4s linear infinite;
    }
    @keyframes shine {
      to {background-position: 200% center;}
    }

    .tagline {
      margin: 5px 0 0;
      font-size: clamp(12px, 2vw, 16px);
      color: #e1f5fe;
    }

    .links {
      margin: 30px auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 350px;
    }
    .link {
      padding: 14px;
      border-radius: 12px;
      text-decoration: none;
      color: white;
      font-size: 18px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      position: relative;
      overflow: hidden;
      transition: 0.3s;
    }
    .link:hover { transform: scale(1.05); }
    .link i { font-size: 20px; transition: transform 0.3s; }
    .link:hover i { transform: scale(1.2) rotate(5deg); }
    .link::after {
      content: "";
      position: absolute;
      inset: 0;
      background: linear-gradient(120deg, transparent, rgba(255,255,255,0.3), transparent);
      transform: translateX(-100%);
      transition: transform 0.6s;
    }
    .link:hover::after { transform: translateX(100%); }

    .instagram { background: linear-gradient(45deg, #f58529, #dd2a7b, #8134af, #515bd4); }
    .telegram  { background: linear-gradient(45deg, #29b6f6, #0288d1); }
    .whatsapp  { background: linear-gradient(45deg, #25D366, #128C7E); }
    .email     { background: linear-gradient(45deg, #ff4b2b, #ff416c); }

    footer {
      margin-top: 40px;
      padding: 15px;
      font-size: 15px;
      color: #cfd8dc;
      font-weight: bold;
      background: rgba(0,0,0,0.2);
      backdrop-filter: blur(4px);
    }
  </style>
</head>
<body>

<header>
  <div class="logo-313">313</div>
  <div>
    <img src="https://i.ibb.co/6cBkTBn8/IMG-20250827-011050-984.jpg" alt="صورة حسين طاهر" class="profile-pic">
  </div>
  <div>
    <h1>حسين طاهر | Hussein Taher</h1>
    <p class="tagline">منتج صوت عربي احترافي | دبلجة وتعليق صوتي بتقنيات متطورة</p>
  </div>
</header>

<div class="links">
  <a class="link instagram" href="https://www.instagram.com/313.h_t" target="_blank"><i class="fab fa-instagram"></i> Instagram | إنستغرام</a>
  <a class="link telegram" href="https://t.me/h313_t" target="_blank"><i class="fab fa-telegram"></i> Telegram | تلغرام</a>
  <a class="link whatsapp" href="https://wa.me/9647715812067" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp | واتساب</a>
  <a class="link email" href="mailto:mly482285@gmail.com" target="_blank"><i class="fas fa-envelope"></i> Email | إيميل</a>
</div>

<footer>
  © 1447هـ - 2025 منتج صوتي
</footer>

</body>
</html>
