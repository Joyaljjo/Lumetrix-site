<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lumetrix | AI. Illuminated.</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background: #0f0f1a;
      color: #f5f5f7;
    }
    header {
      background: rgba(26, 26, 46, 0.85);
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: fixed;
      width: 100%;
      z-index: 1000;
      animation: fadeIn 1.5s ease-in-out;
    }
    header h1 {
      font-size: 28px;
      color: #ffffff;
      animation: slideInTop 1.5s ease-in-out;
    }
    nav a {
      color: #ccc;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }
    .hero {
      text-align: center;
      padding: 120px 20px;
      background: url('https://images.unsplash.com/photo-1638762183522-0b8a4efb17fd?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
      position: relative;
      color: #ffffff;
    }
    .hero::after {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(15, 15, 26, 0.6);
      z-index: 0;
    }
    .hero h2, .hero p, .hero .hero-button {
      position: relative;
      z-index: 1;
    }
    .hero h2 {
      font-size: 48px;
      margin-bottom: 20px;
      animation: slideIn 2s ease-in-out;
    }
    .hero p {
      font-size: 20px;
      max-width: 600px;
      margin: 0 auto 30px;
      color: #ddd;
      animation: fadeInUp 2s ease-in-out;
    }
    .hero-button {
      background: #0ef;
      border: none;
      padding: 12px 24px;
      font-size: 16px;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s, transform 0.3s;
      animation: zoomIn 2s ease-in-out;
    }
    .hero-button:hover {
      background: #0ac;
      transform: scale(1.05);
    }
    .section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section h3 {
      font-size: 32px;
      margin-bottom: 20px;
      color: #ffffff;
      animation: fadeInUp 1.2s ease-in-out;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }
    .feature {
      background: #1e1e2f;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(255,255,255,0.05);
      transition: transform 0.3s;
      animation: fadeInUp 1.5s ease-in-out;
    }
    .feature:hover {
      transform: translateY(-10px);
    }
    .feature h4 {
      font-size: 22px;
      margin-bottom: 10px;
    }
    .feature p {
      font-size: 16px;
      color: #bbb;
    }
    .about-wrapper {
      display: flex;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .about-wrapper img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #0ef;
    }
    .founder-button {
      margin-top: 20px;
      background: #0ef;
      border: none;
      padding: 10px 20px;
      border-radius: 6px;
      font-size: 16px;
      cursor: pointer;
    }
    .founder-button:hover {
      background-color: #0ac;
    }
    footer {
      text-align: center;
      padding: 30px 20px;
      background: #1a1a2e;
      color: #888;
      animation: fadeIn 2s ease-in-out;
    }@keyframes slideIn {
  0% {opacity: 0; transform: translateX(-50px);}
  100% {opacity: 1; transform: translateX(0);}
}
@keyframes slideInTop {
  0% {opacity: 0; transform: translateY(-30px);}
  100% {opacity: 1; transform: translateY(0);}
}
@keyframes fadeInUp {
  0% {opacity: 0; transform: translateY(40px);}
  100% {opacity: 1; transform: translateY(0);}
}
@keyframes zoomIn {
  0% {opacity: 0; transform: scale(0.8);}
  100% {opacity: 1; transform: scale(1);}
}
@keyframes fadeIn {
  0% {opacity: 0;}
  100% {opacity: 1;}
}

  </style>
</head>
<body>
  <header>
    <h1>Lumetrix</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#features">Features</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section class="hero">
    <h2>AI. Illuminated.</h2>
    <p>Discover the future of artificial intelligence with Lumetrix — where precision, clarity, and smart technology shape a better tomorrow.</p>
    <button class="hero-button" onclick="window.open('https://example.com', '_blank')">Get Started</button>
  </section>  <section class="section" id="about">
    <h3>About Lumetrix</h3>
    <div class="about-wrapper">
      <img src="joyal-photo.jpg" alt="Joyal Jose">
      <div>
        <p><strong>Founder & CEO:</strong> Joyal Jose</p>
        <p>Lumetrix is a cutting-edge AI company located in the USA, focused on building transparent, ethical, and high-performance AI solutions. From smart automation to powerful analytics and generative tools, we light the way to innovation.</p>
        <button class="founder-button" onclick="alert('Joyal Jose is the visionary behind Lumetrix, committed to building a better world with ethical AI.')">Meet the Founder</button>
      </div>
    </div>
  </section>  <section class="section" id="features">
    <h3>Core Solutions</h3>
    <div class="features">
      <div class="feature">
        <h4>LumeCore</h4>
        <p>The foundation of Lumetrix intelligence — our powerful language and vision engine.</p>
      </div>
      <div class="feature">
        <h4>LumeGen</h4>
        <p>Generative AI tools for content creation, design, and innovation at scale.</p>
      </div>
      <div class="feature">
        <h4>LumeFlow</h4>
        <p>Workflow automation that boosts productivity and eliminates routine tasks.</p>
      </div>
      <div class="feature">
        <h4>LumeX</h4>
        <p>Real-time data insights and AI-driven decision support systems for businesses.</p>
      </div>
    </div>
  </section>  <footer id="contact">
    <p>© 2025 Lumetrix Technologies. All rights reserved.</p>
    <p>Contact: info@lumetrix.ai</p>
  </footer>
</body>
</html>
