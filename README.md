<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>THE TRADESMEN | General Contracting Services</title>
  <meta name="description" content="THE TRADESMEN provide reliable general contracting services including window washing, car washing, lawn mowing, and more." />
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: Arial, Helvetica, sans-serif; }
    body { background: #f5f5f5; color: #222; line-height: 1.6; }
    header { background: #111; color: #fff; padding: 2.5rem 1rem; text-align: center; }
    header h1 { font-size: 2.5rem; letter-spacing: 2px; }
    header p { margin-top: 0.75rem; font-size: 1.1rem; color: #ccc; }

    nav { background: #222; padding: 0.75rem; text-align: center; }
    nav a { color: #fff; margin: 0 1rem; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }

    section { padding: 3rem 1.5rem; max-width: 1100px; margin: auto; }
    .hero { text-align: center; }
    .hero h2 { font-size: 2rem; margin-bottom: 1rem; }
    .hero p { font-size: 1.1rem; max-width: 700px; margin: auto; }

    .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem; margin-top: 2rem; }
    .card { background: #fff; padding: 1.5rem; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); }
    .card h3 { margin-bottom: 0.5rem; }

    .cta { background: #111; color: #fff; text-align: center; padding: 3rem 1.5rem; }
    .cta h2 { margin-bottom: 1rem; }
    .cta a { display: inline-block; margin-top: 1rem; padding: 0.75rem 1.5rem; background: #f4c430; color: #111; text-decoration: none; font-weight: bold; border-radius: 5px; }
    .cta a:hover { background: #ddb021; }

    footer { background: #222; color: #ccc; text-align: center; padding: 1.5rem; font-size: 0.9rem; }

    .contact-form { max-width: 600px; margin: auto; }
    .contact-form label { display: block; margin-top: 1rem; font-weight: bold; }
    .contact-form input, .contact-form textarea { width: 100%; padding: 0.6rem; margin-top: 0.3rem; border-radius: 4px; border: 1px solid #ccc; }
    .contact-form button { margin-top: 1.5rem; padding: 0.75rem; width: 100%; background: #111; color: #fff; border: none; font-size: 1rem; border-radius: 5px; cursor: pointer; }
    .contact-form button:hover { background: #333; }
  </style>
</head>
<body>

  <header>
    <h1>THE TRADESMEN</h1>
    <p>Reliable General Contracting & Property Services</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="hero">
    <h2>Quality Work. Honest Pricing.</h2>
    <p>THE TRADESMEN provide dependable, professional general contracting services for homes and businesses. Whether you need routine maintenance or one-time help, we show up on time and get the job done right.</p>
  </section>

  <section id="services">
    <h2 style="text-align:center;">Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>Window Washing</h3>
        <p>Interior and exterior window cleaning for homes and small businesses.</p>
      </div>
      <div class="card">
        <h3>Car Washing & Detailing</h3>
        <p>Hand wash, interior cleaning, and basic detailing at your location.</p>
      </div>
      <div class="card">
        <h3>Lawn Mowing & Yard Care</h3>
        <p>Grass cutting, edging, leaf cleanup, and basic landscaping.</p>
      </div>
      <div class="card">
        <h3>Pressure Washing</h3>
        <p>Driveways, sidewalks, decks, fences, and siding.</p>
      </div>
      <div class="card">
        <h3>General Labor</h3>
        <p>Moving help, cleanup, small repairs, and custom jobs.</p>
      </div>
      <div class="card">
        <h3>Custom Requests</h3>
        <p>Have a job not listed? Contact us and we’ll see how we can help.</p>
      </div>
    </div>
  </section>

  <section class="cta">
    <h2>Need Work Done?</h2>
    <p>Contact THE TRADESMEN today for a fast, free estimate.</p>
    <a href="#contact">Get a Quote</a>
  </section>

  <section id="contact">
    <h2 style="text-align:center;">Contact Us</h2>
    <form class="contact-form">
      <label>Name</label>
      <input type="text" placeholder="Your name" required />

      <label>Email</label>
      <input type="email" placeholder="Your email" required />

      <label>Message</label>
      <textarea rows="5" placeholder="Tell us what you need" required></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 THE TRADESMEN. All rights reserved.</p>
  </footer>

</body>
</html>
