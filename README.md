<!DOCTYPE html>
<html lang="am">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>ETHIO REAL | የህንፃ መሳሪያዎች</title>

  <meta name="description"
    content="ETHIO REAL - የህንፃ መሳሪያዎች፣ የቧንቧ እቃዎች እና የኤሌክትሪክ እቃዎች አቅራቢ">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f5f7fa;
      color: #222;
      line-height: 1.6;
    }

    /* HEADER */

    header {
      background: #111827;
      color: white;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 10px rgba(0,0,0,0.2);
    }

    .navbar {
      max-width: 1200px;
      margin: auto;
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #fbbf24;
    }

    .logo span {
      color: white;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-size: 15px;
      transition: 0.3s;
    }

    nav a:hover {
      color: #fbbf24;
    }

    /* HERO */

    .hero {
      background: linear-gradient(135deg, #111827, #1f2937);
      color: white;
      padding: 100px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 48px;
      margin-bottom: 20px;
      color: #fbbf24;
    }

    .hero p {
      max-width: 700px;
      margin: auto;
      font-size: 19px;
      margin-bottom: 30px;
    }

    .btn {
      display: inline-block;
      padding: 14px 28px;
      background: #fbbf24;
      color: #111827;
      text-decoration: none;
      font-weight: bold;
      border-radius: 6px;
      margin: 5px;
      transition: 0.3s;
    }

    .btn:hover {
      background: white;
      transform: translateY(-2px);
    }

    .btn-outline {
      background: transparent;
      border: 2px solid #fbbf24;
      color: #fbbf24;
    }

    .btn-outline:hover {
      background: #fbbf24;
      color: #111827;
    }

    /* SECTIONS */

    section {
      padding: 70px 20px;
    }

    .container {
      max-width: 1200px;
      margin: auto;
    }

    .section-title {
      text-align: center;
      margin-bottom: 45px;
    }

    .section-title h2 {
      font-size: 32px;
      color: #111827;
      margin-bottom: 10px;
    }

    .section-title p {
      color: #666;
    }

    /* SERVICES */

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 12px;
      text-align: center;
      box-shadow: 0 5px 20px rgba(0,0,0,0.08);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-8px);
    }

    .card .icon {
      font-size: 45px;
      margin-bottom: 15px;
    }

    .card h3 {
      margin-bottom: 12px;
      color: #111827;
    }

    /* ABOUT */

    .about {
      background: #111827;
      color: white;
    }

    .about-content {
      max-width: 850px;
      margin: auto;
      text-align: center;
    }

    .about h2 {
      color: #fbbf24;
      margin-bottom: 20px;
      font-size: 32px;
    }

    /* WHY US */

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .feature {
      background: white;
      padding: 25px;
      border-left: 5px solid #fbbf24;
      border-radius: 8px;
      box-shadow: 0 3px 12px rgba(0,0,0,0.06);
    }

    .feature h3 {
      margin-bottom: 10px;
    }

    /* CONTACT */

    .contact {
      background: #fbbf24;
      text-align: center;
    }

    .contact h2 {
      color: #111827;
      margin-bottom: 20px;
      font-size: 32px;
    }

    .contact p {
      font-size: 18px;
      margin: 10px 0;
    }

    .contact a {
      color: #111827;
      font-weight: bold;
      text-decoration: none;
    }

    /* FOOTER */

    footer {
      background: #111827;
      color: white;
      text-align: center;
      padding: 25px 15px;
    }

    footer span {
      color: #fbbf24;
    }

    /* FLOATING BUTTON */

    .whatsapp {
      position: fixed;
      bottom: 25px;
      right: 25px;
      background: #25D366;
      color: white;
      width: 60px;
      height: 60px;
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
      text-decoration: none;
      font-size: 25px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
      z-index: 999;
    }

    /* MOBILE */

    @media(max-width: 700px) {

      .navbar {
        flex-direction: column;
        gap: 12px;
      }

      nav a {
        margin: 0 8px;
        font-size: 14px;
      }

      .hero {
        padding: 70px 20px;
      }

      .hero h1 {
        font-size: 34px;
      }

      .hero p {
        font-size: 16px;
      }

      .section-title h2 {
        font-size: 27px;
      }
    }
  </style>
</head>

