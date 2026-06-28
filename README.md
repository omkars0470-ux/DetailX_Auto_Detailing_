<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DETAILX AUTO DETAILING STUDIO & WASHING</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: Arial, sans-serif;
      background: #0b1220;
      color: #fff;
      line-height: 1.6;
    }
    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
    }
    header {
      padding: 30px 0;
      text-align: center;
      background: linear-gradient(135deg, #111827, #1f2937);
      border-bottom: 2px solid #334155;
    }
    header img {
      max-width: 180px;
      margin-bottom: 15px;
    }
    h1 {
      font-size: 2.2rem;
      margin-bottom: 10px;
      color: #ffffff;
    }
    .subtitle {
      color: #cbd5e1;
      font-size: 1.1rem;
    }
    .hero {
      padding: 60px 0;
      text-align: center;
      background: linear-gradient(180deg, #0f172a, #111827);
    }
    .hero h2 {
      font-size: 2rem;
      margin-bottom: 15px;
    }
    .hero p {
      color: #cbd5e1;
      max-width: 700px;
      margin: auto;
    }
    .buttons {
      margin-top: 25px;
    }
    .btn {
      display: inline-block;
      padding: 12px 20px;
      margin: 8px;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }
    .btn-primary {
      background: #22c55e;
      color: #fff;
    }
    .btn-secondary {
      background: transparent;
      color: #fff;
      border: 1px solid #64748b;
    }
    section {
      padding: 50px 0;
    }
    h3 {
      font-size: 1.7rem;
      margin-bottom: 20px;
      color: #38bdf8;
      text-align: center;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }
    .card {
      background: #111827;
      padding: 20px;
      border-radius: 14px;
      border: 1px solid #1f2937;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
    .card h4 {
      margin-bottom: 10px;
      color: #fff;
    }
    .card p, .card li {
      color: #cbd5e1;
    }
    ul {
      list-style: disc;
      padding-left: 20px;
    }
    .contact p {
      margin-bottom: 10px;
      text-align: center;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #020617;
      color: #94a3b8;
      border-top: 1px solid #1f2937;
    }
    .logo-box {
      width: 180px;
      height: 90px;
      margin: 0 auto 15px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: #000;
      border-radius: 10px;
      overflow: hidden;
    }
    .logo-box img {
      max-width: 100%;
      max-height: 100%;
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <div class="logo-box">
        <img src="logo.png" alt="DETAILX Logo">
      </div>
      <h1>DETAILX AUTO DETAILING STUDIO & WASHING</h1>
      <div class="subtitle">Premium Car Wash and Detailing Service in Lonikand</div>
    </div>
  </header>

  <div class="hero">
    <div class="container">
      <h2>Clean Car, Happy Drive</h2>
      <p>
        Welcome to DETAILX AUTO DETAILING STUDIO & WASHING, your trusted destination for professional car wash, detailing, and shine care.
        We provide quality service that keeps your vehicle looking fresh, clean, and well-maintained.
      </p>
      <div class="buttons">
        <a href="tel:7770006332" class="btn btn-primary">Call Now</a>
        <a href="#contact" class="btn btn-secondary">Visit Us</a>
      </div>
    </div>
  </div>

  <section>
    <div class="container">
      <h3>About Us</h3>
      <div class="card">
        <p>
          We are dedicated to providing professional car care with attention to detail.
          Our team focuses on quality washing, interior cleaning, detailing, rubbing, and polishing to give your car the best treatment possible.
        </p>
      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <h3>Services</h3>
      <div class="grid">
        <div class="card"><h4>Car Wash</h4><p>Complete exterior cleaning for your vehicle.</p></div>
        <div class="card"><h4>Interior Cleaning</h4><p>Clean and fresh interior care for your car.</p></div>
        <div class="card"><h4>Car Detailing</h4><p>Premium care for deep cleaning and finishing.</p></div>
        <div class="card"><h4>Rubbing</h4><p>Improve the shine and finish of your car paint.</p></div>
        <div class="card"><h4>Polishing</h4><p>Restore smooth shine and fresh look.</p></div>
        <div class="card"><h4>Premium Shine Care</h4><p>Special care to make your vehicle stand out.</p></div>
      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <h3>Pricing</h3>
      <div class="grid">
        <div class="card"><h4>Sedan Car Wash</h4><p>₹250</p></div>
        <div class="card"><h4>SUV Car Wash</h4><p>₹300</p></div>
        <div class="card"><h4>Interior Cleaning</h4><p>As per condition</p></div>
        <div class="card"><h4>Detailing Packages</h4><p>Available on request</p></div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container contact">
      <h3>Contact Us</h3>
      <div class="card">
        <p><strong>Address:</strong> GATE NO-31/1/1, Near Autodrive Service Center, Alandi-Markal Road, Tulapur Phata, Lonikand</p>
        <p><strong>Phone:</strong> 7770006332 / 9561093939</p>
      </div>
    </div>
  </section>

  <footer>
    <p>DETAILX AUTO DETAILING STUDIO & WASHING</p>
  </footer>

</body>
</html>
