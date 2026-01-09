# restaurant-website
My restaurant website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Royal Spice Restaurant</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fffaf5;
      color: #333;
    }
    header {
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1552566626-52f8b828add9');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 80px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 20px;
    }
    nav {
      background: #8b0000;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .menu {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .card h3 {
      margin-top: 0;
      color: #8b0000;
    }
    .contact {
      background: #f5e9da;
      border-radius: 12px;
      padding: 30px;
    }
    footer {
      background: #8b0000;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Royal Spice Restaurant</h1>
    <p>Delicious Food • Cozy Ambience • Pure Taste</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>
      Welcome to <b>Royal Spice Restaurant</b>, where taste meets tradition. 
      We serve fresh, hygienic and delicious food made with love and authentic spices.
    </p>
  </section>

  <section id="menu">
    <h2>Our Popular Menu</h2>
    <div class="menu">
      <div class="card">
        <h3>Paneer Butter Masala</h3>
        <p>Rich & creamy curry with fresh paneer.</p>
      </div>
      <div class="card">
        <h3>Biryani Special</h3>
        <p>Slow cooked rice with aromatic spices.</p>
      </div>
      <div class="card">
        <h3>Butter Naan</h3>
        <p>Soft & fluffy naan with butter.</p>
      </div>
      <div class="card">
        <h3>Cold Drinks & Desserts</h3>
        <p>Sweet ending to your meal.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <div class="contact">
      <p><b>📍 Address:</b> Main Market, Your City</p>
      <p><b>📞 Phone:</b> 9XXXXXXXXX</p>
      <p><b>⏰ Timing:</b> 10 AM – 11 PM</p>
    </div>
  </section>

  <footer>
    <p>© 2026 Royal Spice Restaurant | All Rights Reserved</p>
  </footer>

</body>
</html>
