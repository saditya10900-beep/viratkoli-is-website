
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>King Kohli | Aditya Singh</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #080d18;
      color: white;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 22px 8%;
      background: #05080f;
      border-bottom: 1px solid #252b39;
    }

    .logo {
      font-size: 25px;
      color: #f8c44f;
      font-weight: bold;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 18px;
      font-size: 14px;
    }

    nav a:hover {
      color: #f8c44f;
    }

    .hero {
      min-height: 80vh;
      padding: 80px 8%;
      display: flex;
      align-items: center;
      background:
        radial-gradient(ellipse at 80% 45%, #17416a 0%, transparent 40%),
        linear-gradient(120deg, #080d18, #101d31);
    }

    .hero-content {
      max-width: 700px;
    }

    .tag {
      color: #f8c44f;
      letter-spacing: 4px;
      font-weight: bold;
    }

    h1 {
      font-size: clamp(48px, 9vw, 88px);
      margin: 20px 0 10px;
      line-height: 1;
    }

    h1 span {
      color: #f8c44f;
    }

    .hero p {
      color: #d0d6e1;
      font-size: 18px;
      line-height: 1.8;
      margin: 24px 0;
    }

    .btn {
      display: inline-block;
      background: #f8c44f;
      color: #10131a;
      padding: 14px 24px;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      cursor: pointer;
    }

    .btn:hover {
      background: white;
    }

    section.content {
      padding: 70px 8%;
      text-align: center;
    }

    .section-title {
      font-size: 36px;
      margin-bottom: 15px;
    }

    .description {
      max-width: 750px;
      margin: 0 auto 30px;
      color: #c1c9d7;
      line-height: 1.8;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
      gap: 20px;
      margin-top: 35px;
    }

    .card {
      background: #111a2a;
      border: 1px solid #26334a;
      border-radius: 12px;
      padding: 30px 20px;
      transition: transform 0.25s;
    }

    .card:hover {
      transform: translateY(-6px);
      border-color: #f8c44f;
    }

    .card .icon {
      font-size: 38px;
      margin-bottom: 15px;
    }

    .card h3 {
      color: #f8c44f;
      margin-bottom: 12px;
    }

    .card p {
      color: #c1c9d7;
      line-height: 1.6;
    }

    .highlight {
      background: #0d1422;
    }

    .quote {
      font-size: 25px;
      font-style: italic;
      color: #f8c44f;
      max-width: 750px;
      margin: 25px auto;
      line-height: 1.6;
    }

    #fanMessage {
      margin-top: 25px;
      color: #f8c44f;
      line-height: 1.8;
    }

    footer {
      text-align: center;
      padding: 30px 15px;
      background: #05080f;
      color: #aeb8c9;
      line-height: 2;
    }

    @media (max-width: 700px) {
      header {
        flex-direction: column;
        gap: 18px;
      }

      nav {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 15px;
      }

      nav a {
        margin: 0;
      }

      .hero {
        min-height: 70vh;
        padding: 60px 7%;
      }

      section.content {
        padding: 55px 7%;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">👑 KING KOHLI</div>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#career">Career</a>
      <a href="#records">Records</a>
      <a href="#fans">Fans</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="hero-content">
        <div class="tag">THE KING OF CRICKET</div>

        <h1>VIRAT<br><span>KOHLI</span></h1>

        <p>
          Passion. Discipline. Dedication.<br>
          A tribute to one of India's most loved
          cricketers, created by Aditya Singh.
        </p>

        <a href="#about" class="btn">EXPLORE HIS JOURNEY →</a>
      </div>
    </section>

    <section class="content" id="about">
      <h2 class="section-title">About Virat Kohli</h2>

      <p class="description">
        Virat Kohli is an Indian international cricketer,
        admired for his batting, determination and
        competitive spirit. His journey inspires millions
        of cricket fans around the world.
      </p>

      <div class="cards">
        <div class="card">
          <div class="icon">🇮🇳</div>
          <h3>Team India</h3>
          <p>A celebrated Indian international cricketer.</p>
        </div>

        <div class="card">
          <div class="icon">🏏</div>
          <h3>Right-Hand Batter</h3>
          <p>Known for consistency and aggressive batting.</p>
        </div>

        <div class="card">
          <div class="icon">👑</div>
          <h3>King Kohli</h3>
          <p>A fan-favourite name recognised around the world.</p>
        </div>
      </div>
    </section>

    <section class="content highlight" id="career">
      <h2 class="section-title">His Cricket Journey</h2>

      <p class="description">
        From representing India at the Under-19 level
        to becoming a leading figure in international
        cricket, Virat Kohli has built an extraordinary
        career through hard work and dedication.
      </p>

      <div class="cards">
        <div class="card">
          <h3>2008</h3>
          <p>Led India to the Under-19 World Cup title.</p>
        </div>

        <div class="card">
          <h3>India</h3>
          <p>Built a remarkable international career.</p>
        </div>

        <div class="card">
          <h3>IPL</h3>
          <p>A long-standing star of Royal Challengers Bengaluru.</p>
        </div>
      </div>
    </section>

    <section class="content" id="records">
      <h2 class="section-title">Legacy & Achievements</h2>

      <p class="description">
        Explore his memorable performances, international
        milestones, major trophies and cricket records.
        Verify current statistics from official cricket sources.
      </p>

      <div class="cards">
        <div class="card">
          <div class="icon">🏆</div>
          <h3>Major Trophies</h3>
          <p>Memorable achievements in international cricket.</p>
        </div>

        <div class="card">
          <div class="icon">💯</div>
          <h3>Centuries</h3>
          <p>Celebrated for outstanding batting performances.</p>
        </div>

        <div class="card">
          <div class="icon">🔥</div>
          <h3>Big Matches</h3>
          <p>Known for intensity under pressure.</p>
        </div>
      </div>
    </section>

    <section class="content highlight" id="fans">
      <h2 class="section-title">King Kohli Fans ❤️</h2>

      <p class="quote">
        "Never stop working hard for your dreams."
      </p>

      <p class="description">
        Made with passion by Aditya Singh, for cricket fans.
      </p>

      <button class="btn" onclick="showMessage()">
        I'M A KOHLI FAN ❤️
      </button>

      <p id="fanMessage" aria-live="polite"></p>
    </section>
  </main>

  <footer>
    <p>👑 KING KOHLI — FAN WEBSITE</p>
    <p>Created by Aditya Singh | © 2026</p>
    <p>Unofficial fan page. Not affiliated with Virat Kohli or BCCI.</p>
  </footer>

  <script>
    function showMessage() {
      document.getElementById("fanMessage").textContent =
        "Thank you for supporting King Kohli! 🏏❤️";
    }
  </script>

</body>
</html>
