<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sweet Bakes | Luxury Cakes & Bakes</title>
  <style>
    /* Reset & fonts */
    * {margin:0; padding:0; box-sizing:border-box;}
    body {font-family:'Segoe UI', sans-serif; background:#0b0b0b; color:#f5f5f5; line-height:1.6;}
    a {text-decoration:none;}
    h1,h2,h3 {margin-bottom:15px;}
    h1 {font-size:3em; letter-spacing:3px;}
    h2 {font-size:2.2em; color:#d4af37; margin-top:40px;}
    h3 {font-size:1.5em; color:#f0e6c8;}
    p {margin-bottom:15px; color:#d6d6d6;}

    /* Navigation */
    nav {background:#000; padding:18px; text-align:center; border-bottom:1px solid #d4af37;}
    nav a {color:#d4af37; margin:0 20px; font-weight:bold;}
    nav a:hover {color:#fff;}

    /* Header */
    header {text-align:center; padding:70px 20px;}
    header p {color:#f0e6c8; font-size:1.2em;}

    /* Sections */
    section {max-width:1000px; margin:40px auto; padding:0 20px;}

    /* Cards */
    .cards {display:grid; grid-template-columns:repeat(auto-fit, minmax(250px, 1fr)); gap:30px; margin-top:30px;}
    .card {background:#1a1a1a; border-radius:20px; padding:20px; text-align:center; transition: transform 0.3s; border:1px solid #d4af37;}
    .card:hover {transform:translateY(-8px);}
    .card img {width:100%; border-radius:15px; margin-bottom:15px;}

    /* CTA */
    .cta {text-align:center; background:#000; border:2px solid #d4af37; padding:80px 20px; border-radius:20px;}
    .cta a {display:inline-block; margin-top:25px; background:#d4af37; color:#000; padding:16px 40px; border-radius:50px; font-weight:bold;}
    .cta a:hover {background:#f5e1a4;}

    /* Footer */
    footer {background:#000; text-align:center; padding:30px; border-top:1px solid #d4af37; color:#d4af37;}

    /* Extra spacing for luxury feel */
    .spacer {height:40px;}
  </style>
</head>
<body>

<!-- Header -->
<header>
  <h1>Sweet Bakes</h1>
  <p>Luxury Cakes & Bakes Made with Love</p>
</header>

<!-- Navigation -->
<nav>
  <a href="#about">About</a>
  <a href="#cakes">Our Cakes</a>
  <a href="#order">Order</a>
</nav>

<!-- About Section -->
<section id="about">
  <h2>About Sweet Bakes</h2>
  <p>Sweet Bakes creates custom cakes and a wide range of freshly baked treats, all made with high-quality ingredients and care. From birthdays and special celebrations to everyday indulgences, every bake is crafted to delight in both taste and presentation.</p>

  <div class="cards">
    <div class="card">
      <h3>Our Story</h3>
      <p>Founded with passion, Sweet Bakes started as a home-based bakery to bring love and flavor into every celebration.</p>
    </div>
    <div class="card">
      <h3>Why Choose Us</h3>
      <p>We prioritize freshness, quality ingredients, and custom designs tailored to your event.</p>
    </div>
    <div class="card">
      <h3>Our Promise</h3>
      <p>Every bake is crafted with care, ensuring not just taste but an elegant presentation that impresses.</p>
    </div>
  </div>
</section>

<div class="spacer"></div>

<!-- Our Cakes Section -->
<section id="cakes">
  <h2>Our Cakes & Bakes</h2>
  <p>We offer a variety of baked delights perfect for all occasions. Photos will be updated soon!</p>

  <div class="cards">
    <div class="card">
      <img src="https://via.placeholder.com/400x250" alt="Birthday Cakes">
      <h3>Birthday Cakes</h3>
      <p>Custom designs with delicious flavors to make birthdays unforgettable.</p>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/400x250" alt="Custom Cakes">
      <h3>Custom Cakes</h3>
      <p>Tailored cakes for any celebration, crafted to your specifications.</p>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/400x250" alt="Cupcakes">
      <h3>Cupcakes</h3>
      <p>Perfect for parties or a sweet treat at home, freshly baked daily.</p>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/400x250" alt="Cookies & Treats">
      <h3>Cookies & Treats</h3>
      <p>Delightful cookies, pastries, and bite-sized sweets for every occasion.</p>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/400x250" alt="Dessert Boxes">
      <h3>Dessert Boxes</h3>
      <p>Curated boxes filled with our finest baked goods, ideal for gifts or events.</p>
    </div>
  </div>
</section>

<div class="spacer"></div>

<!-- Order Section -->
<section id="order">
  <h2>Order Your Bakes</h2>
  <p>Place your order easily through WhatsApp or phone. We respond quickly and help you design your perfect bake.</p>
  <div class="cta">
    <a href="https://wa.me/13463040641">💬 Order on WhatsApp</a>
    <p style="margin-top:20px;">📞 (346) 304-0641</p>
  </div>
</section>

<div class="spacer"></div>

<!-- Footer -->
<footer>
  <p>© 2025 Sweet Bakes • All Rights Reserved</p>
</footer>

</body>
</html>
