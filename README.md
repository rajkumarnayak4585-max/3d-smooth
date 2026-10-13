
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Raj Kumar Nayak | My Business</title>
  <style>
    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: white;
      background: #030817;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 8%;
      background: #071329;
      border-bottom: 1px solid #123d70;
    }

    .logo { color: #16caff; font-size: 23px; font-weight: bold; }

    a { color: white; text-decoration: none; }

    .hero {
      min-height: 75vh;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-around;
      gap: 30px;
      padding: 60px 8%;
      background: radial-gradient(ellipse at right, #103d81, #030817 65%);
    }

    h1 { font-size: clamp(38px, 6vw, 65px); margin: 15px 0; }
    h1 span { color: #12caff; }
    p { color: #c5d5ed; line-height: 1.8; }

    .btn {
      display: inline-block;
      background: #0789ff;
      padding: 13px 22px;
      border-radius: 30px;
      margin-top: 12px;
    }

    .art {
      width: 280px;
      height: 280px;
      display: grid;
      place-items: center;
      font-size: 100px;
      border: 2px solid #168fff;
      border-radius: 35px;
      background: linear-gradient(135deg, #153d80, #070d21);
      box-shadow: 0 0 45px #087dff55;
      animation: float 4s ease-in-out infinite;
      transform-style: preserve-3d;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0) rotateY(-8deg); }
      50% { transform: translateY(-18px) rotateY(8deg); }
    }

    section { padding: 55px 8%; text-align: center; }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .card {
      padding: 25px;
      background: #0a1730;
      border: 1px solid #164a80;
      border-radius: 18px;
      transition: transform .3s, box-shadow .3s;
    }

    .card:hover {
      transform: translateY(-10px) scale(1.02);
      box-shadow: 0 10px 30px #008cff33;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #071329;
    }

    @media (max-width: 600px) {
      header { padding: 18px 5%; }
      .hero { padding: 45px 6%; text-align: center; }
      .art { width: 220px; height: 220px; }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">RK.</div>
    <a href="#contact">Contact ↗</a>
  </header>

  <main>
    <div class="hero">
      <div>
        <p>👋 Namaste! Welcome to my website</p>
        <h1>Raj Kumar<br><span>Nayak</span></h1>
        <h2>Chhote Sapne, Bade Iraade 🚀</h2>
        <p>Main Class 9th ka student hoon.<br>
        Main technology seekh raha hoon aur
        apne business ideas par kaam kar raha hoon.</p>
        <a class="btn" href="#services">Explore My Website →</a>
      </div>
      <div class="art">🚀</div>
    </div>

    <section id="about">
      <h2>About Me 👨‍💻</h2>
      <p>Mera naam Raj Kumar Nayak hai.
      Mujhe technology, business aur coding mein interest hai.</p>
    </section>

    <section id="services">
      <h2>My Services</h2>
      <div class="cards">
        <div class="card">
          <h3>💻 Technology</h3>
          <p>Nayi technology seekhna.</p>
        </div>
        <div class="card">
          <h3>🌐 Website</h3>
          <p>Modern website banana seekhna.</p>
        </div>
        <div class="card">
          <h3>💡 Business Ideas</h3>
          <p>Naye ideas aur creative projects.</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <p>Mujhse business ya website ke baare mein baat karein.</p>
      <a class="btn"
         href="https://wa.me/?text=Hello%20Raj%20Kumar%20Nayak">
         WhatsApp par Message Karein
      </a>
    </section>
  </main>

  <footer>
    © 2026 Raj Kumar Nayak | Learn • Create • Grow
  </footer>

</body>
</html>

