# Bradford-Home-Services-
Business Page for Bradford Home Services 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bradford Home Services | Reliable Local Home Repair</title>

  <meta name="description" content="Bradford Home Services offers plumbing, yard work, tree removal, pressure washing, and general home repairs. Reliable, affordable, no job too small.">
  <meta name="keywords" content="home services, plumbing, yard work, tree removal, pressure washing, handyman">

  <style>
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background: #f4f6f8;
      color: #222;
      line-height: 1.6;
    }

    /* HEADER */
    header {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: #123c66;
      color: #fff;
      padding: 20px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.15);
    }
    header h1 { margin: 0; font-size: 26px; }
    header p { margin: 6px 0 0; opacity: 0.9; }

    nav {
      margin-top: 12px;
      display: flex;
      gap: 18px;
      flex-wrap: wrap;
    }
    nav a {
      color: #fff;
      font-weight: 600;
      text-decoration: none;
      transition: 0.2s;
    }
    nav a:hover { color: #ffcc33; }

    /* HERO */
    .hero {
      background: linear-gradient(135deg, #123c66, #1f5d99);
      color: white;
      padding: 80px 20px;
      text-align: center;
    }
    .hero h2 { font-size: 40px; margin-bottom: 10px; }
    .hero p { font-size: 20px; margin-bottom: 30px; }
    .hero a {
      background: #ffcc33;
      color: #000;
      padding: 16px 28px;
      border-radius: 10px;
      font-size: 20px;
      font-weight: 700;
      text-decoration: none;
    }

    /* SECTIONS */
    section {
      max-width: 1100px;
      margin: auto;
      padding: 70px 20px;
    }
    h3 {
      font-size: 32px;
      margin-bottom: 20px;
      text-align: center;
    }

    /* SERVICES */
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 25px;
      margin-top: 40px;
    }
    .card {
      background: white;
      padding: 28px;
      border-radius: 16px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.08);
      text-align: center;
      font-weight: 600;
      transition: 0.3s;
    }
    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 15px 35px rgba(0,0,0,0.12);
    }

    /* WHY US */
    .why {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
      gap: 20px;
      margin-top: 40px;
    }
    .why div {
      background: white;
      padding: 24px;
      border-radius: 14px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.08);
    }

    /* CTA */
    .cta {
      background: #123c66;
      color: white;
      text-align: center;
      padding: 80px 20px;
    }
    .cta a {
      display: inline-block;
      margin-top: 20px;
      background: #ffcc33;
      color: black;
      padding: 16px 28px;
      border-radius: 10px;
      font-size: 20px;
      font-weight: 700;
      text-decoration: none;
    }

    /* CONTACT */
    form {
      max-width: 450px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 12px;
    }
    input, textarea {
      padding: 14px;
      border-radius: 10px;
      border: 1px solid #ccc;
      font-size: 16px;
    }
    button {
      background: #ffcc33;
      border: none;
      padding: 14px;
      border-radius: 10px;
      font-size: 18px;
      font-weight: 700;
      cursor: pointer;
    }

    /* FOOTER */
    footer {
      background: #111;
      color: #bbb;
      text-align: center;
      padding: 25px;
    }

    /* FLOATING CALL BUTTON */
    .call-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #ffcc33;
      color: black;
      padding: 16px 20px;
      border-radius: 50px;
      font-weight: 800;
      text-decoration: none;
      box-shadow: 0 10px 25px rgba(0,0,0,0.25);
      z-index: 2000;
    }
  </style>
</head>

<body>

<header>
  <h1>Bradford Home Services</h1>
  <p>Reliable • Affordable • No Job Too Small</p>
  <nav>
    <a href="#services">Services</a>
    <a href="#why">Why Us</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="hero">
  <h2>Home Repairs & Outdoor Work You Can Trust</h2>
  <p>Fast response. Fair pricing. Quality work.</p>
  <a href="tel:7069494767">📞 Call or Text 706-949-4767</a>
</div>

<section id="services">
  <h3>Our Services</h3>
  <div class="services">
    <div class="card">Plumbing Repairs</div>
    <div class="card">Tree Removal & Trimming</div>
    <div class="card">Yard Work & Cleanups</div>
    <div class="card">Pressure Washing</div>
    <div class="card">General Home Repairs</div>
    <div class="card">Seasonal Maintenance</div>
  </div>
</section>

<section id="why">
  <h3>Why Choose Bradford Home Services</h3>
  <div class="why">
    <div>✔ Local, honest, and dependable</div>
    <div>✔ Affordable pricing</div>
    <div>✔ Fast turnaround</div>
    <div>✔ No job too small</div>
  </div>
</section>

<div class="cta">
  <h3>Need Work Done Today?</h3>
  <p>Reach out now for a fast response and free estimate.</p>
  <a href="tel:7069494767">📞 Call or Text Now</a>
</div>

<section id="contact">
  <h3>Contact Us</h3>
  <form>
    <input type="text" placeholder="Your Name" required>
    <input type="tel" placeholder="Phone Number" required>
    <textarea placeholder="What do you need done?" rows="5" required></textarea>
    <button type="submit">Send Message</button>
  </form>
</section>

<footer>
  © 2026 Bradford Home Services • Serving Your Community
</footer>

<a href="tel:7069494767" class="call-float">📞 Call Now</a>

</body>
</html>