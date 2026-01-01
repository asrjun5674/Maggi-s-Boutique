maggi's boutique
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Maggi’s Boutique</title>

<style>
  body {
    margin: 0;
    font-family: "Poppins", Arial, sans-serif;
    background: #1a0b0b;
    color: #f5e7c6;
  }

  /* Shiny Gold Gradient */
  :root {
    --gold: linear-gradient(135deg,#e8cf7a,#d4b24c,#f6e8a3,#c9a32f);
    --maroon: #4a0f15;
  }

  header {
    background: var(--maroon);
    padding: 18px 60px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 10;
    box-shadow: 0 8px 20px rgba(0,0,0,.5);
  }

  .logo {
    font-size: 26px;
    font-weight: 700;
    background: var(--gold);
    -webkit-background-clip: text;
    color: transparent;
    letter-spacing: 1px;
  }

  nav a {
    text-decoration: none;
    margin-left: 28px;
    color: #f5e7c6;
    font-weight: 500;
  }

  .hero {
    background: radial-gradient(circle at top, #6d1c22, #1a0b0b);
    padding: 120px 60px;
    text-align: center;
  }

  .hero h1 {
    font-size: 58px;
    margin: 0;
    background: var(--gold);
    -webkit-background-clip: text;
    color: transparent;
  }

  .hero p {
    margin-top: 14px;
    font-size: 18px;
    color: #f3e8cc;
  }

  .btn {
    margin-top: 30px;
    padding: 12px 28px;
    border-radius: 40px;
    border: none;
    font-size: 16px;
    font-weight: 600;
    cursor: pointer;
    background: var(--gold);
    color: #4a0f15;
    box-shadow: 0 10px 20px rgba(0,0,0,.6);
  }

  .section {
    padding: 90px 60px;
  }

  .title {
    font-size: 34px;
    margin-bottom: 20px;
    background: var(--gold);
    -webkit-background-clip: text;
    color: transparent;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(260px,1fr));
    gap: 26px;
  }

  .card {
    background: #2a1012;
    border-radius: 18px;
    padding: 18px;
    box-shadow: 0 8px 22px rgba(0,0,0,.7);
    border: 1px solid rgba(255,215,150,.25);
  }

  footer {
    text-align: center;
    padding: 40px;
    background: #120607;
    color: #c9a87c;
  }
</style>
</head>

<body>

<header>
  <div class="logo">Maggi’s Boutique</div>
  <nav>
    <a href="#about">About</a>
    <a href="#collection">Collection</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Elegance in Every Thread</h1>
  <p>Premium Traditional • Ethnic • Designer Wear</p>
  <button class="btn">Explore Collection</button>
</section>

<section id="about" class="section">
  <h2 class="title">About Maggi’s Boutique</h2>
  <p>
    Discover handcrafted elegance, premium fabrics, and timeless ethnic fashion.
    Every outfit is curated with passion, grace, and modern sophistication.
  </p>
</section>

<section id="collection" class="section">
  <h2 class="title">Our Signature Collection</h2>

  <div class="grid">
    <div class="card">Sarees — Royal Maroon Series</div>
    <div class="card">Lehengas — Heritage Gold Edition</div>
    <div class="card">Anarkalis — Bridal Luxe Collection</div>
    <div class="card">Custom Tailored Designs</div>
  </div>
</section>

<section id="contact" class="section">
  <h2 class="title">Contact & Visit</h2>
  <p>Maggi’s Boutique • Premium Fashion Studio</p>
  <p>WhatsApp | Instagram | In-Store Visit</p>
</section>

<footer>
  © 2025 Maggi’s Boutique — All Rights Reserved
</footer>

</body>
</html>
