# wsfairexchange.github.io
WS FAIR EXCHANGE WEBSITE
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>WS FAIR EXCHANGE</title>
  <style>
    /* Reset and base */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f4ff; /* light blue background */
      color: #004080; /* dark blue text */
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    /* Navigation */
    nav {
      width: 100%;
      background: white;
      padding: 1rem 2rem;
      display: flex;
      align-items: center;
      position: fixed;
      top: 0;
      left: 0;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      z-index: 1000;
    }
    .hamburger {
      cursor: pointer;
      width: 25px;
      height: 18px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .hamburger div {
      height: 3px;
      background-color: #004080;
      border-radius: 2px;
    }
    /* Hero Section */
    .hero {
      margin-top: 80px; /* to avoid nav overlap */
      width: 90%;
      max-width: 1200px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
      padding: 2rem;
      display: flex;
      gap: 2rem;
      align-items: center;
      flex-wrap: wrap;
    }
    .hero img {
      flex: 1 1 400px;
      max-width: 400px;
      border-radius: 8px;
      object-fit: cover;
    }
    .hero-content {
      flex: 1 1 400px;
    }
    .hero-content h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    /* Services Section */
    .services {
      margin-top: 2rem;
      background: #004080;
      color: white;
      padding: 2rem;
      border-radius: 8px;
      width: 90%;
      max-width: 1200px;
      display: flex;
      align-items: center;
      gap: 1rem;
      font-size: 1.2rem;
    }
    .services-icon {
      width: 50px;
      height: 50px;
      background: white;
      color: #004080;
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
      font-weight: bold;
      font-size: 1.5rem;
      user-select: none;
    }
  </style>
</head>
<body>

  <nav>
    <div class="hamburger" aria-label="Open navigation menu" role="button" tabindex="0">
      <div></div>
      <div></div>
      <div></div>
    </div>
  </nav>

  <section class="hero">
    <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=800&q=80" alt="People exchanging money" />
    <div class="hero-content">
      <h1>Welcome to WS FAIR EXCHANGE</h1>
      <p>Your trusted partner for fair currency exchange and payments across all borders.</p>
    </div>
  </section>

  <section class="services">
    <div class="services-icon">S</div>
    <div>Our Services: Fast, Secure, and Reliable Money Exchange using MPESA & PayPal.</div>
  </section>

</body>
</html>