<body>

  <!-- HEADER -->

  <header>
    <div class="navbar">

      <div class="logo">
        ETHIO <span>REAL</span>
      </div>

      <nav>
        <a href="#home">መነሻ</a>
        <a href="#services">አገልግሎቶች</a>
        <a href="#about">ስለ እኛ</a>
        <a href="#contact">ያግኙን</a>
      </nav>

    </div>
  </header>


  <!-- HERO -->

  <section class="hero" id="home">

    <h1>ETHIO REAL</h1>

    <p>
      የህንፃ መሳሪያዎች፣
      የቧንቧ እቃዎች እና
      የኤሌክትሪክ እቃዎች
      በጥራት እና በተመጣጣኝ ዋጋ።
    </p>

    <a href="#contact" class="btn">
      ያግኙን
    </a>

    <a href="#services" class="btn btn-outline">
      እቃዎቻችንን ይመልከቱ
    </a>

  </section>


  <!-- SERVICES -->

  <section id="services">

    <div class="container">

      <div class="section-title">

        <h2>የምናቀርባቸው እቃዎች</h2>

        <p>
          ለህንፃዎ የሚያስፈልጉ የተለያዩ ጥራት ያላቸው እቃዎች
        </p>

      </div>


      <div class="services">

        <div class="card">

          <div class="icon">🏗️</div>

          <h3>የህንፃ መሳሪያዎች</h3>

          <p>
            ለቤት እና ለህንፃ ስራ
            የሚያስፈልጉ የተለያዩ
            መሳሪያዎች።
          </p>

        </div>


        <div class="card">

          <div class="icon">🚰</div>

          <h3>የቧንቧ እቃዎች</h3>

          <p>
            የውሃ ቧንቧዎች፣
            ፊቲንግ እና
            የተለያዩ የፕላምቢንግ እቃዎች።
          </p>

        </div>


        <div class="card">

          <div class="icon">⚡</div>

          <h3>የኤሌክትሪክ እቃዎች</h3>

          <p>
            ኬብሎች፣
            ስዊቾች፣
            ሶኬቶች እና
            ሌሎች የኤሌክትሪክ እቃዎች።
          </p>

        </div>


        <div class="card">

          <div class="icon">🚿</div>

          <h3>የመታጠቢያ እቃዎች</h3>

          <p>
            ዘመናዊ እና
            ጥራት ያላቸው
            የባኞ እና የመታጠቢያ እቃዎች።
          </p>

        </div>

      </div>

    </div>

  </section>


  <!-- ABOUT -->

  <section class="about" id="about">

    <div class="about-content">

      <h2>ስለ ETHIO REAL</h2>

      <p>
        ETHIO REAL ለደንበኞቻችን
        ጥራት ያላቸውን
        የህንፃ፣ የቧንቧ እና
        የኤሌክትሪክ እቃዎች
        በተመጣጣኝ ዋጋ
        ለማቅረብ የሚሰራ አቅራቢ ነው።
      </p>

      <br>

      <p>
        ዓላማችን ለነጋዴዎች እና
        ለደንበኞቻችን
        ታማኝ አቅርቦት
        እና ጥሩ አገልግሎት
        መስጠት ነው።
      </p>

    </div>

  </section>


  <!-- WHY US -->

  <section>

    <div class="container">

      <div class="section-title">

        <h2>ለምን ETHIO REAL?</h2>

        <p>
          ለእርስዎ የምንሰጣቸው ጥቅሞች
        </p>

      </div>


      <div class="features">

        <div class="feature">

          <h3>✅ ጥራት</h3>

          <p>
            ጥራት ያላቸው እቃዎች
            ለማቅረብ እንሰራለን።
          </p>

        </div>


        <div class="feature">

          <h3>💰 ተመጣጣኝ ዋጋ</h3>

          <p>
            በተመጣጣኝ ዋጋ
            ጥራት ያላቸውን
            እቃዎች ያግኙ።
          </p>

        </div>


        <div class="feature">

          <h3>🤝 ታማኝነት</h3>

          <p>
            ከደንበኞቻችን ጋር
            በታማኝነት እንሰራለን።
          </p>

        </div>


        <div class="feature">

          <h3>🚚 አገልግሎት</h3>

          <p>
            ፈጣን እና
            ጥሩ የደንበኛ
            አገልግሎት።
          </p>

        </div>

      </div>

    </div>

  </section>


  <!-- CONTACT -->

  <section class="contact" id="contact">

    <div class="container">

      <h2>ያግኙን</h2>

      <p>
        📞 ስልክ:
        <a href="tel:+251976213646">
          +251 976 213 646
        </a>
      </p>

      <p>
        💬 Telegram:
        @real_business76
      </p>

      <p>
        🎵 TikTok:
        @userbreal1234
      </p>

      <br>

      <a
        href="tel:+251976213646"
        class="btn"
      >
        📞 አሁን ይደውሉ
      </a>

    </div>

  </section>


  <!-- FOOTER -->

  <footer>

    <p>
      © 2026
      <span>ETHIO REAL</span>
      | All Rights Reserved
    </p>

    <p>
      ጥራት • ታማኝነት • ተመጣጣኝ ዋጋ
    </p>

  </footer>


  <!-- WHATSAPP BUTTON -->

  <a
    class="whatsapp"
    href="https://wa.me/251976213646"
    target="_blank"
    title="WhatsApp"
  >
    💬
  </a>


</body>
</html>
