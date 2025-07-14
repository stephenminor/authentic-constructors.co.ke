
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Authentic Constructors Kenya</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --primary: #00553A;
      --secondary: #F9A825;
      --bg-light: #f4f6f8;
      --text-dark: #333;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--bg-light);
      color: var(--text-dark);
      scroll-behavior: smooth;
    }

    /* Updated header */
    header {
      background-color: white;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 0 20px rgba(0,0,0,0.1);
      animation: fadeIn 2s ease-in-out;
    }

    header i {
      font-size: 48px;
      color: var(--secondary);
      margin-bottom: 10px;
      animation: bounce 2s infinite;
    }

    header h1 {
      font-size: 2.4em;
      color: var(--primary);
      margin: 10px 0 5px;
    }

    header h2 {
      font-size: 1.3em;
      color: var(--secondary);
      margin-bottom: 10px;
    }

    header p {
      max-width: 700px;
      margin: 0 auto;
      font-size: 1em;
    }

    nav {
      background-color: var(--primary);
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 15px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 16px;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--secondary);
    }

    section {
      padding: 60px 30px;
      max-width: 1200px;
      margin: 0 auto;
    }

    h1, h2 {
      text-align: center;
      color: var(--primary);
    }

    .services-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      margin-top: 40px;
    }

    .service-card {
      background: #fff;
      flex: 1 1 280px;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      animation: fadeInUp 1s ease forwards;
    }

    .service-card:hover {
      transform: translateY(-6px);
      box-shadow: 0 12px 24px rgba(0,0,0,0.15);
    }

    .service-card i {
      font-size: 32px;
      color: var(--secondary);
      margin-bottom: 15px;
      display: block;
      text-align: center;
    }

    .service-card h3 {
      margin-top: 0;
      text-align: center;
      color: var(--primary);
    }

    .service-card p {
      color: #555;
      text-align: center;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
  </style>
</head>
<body>

  <!-- New Branded Header -->
  <header>
    <i class="fas fa-building"></i>
    <h1>Authentic Constructors</h1>
    <h2>Building Services and Consultation</h2>
    <p>Delivering quality, structure, and style — from blueprint to finish.</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#services">Services</a>
    <a href="#">Projects</a>
    <a href="#">Contact</a>
  </nav>

  <section>
    <h1>Welcome to Authentic Constructors Kenya</h1>
    <p style="text-align: center; max-width: 800px; margin: auto;">
      From concept to completion, we deliver construction excellence with integrity and creativity.
    </p>

    <h2 id="services">Our Services</h2>
    <div class="services-grid">
      <div class="service-card">
        <i class="fas fa-drafting-compass"></i>
        <h3>Building Consultation</h3>
        <p>Precision-driven drawings and layout plans for flawless execution.</p>
      </div>

      <div class="service-card">
        <i class="fas fa-couch"></i>
        <h3>Interior Design</h3>
        <p>Spaces styled to inspire—tailored finishes and elegant layouts.</p>
      </div>

      <div class="service-card">
        <i class="fas fa-hard-hat"></i>
        <h3>Construction Works</h3>
        <p>Reliable construction backed by expert tools and supervision.</p>
      </div>

      <div class="service-card">
        <i class="fas fa-wrench"></i>
        <h3>Welding & Fabrication</h3>
        <p>Durable steelwork using SHS and precision detailing.</p>
      </div>

      <div class="service-card">
        <i class="fas fa-ruler-combined"></i>
        <h3>Bar Bending</h3>
        <p>Reinforcement schedules built for structural strength.</p>
      </div>

      <div class="service-card">
        <i class="fas fa-tree"></i>
        <h3>Landscaping</h3>
        <p>Outdoor beauty designed to harmonize with every structure.</p>
      </div>

      <div class="service-card">
        <i class="fas fa-paint-roller"></i>
        <h3>Painting</h3>
        <p>Premium coatings for aesthetic finish.</p>
      </div>

      <div class="service-card">
        <i class="fas fa-toilet"></i>
        <h3>Drainage & Sanitation</h3>
        <p>Clean water systems and funtional drainange pipes to ensure hygiene.</p>
      </div>

      <div class="service-card">
        <i class="fas fa-road"></i>
        <h3>Carbo Paving</h3>
        <p>Masterpac-enhanced surfaces for long-lasting performance.</p>
      </div>

      <div class="service-card">
        <i class="fas fa-faucet"></i>
        <h3>Plumbing</h3>
        <p>Efficient water flow and installation you can trust.</p>
      </div>

      <div class="service-card">
        <i class="fas fa-hammer"></i>
        <h3>Carpentry</h3>
        <p>Refined joinery and craftsmanship using premium materials.</p>
      </div>
    </div>
  </section><!-- PDF Interaction Options -->
<div style="text-align: center; margin-top: 60px;">

  <!-- Download Button -->
  <a href="Presentation 5.pdf" download style="
    display: inline-block;
    padding: 14px 28px;
    background-color: var(--primary);
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: bold;
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  ">
    📄 Download Company Profile (PDF)
  </a>

  <!-- View Button -->
  <div style="margin-top: 20px;">
    <a href="Presentation 5.pdf" target="_blank" style="
      display: inline-block;
      padding: 12px 24px;
      background-color: var(--secondary);
      color: black;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
    ">
      👁️ View Company Profile Online
    </a>
  </div>
</div>

<!-- Embedded PDF Preview -->
<section style="max-width: 1000px; margin: 60px auto;">
  <h2 style="text-align: center; color: var(--primary);">Preview Our Company Profile</h2>
  <iframe 
    src="Presentation 5.pdf"
    width="100%" 
    height="600px" 
    style="border: 1px solid #ccc; border-radius: 8px;">
    This browser does not support embedded PDFs. 
    <a href="Presentation 5.pdf" target="_blank">Download it instead.</a>
  </iframe>
</section>


</body>
</html>
