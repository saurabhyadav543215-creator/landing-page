# landing-page
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Modern Landing Page</title>
  <style>
    :root {
      --primary: #2563eb;
      --dark: #0f172a;
      --muted: #64748b;
      --light: #f8fafc;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Inter', sans-serif; background: var(--light); color: var(--dark); }
    header { padding: 20px 40px; display: flex; justify-content: space-between; align-items: center; background: white; box-shadow: 0 2px 10px rgba(0,0,0,0.05); position: sticky; top: 0; }
    header h2 { font-size: 22px; font-weight: 700; }
    nav a { margin-left: 20px; text-decoration: none; color: var(--dark); font-size: 15px; }
    nav a:hover { color: var(--primary); }

    .hero { padding: 80px 40px; display: flex; align-items: center; justify-content: space-between; }
    .hero-text { max-width: 520px; }
    .hero-text h1 { font-size: 48px; line-height: 1.2; }
    .hero-text p { margin-top: 16px; font-size: 18px; color: var(--muted); }
    .hero-text button { margin-top: 26px; background: var(--primary); padding: 14px 24px; border: none; border-radius: 8px; color: white; cursor: pointer; font-size: 16px; }
    .hero-text button:hover { opacity: 0.9; }

    .hero img { width: 460px; border-radius: 16px; box-shadow: 0 10px 30px rgba(0,0,0,0.1); }

    .features { padding: 60px 40px; text-align: center; }
    .features h2 { font-size: 34px; }
    .features-grid { margin-top: 40px; display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 26px; }
    .card { background: white; padding: 26px; border-radius: 12px; box-shadow: 0 6px 20px rgba(0,0,0,0.06); }
    .card h3 { margin-bottom: 10px; font-size: 20px; }
    .card p { font-size: 15px; color: var(--muted); }

    footer { margin-top: 60px; padding: 20px; text-align: center; color: var(--muted); font-size: 14px; }
  </style>
</head>
<body>

<header>
  <h2>YourBrand</h2>
  <nav>
    <a href="#about">About</a>
    <a href="#features">Features</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <div class="hero-text">
    <h1>Build Anything With Confidence</h1>
    <p>Launch your product, service, or idea with a stunning landing page that converts visitors into customers.</p>
    <button>Get Started</button>
  </div>
  <img src="https://cdn.pixabay.com/photo/2015/01/08/18/29/startup-593327_1280.jpg" alt="Landing Image" />
</section>

<section id="features" class="features">
  <h2>Why Choose Us?</h2>
  <div class="features-grid">
    <div class="card">
      <h3>Fast Performance</h3>
      <p>Your landing page loads instantly, giving users a seamless experience.</p>
    </div>
    <div class="card">
      <h3>Responsive Design</h3>
      <p>Looks perfect on all devices — mobile, tablet, and desktop.</p>
    </div>
    <div class="card">
      <h3>Easy to Customize</h3>
      <p>Modify text, colors, and visuals effortlessly to match your brand.</p>
    </div>
  </div>
</section>

<footer>
  © 2025 YourBrand — All rights reserved.
</footer>

</body>
</html>
