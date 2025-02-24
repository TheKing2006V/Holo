<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="MoulayDrissAcademy - Unleashing Potential, Igniting Passion. Join us to explore creativity and innovation.">
  <meta name="keywords" content="MoulayDrissAcademy, education, creativity, passion, learning">
  <meta name="author" content="MoulayDrissAcademy">
  <meta property="og:title" content="MoulayDrissAcademy">
  <meta property="og:description" content="Unleashing Potential, Igniting Passion. Join us today!">
  <meta property="og:image" content="https://i.imgur.com/O3amwqv.jpeg">
  <meta property="og:url" content="https://moulaydrissacademy.com">
  <meta name="twitter:card" content="summary_large_image">
  <title>MoulayDrissAcademy</title>
  <link rel="preload" href="https://i.imgur.com/O3amwqv.jpeg" as="image">
  <link rel="preload" href="https://i.imgur.com/JjtC431.png" as="image">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&family=Bungee+Spice&family=Open+Sans:wght@400;700&family=Tajawal:wght@400;700&family=Cinzel:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-gradient: linear-gradient(135deg, #FFC107, #FF4500, #FFC107);
      --dark-bg: #121212;
      --text-color: #fff;
      --shadow: 0 8px 15px rgba(0, 0, 0, 0.5);
      --rounded: 25px;
      --transition: 0.3s ease;
    }
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      color: var(--text-color);
      background: var(--dark-bg);
      overflow-x: hidden;
      line-height: 1.6;
      transition: all 0.3s ease;
    }
    [lang="ar"] body {
      font-family: 'Tajawal', sans-serif;
      direction: rtl;
    }
    h1, h2, h3 {
      font-family: 'Bungee Spice', cursive;
      background: var(--primary-gradient);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-size: 3rem;
      margin-bottom: 10px;
    }
    [lang="ar"] h1, [lang="ar"] h2, [lang="ar"] h3,
    [lang="fr"] h1, [lang="fr"] h2, [lang="fr"] h3 {
      background: var(--primary-gradient);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    [lang="ar"] h1, [lang="ar"] h2, [lang="ar"] h3 {
      font-family: 'Tajawal', sans-serif;
    }
    p {
      font-family: 'Open Sans', sans-serif;
    }
    [lang="ar"] p {
      font-family: 'Tajawal', sans-serif;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }
    .rounded {
      border-radius: var(--rounded);
    }
    #preloader {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: var(--dark-bg);
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 2000;
      opacity: 1;
      transition: opacity 0.5s ease;
    }
    #preloader.hidden {
      opacity: 0;
      pointer-events: none;
    }
    .loader {
      width: 50px;
      height: 50px;
      border: 5px solid #FF4500;
      border-top: 5px solid #FFC107;
      border-radius: 50%;
      animation: spin 1s linear infinite;
    }
    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
    .floating-bar {
      position: fixed;
      top: 20px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      gap: 20px;
      z-index: 1000;
    }
    .floating-bar .icon {
      font-size: 2rem;
      cursor: pointer;
      transition: transform var(--transition), box-shadow var(--transition);
    }
    .floating-bar .icon:hover {
      transform: scale(1.2);
      box-shadow: 0 0 15px rgba(255, 193, 7, 0.8);
    }
    .hero-section {
      position: relative;
      text-align: center;
      padding: 100px 20px;
      background: linear-gradient(135deg, #FF4500 0%, #1A1A1A 50%, #FF4500 100%);
      overflow: hidden;
    }
    [lang="ar"] .hero-section {
      text-align: center;
    }
    .hero-section-inner {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }
    .hero-section img {
      width: 100%;
      max-width: 600px;
      margin: 20px auto 0;
      display: block;
      box-shadow: var(--shadow);
      transition: transform var(--transition);
      border-radius: var(--rounded);
    }
    .hero-section img:hover {
      transform: scale(1.05);
    }
    .floating-icons .icon {
      position: absolute;
      font-size: 2rem;
      animation: float 5s infinite ease-in-out;
      opacity: 0.8;
      pointer-events: none;
    }
    .floating-icons .icon:nth-child(1) { top: 10%; left: 10%; animation-delay: 0s; }
    .floating-icons .icon:nth-child(2) { top: 40%; right: 15%; animation-delay: 1s; }
    .floating-icons .icon:nth-child(3) { bottom: 30%; left: 25%; animation-delay: 2s; }
    .floating-icons .icon:nth-child(4) { bottom: 10%; right: 10%; animation-delay: 3s; }
    .floating-icons .icon:nth-child(5) { top: 60%; left: 50%; animation-delay: 4s; }
    .floating-icons .icon:nth-child(6) { bottom: 50%; right: 40%; animation-delay: 5s; }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }
    .cta-button {
      background: var(--primary-gradient);
      color: white;
      border: 2px solid #FFC107;
      padding: 15px 30px;
      font-size: 1.2rem;
      border-radius: 50px;
      cursor: pointer;
      transition: transform var(--transition), box-shadow var(--transition);
      font-family: 'Bungee Spice', cursive;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin: 10px;
    }
    [lang="ar"] .cta-button {
      font-family: 'Tajawal', sans-serif;
    }
    .cta-button:hover {
      transform: scale(1.1);
      box-shadow: 0 8px 15px rgba(255, 193, 7, 0.5);
    }
    .auth-buttons {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }
    .modal, .about-us-modal {
      display: none;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: #222;
      padding: 30px;
      border-radius: var(--rounded);
      box-shadow: var(--shadow);
      z-index: 1000;
      text-align: center;
    }
    [lang="ar"] .modal, [lang="ar"] .about-us-modal {
      text-align: center;
    }
    .modal input {
      width: calc(100% - 20px);
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #444;
      border-radius: var(--rounded);
      background: #333;
      color: var(--text-color);
      text-align: center;
    }
    [lang="ar"] .modal input {
      text-align: center;
    }
    .modal button, .about-us-modal button {
      background: white;
      color: #FF4500;
      border: none;
      padding: 10px 20px;
      font-size: 1rem;
      border-radius: 50px;
      cursor: pointer;
      transition: transform var(--transition), box-shadow var(--transition);
      font-family: 'Bungee Spice', cursive;
    }
    [lang="ar"] .modal button, [lang="ar"] .about-us-modal button {
      font-family: 'Tajawal', sans-serif;
    }
    .modal button:hover, .about-us-modal button:hover {
      transform: scale(1.1);
      box-shadow: 0 8px 15px rgba(255, 69, 0, 0.5);
    }
    .overlay {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.8);
      z-index: 999;
    }
    .success-message {
      color: #00ff00;
      margin-top: 10px;
      display: none;
    }
    .programs {
      background: linear-gradient(135deg, #000, #FF4500, #000);
      padding: 50px 40px;
      margin: 100px 40px;
      border-radius: var(--rounded);
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.5s ease, transform 0.5s ease;
    }
    .programs.show {
      opacity: 1;
      transform: translateY(0);
    }
    .program-item {
      background: #222;
      padding: 20px;
      margin: 20px 0;
      border-radius: var(--rounded);
      text-align: center;
      transition: transform var(--transition), box-shadow var(--transition);
    }
    [lang="ar"] .program-item {
      text-align: center;
    }
    .program-item:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 15px rgba(255, 69, 0, 0.5);
    }
    .dot {
      width: 20px;
      height: 20px;
      background: #00f;
      border-radius: 50%;
      margin: 0 auto 20px;
      box-shadow: 0 0 15px rgba(0, 0, 255, 0.8);
      animation: pulse 2s infinite;
      cursor: pointer;
    }
    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
    footer {
      background: #1A1A1A;
      color: var(--text-color);
      padding: 30px 40px;
      text-align: center;
      border-radius: var(--rounded);
      margin: 100px 40px 40px;
    }
    [lang="ar"] footer {
      text-align: center;
    }
    footer a {
      color: var(--text-color);
      text-decoration: none;
      margin: 0 15px;
      transition: transform var(--transition), color var(--transition);
    }
    footer a:hover {
      transform: scale(1.1);
      color: #FFC107;
    }
    footer a:focus {
      outline: 2px solid #FFC107;
      outline-offset: 2px;
    }
    button:focus, .icon:focus {
      outline: 2px solid #FFC107;
      outline-offset: 2px;
    }
    #language-bar {
      position: fixed;
      top: 20px;
      right: 20px;
      z-index: 1000;
      display: flex;
      gap: 6px;
      padding: 3px 6px;
      background: linear-gradient(135deg, rgba(255, 193, 7, 0.2), rgba(255, 69, 0, 0.2));
      border-radius: 30px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }
    [lang="ar"] #language-bar {
      left: 20px;
      right: auto;
    }
    .lang-btn {
      width: 30px;
      height: 30px;
      background: #222;
      color: var(--text-color);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Poppins', sans-serif;
      font-size: 0.9rem;
      font-weight: 600;
      cursor: pointer;
      transition: transform var(--transition), box-shadow var(--transition), background var(--transition);
      border: 1px solid transparent;
    }
    .lang-btn:hover {
      transform: scale(1.1);
      box-shadow: 0 0 8px rgba(255, 193, 7, 0.8);
    }
    .lang-btn.active {
      background: var(--primary-gradient);
      border: 1px solid #FFC107;
      color: white;
      box-shadow: 0 0 12px rgba(255, 193, 7, 0.5);
    }
    #auth-window {
      display: none;
      position: relative;
      min-height: 100vh;
      background: linear-gradient(135deg, #FF4500 0%, #1A1A1A 50%, #FF4500 100%);
      padding: 40px 20px;
      overflow-y: auto;
      scroll-behavior: smooth;
      text-align: center;
    }
    [lang="ar"] #auth-window, [lang="fr"] #auth-window {
      text-align: center;
    }
    .auth-header {
      margin-bottom: 40px;
    }
    .auth-logo {
      width: 150px;
      margin: 0 auto;
      display: block;
    }
    .red-dot {
      width: 20px;
      height: 20px;
      background: #FF4500;
      border-radius: 50%;
      margin: 20px auto;
      box-shadow: 0 0 15px rgba(255, 69, 0, 0.8);
      animation: pulse 2s infinite;
      cursor: pointer;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 20px;
      max-width: 1000px;
      margin: 0 auto 40px;
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.5s ease, transform 0.5s ease;
    }
    .gallery.show {
      opacity: 1;
      transform: translateY(0);
    }
    .gallery img {
      width: 100%;
      height: 150px;
      border-radius: var(--rounded);
      object-fit: cover;
      box-shadow: var(--shadow);
      cursor: pointer;
      transition: all 0.3s ease;
    }
    .gallery img.enlarged {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: auto;
      height: auto;
      max-width: 90%;
      max-height: 90vh;
      z-index: 2000; /* Increased to ensure top layer */
      box-shadow: 0 0 30px rgba(0, 0, 0, 0.8);
      border-radius: var(--rounded);
    }
    .image-overlay {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: transparent; /* No darkening */
      z-index: 1500; /* Below image but above other elements */
      cursor: pointer;
    }
    .video-section {
      max-width: 640px;
      margin: 0 auto 40px;
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.5s ease, transform 0.5s ease;
    }
    .video-section.show {
      opacity: 1;
      transform: translateY(0);
    }
    .video-section iframe {
      width: 100%;
      height: 360px;
      border-radius: var(--rounded);
      box-shadow: var(--shadow);
    }
    .auth-footer {
      font-family: 'Cinzel', serif;
      font-size: 1.2rem;
      padding: 20px;
    }
    .auth-footer span {
      display: inline-block;
      animation: glow 2s infinite;
    }
    @keyframes glow {
      0%, 100% { text-shadow: 0 0 5px #FFC107; }
      50% { text-shadow: 0 0 15px #FFC107; }
    }
    @media (max-width: 768px) {
      h1 { font-size: 2.5rem; }
      .hero-section, #auth-window { padding: 60px 20px; }
      .programs { margin: 50px 20px; padding: 30px 20px; }
      footer { padding: 30px 20px; margin: 50px 20px 20px; }
      #language-bar { top: 10px; right: 10px; }
      [lang="ar"] #language-bar { left: 10px; right: auto; }
      .gallery { grid-template-columns: repeat(2, 1fr); }
      .video-section iframe { height: 200px; }
    }
  </style>
</head>
<body>
  <div id="preloader">
    <div class="loader"></div>
  </div>
  <div id="language-bar">
    <div class="lang-btn" data-lang="en">En</div>
    <div class="lang-btn" data-lang="ar">Ar</div>
    <div class="lang-btn" data-lang="fr">Fr</div>
  </div>
  <div class="floating-bar">
    <span class="icon" role="img" aria-label="Book" data-modal="book-modal" tabindex="0">📚</span>
    <span class="icon" role="img" aria-label="Basketball" data-modal="basketball-modal" tabindex="0">🏀</span>
    <span class="icon" role="img" aria-label="Lamp" data-modal="lamp-modal" tabindex="0">💡</span>
  </div>
  <section class="hero-section rounded" aria-labelledby="hero-title">
    <div class="floating-icons">
      <span class="icon" role="img" aria-label="Star">🌟</span>
      <span class="icon" role="img" aria-label="Book">📚</span>
      <span class="icon" role="img" aria-label="Paintbrush">🎨</span>
      <span class="icon" role="img" aria-label="Lightbulb">💡</span>
      <span class="icon" role="img" aria-label="Music Note">🎵</span>
      <span class="icon" role="img" aria-label="Brain">🧠</span>
    </div>
    <div class="hero-section-inner rounded">
      <h1 id="hero-title" data-translate="title">MoulayDrissAcademy</h1>
      <p data-translate="hero-subtitle">Unleashing Potential, Igniting Passion.</p>
      <button class="cta-button" id="get-started" data-translate="get-started">Get Started</button>
      <div class="auth-buttons">
        <button class="cta-button" id="join-us-btn" data-translate="join-us">Join Us</button>
        <button class="cta-button" id="sign-in-btn" data-translate="sign-in">Sign In</button>
      </div>
      <img src="https://i.imgur.com/O3amwqv.jpeg" alt="Featured Image" loading="lazy">
    </div>
  </section>
  <div class="overlay" id="overlay"></div>
  <div class="modal rounded" id="join-modal" aria-modal="true" role="dialog">
    <div class="modal-content">
      <h2 data-translate="join-us">Join Us</h2>
      <input type="text" id="join-username" placeholder="Username" required aria-label="Username" data-translate-placeholder="username">
      <input type="email" id="join-email" placeholder="Your Email" required aria-label="Email" data-translate-placeholder="your-email">
      <input type="email" id="join-verify-email" placeholder="Verify Your Email" required aria-label="Verify Email" data-translate-placeholder="verify-email">
      <button id="join-submit" data-translate="submit">Submit</button>
      <p id="join-error" style="color: red; display: none;" data-translate="error-message">Please fill out all fields correctly.</p>
      <p id="join-success" class="success-message" data-translate="join-success">Thank you for joining! You can now access the gallery.</p>
    </div>
  </div>
  <div class="modal rounded" id="signin-modal" aria-modal="true" role="dialog">
    <div class="modal-content">
      <h2 data-translate="sign-in">Sign In</h2>
      <input type="text" id="signin-username" placeholder="Username" required aria-label="Username" data-translate-placeholder="username">
      <input type="email" id="signin-email" placeholder="Your Email" required aria-label="Email" data-translate-placeholder="your-email">
      <input type="email" id="signin-verify-email" placeholder="Verify Your Email" required aria-label="Verify Email" data-translate-placeholder="verify-email">
      <button id="signin-submit" data-translate="submit">Submit</button>
      <p id="signin-error" style="color: red; display: none;" data-translate="error-message">Please fill out all fields correctly.</p>
      <p id="signin-success" class="success-message" data-translate="signin-success">Welcome back! You can now access the gallery.</p>
    </div>
  </div>
  <div id="content-container"></div>
  <div class="about-us-modal" id="about-us-modal">
    <div class="dot" data-close></div>
    <p data-translate="about-us">
      Our academy represents a groundbreaking initiative at Moulay Driss High School—a beacon of inspiration for students to dream bigger and aim higher. Today, Friday, February 21th at 11 PM, we proudly unveil the first beta version of our website. This milestone reflects weeks of relentless dedication from our team:  
      <br><br><strong>Othman Seffar:</strong> Developer and coder, who overcame challenges like limited resources and academic commitments to craft this platform.<br><br><strong>Mohammed Allali:</strong> In web design and arrangement of important data of versions and collection of necessary resources.<br><br><strong>Mehdi Achkame:</strong> Logistics and organization expert, ensuring seamless coordination and execution.<br><br>
      Despite obstacles, we poured our hearts into creating a functional, elegant, and meaningful platform for our school community.  
      <br><br>We humbly seek your support, feedback, and encouragement as we refine and expand this initiative. Your belief in our vision fuels our determination and inspires us to push beyond limits.  
      <br><br>From the depths of our hearts, we thank you for standing by us and believing in the transformative power of education. Together, we will achieve greatness and leave a lasting legacy for Moulay Driss High School. ❤️ 
    </p>
  </div>
  <div class="about-us-modal" id="book-modal">
    <div class="dot" data-close></div>
    <p data-translate="book-modal">📚 Book: Dive into the world of knowledge and creativity!</p>
  </div>
  <div class="about-us-modal" id="basketball-modal">
    <div class="dot" data-close></div>
    <p data-translate="basketball-modal">🏀 Basketball: Stay active and energized with sports!</p>
  </div>
  <div class="about-us-modal" id="lamp-modal">
    <div class="dot" data-close></div>
    <p data-translate="lamp-modal">💡 Idea: Spark innovation and bring your ideas to life!</p>
  </div>
  <footer class="rounded">
    <p data-translate="footer-copyright">© 2025 MoulayDrissAcademy. All rights reserved by the creator of the website Othman Seffar.</p>
    <div>
      <a href="#hero-title" data-section="home" data-translate="home">Home</a>
      <a href="#content-container" data-section="programs" data-translate="programs">Programs</a>
      <a href="#about-us-modal" data-section="about" data-translate="about-us-link">About Us</a>
      <a href="#content-container" data-section="contact" data-translate="contact">Contact</a>
    </div>
  </footer>
  <div id="auth-window">
    <div class="auth-header">
      <img src="https://i.imgur.com/JjtC431.png" alt="Logo" class="auth-logo">
      <div class="red-dot" id="back-to-home"></div>
    </div>
    <h2 data-translate="activity-memory">Activity and Memory ❤️</h2>
    <div class="gallery">
      <img src="https://i.imgur.com/hxXUhJL.jpeg" alt="Activity 1">
      <img src="https://i.imgur.com/9llmr7L.jpeg" alt="Activity 2">
      <img src="https://i.imgur.com/a6yf6ks.jpeg" alt="Activity 3">
      <img src="https://i.imgur.com/F3Un9tD.jpeg" alt="Activity 4">
      <img src="https://i.imgur.com/bvyXHqx.jpeg" alt="Activity 5">
      <img src="https://i.imgur.com/RIJ5RRQ.jpeg" alt="Activity 6">
      <img src="https://i.imgur.com/s6s0Ryz.jpeg" alt="Activity 7">
      <img src="https://i.imgur.com/ueDfSvp.jpeg" alt="Activity 8">
      <img src="https://i.imgur.com/EAKc8Gt.jpeg" alt="Activity 9">
      <img src="https://i.imgur.com/zA0Wn0Z.jpeg" alt="Activity 10">
    </div>
    <div class="video-section">
      <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
    </div>
    <div class="auth-footer" data-translate="believe">Believe in yourself <span>✨</span></div>
  </div>
  <div class="image-overlay" id="image-overlay"></div>

  <script>
    const translations = {
      en: {
        title: "MoulayDrissAcademy",
        "hero-subtitle": "Unleashing Potential, Igniting Passion.",
        "get-started": "Get Started",
        "join-us": "Join Us",
        "sign-in": "Sign In",
        "your-name": "Your Name",
        "your-email": "Your Email",
        "username": "Username",
        "verify-email": "Verify Your Email",
        submit: "Submit",
        "error-message": "Please fill out all fields correctly.",
        "join-success": "Thank you for joining! You can now access the gallery.",
        "signin-success": "Welcome back! You can now access the gallery.",
        "about-us": "Our academy represents a groundbreaking initiative at Moulay Driss High School—a beacon of inspiration for students to dream bigger and aim higher. Today, Friday, February 21th at 11 PM, we proudly unveil the first beta version of our website. This milestone reflects weeks of relentless dedication from our team:  <br><br><strong>Othman Seffar:</strong> Developer and coder, who overcame challenges like limited resources and academic commitments to craft this platform.<br><br><strong>Mohammed Allali:</strong> In web design and arrangement of important data of versions and collection of necessary resources.<br><br><strong>Mehdi Achkame:</strong> Logistics and organization expert, ensuring seamless coordination and execution.<br><br>Despite obstacles, we poured our hearts into creating a functional, elegant, and meaningful platform for our school community.  <br><br>We humbly seek your support, feedback, and encouragement as we refine and expand this initiative. Your belief in our vision fuels our determination and inspires us to push beyond limits.  <br><br>From the depths of our hearts, we thank you for standing by us and believing in the transformative power of education. Together, we will achieve greatness and leave a lasting legacy for Moulay Driss High School. ❤️",
        "book-modal": "📚 Book: Dive into the world of knowledge and creativity!",
        "basketball-modal": "🏀 Basketball: Stay active and energized with sports!",
        "lamp-modal": "💡 Idea: Spark innovation and bring your ideas to life!",
        "footer-copyright": "© 2025 MoulayDrissAcademy. All rights reserved by the creator of the website Othman Seffar.",
        home: "Home",
        programs: "Programs",
        "about-us-link": "About Us",
        contact: "Contact",
        "programs-title": "Our Programs",
        "content-creation": "Content Creation",
        "content-creation-desc": "Learn to create engaging content for various platforms.",
        activity: "Activity",
        "activity-desc": "Participate in fun and educational activities.",
        "communication-skills": "Communication & Soft Skills",
        "communication-skills-desc": "Develop essential communication and interpersonal skills.",
        "mental-games": "Mental Development Games",
        "mental-games-desc": "Enhance cognitive abilities through interactive games.",
        "contact-title": "Contact Us",
        "contact-email": "Email: seffarothman3@gmail.com",
        "contact-phone": "Phone: +212702533713",
        "activity-memory": "Activity and Memory ❤️",
        "believe": "Believe in yourself",
        "please-auth": "Please sign in or join us first!"
      },
      ar: {
        title: "أكاديمية مولاي إدريس",
        "hero-subtitle": "أطلق العنان للإمكانيات، أشعل الشغف.",
        "get-started": "ابدأ الآن",
        "join-us": "انضم إلينا",
        "sign-in": "تسجيل الدخول",
        "your-name": "اسمك",
        "your-email": "بريدك الإلكتروني",
        "username": "اسم المستخدم",
        "verify-email": "تأكيد بريدك الإلكتروني",
        submit: "إرسال",
        "error-message": "يرجى تعبئة جميع الحقول بشكل صحيح.",
        "join-success": "شكرًا لانضمامك! يمكنك الآن الوصول إلى المعرض.",
        "signin-success": "مرحبًا بعودتك! يمكنك الآن الوصول إلى المعرض.",
        "about-us": "تُمثل أكاديميتنا مبادرة رائدة في ثانوية مولاي إدريس، تُشكل منارة إلهام للطلاب كي يحلموا بطموحات أوسع ويسعوا إلى آفاق أعلى. في هذا اليوم، الجمعة 21 فبراير عند الساعة 11 مساءً، نفخر بإطلاق النسخة التجريبية الأولى من موقعنا الإلكتروني. يعكس هذا الإنجاز أسابيع من التفاني الدؤوب من قِبل فريقنا:  <br><br><strong>عثمان الصفار:</strong> مطور ومبرمج، تغلب على تحديات مثل محدودية الموارد والالتزامات الأكاديمية ليُصيغ هذه المنصة.<br><br><strong>محمد علالي:</strong> مختص في تصميم الويب وتنظيم بيانات الإصدارات الهامة وجمع الموارد الضرورية.<br><br><strong>مهدي أشكام:</strong> خبير في التنظيم واللوجستيات، ضمن التنسيق والتنفيذ السلسين.<br><br>رغم العوائق، بذلنا قصارى جهدنا لنُنشئ منصة عملية، أنيقة، وذات قيمة لمجتمع مدرستنا.  <br><br>نناشدكم بكل تواضع دعمكم، آراءكم، وتشجيعكم ونحن نعمل على تهيئة هذه المبادرة وتوسعتها. إيمانكم برؤيتنا يُغذي عزيمتنا ويُلهمنا لتخطي الحدود.  <br><br>من أعماق قلوبنا، نشكركم على دعمكم وثقتكم بقوة التعليم التحويلية. معًا، سنحقق العظمة ونترك إرثًا خالدًا لثانوية مولاي إدريس. ❤️",
        "book-modal": "📚 كتاب: انغمس في عالم المعرفة والإبداع!",
        "basketball-modal": "🏀 كرة السلة: حافظ على نشاطك وحيويتك مع الرياضة!",
        "lamp-modal": "💡 فكرة: أشعل شرارة الابتكار وحقق أفكارك على أرض الواقع!",
        "footer-copyright": "© 2025 أكاديمية مولاي إدريس. جميع الحقوق محفوظة لمبدع الموقع عثمان الصفار.",
        home: "الرئيسية",
        programs: "البرامج",
        "about-us-link": "من نحن",
        contact: "اتصل بنا",
        "programs-title": "برامجنا",
        "content-creation": "إنشاء المحتوى",
        "content-creation-desc": "تعلم كيفية إبداع محتوى جذاب لمختلف المنصات.",
        activity: "نشاط",
        "activity-desc": "شارك في أنشطة ممتعة وتعليمية.",
        "communication-skills": "مهارات التواصل والمهارات الناعمة",
        "communication-skills-desc": "طوّر مهارات التواصل الأساسية والتفاعل البيني.",
        "mental-games": "ألعاب التنمية العقلية",
        "mental-games-desc": "عزز قدراتك المعرفية من خلال ألعاب تفاعلية.",
        "contact-title": "تواصل معنا",
        "contact-email": "البريد الإلكتروني: seffarothman3@gmail.com",
        "contact-phone": "الهاتف: +212702533713",
        "activity-memory": "النشاط والذكريات ❤️",
        "believe": "آمن بنفسك",
        "please-auth": "يرجى تسجيل الدخول أو الانضمام أولاً!"
      },
      fr: {
        title: "Académie Moulay Driss",
        "hero-subtitle": "Libérer le potentiel, enflammer la passion.",
        "get-started": "Commencer",
        "join-us": "Rejoignez-nous",
        "sign-in": "Se connecter",
        "your-name": "Votre nom",
        "your-email": "Votre email",
        "username": "Nom d'utilisateur",
        "verify-email": "Vérifiez votre email",
        submit: "Soumettre",
        "error-message": "Veuillez remplir tous les champs correctement.",
        "join-success": "Merci de nous avoir rejoints ! Vous pouvez maintenant accéder à la galerie.",
        "signin-success": "Bon retour ! Vous pouvez maintenant accéder à la galerie.",
        "about-us": "Notre académie représente une initiative révolutionnaire au lycée Moulay Driss—un phare d’inspiration pour les élèves afin qu’ils rêvent plus grand et visent plus haut. Aujourd’hui, vendredi 21 février à 23h, nous dévoilons avec fierté la première version bêta de notre site web. Cette étape reflète des semaines de dévouement acharné de notre équipe :  <br><br><strong>Othman Seffar :</strong> Développeur et codeur, qui a surmonté des défis tels que des ressources limitées et des engagements académiques pour concevoir cette plateforme.<br><br><strong>Mohammed Allali :</strong> En conception web, organisation des données importantes des versions et collecte des ressources nécessaires.<br><br><strong>Mehdi Achkame :</strong> Expert en logistique et organisation, assurant une coordination et une exécution fluides.<br><br>Malgré les obstacles, nous avons mis tout notre cœur à créer une plateforme fonctionnelle, élégante et significative pour notre communauté scolaire.  <br><br>Nous sollicitons humblement votre soutien, vos retours et vos encouragements alors que nous affinons et développons cette initiative. Votre foi en notre vision nourrit notre détermination et nous inspire à repousser les limites.  <br><br>Du fond de nos cœurs, nous vous remercions de nous soutenir et de croire au pouvoir transformateur de l’éducation. Ensemble, nous atteindrons la grandeur et laisserons un héritage durable pour le lycée Moulay Driss. ❤️",
        "book-modal": "📚 Livre : Plongez dans le monde de la connaissance et de la créativité !",
        "basketball-modal": "🏀 Basket-ball : Restez actif et énergisé avec le sport !",
        "lamp-modal": "💡 Idée : Suscitez l’innovation et donnez vie à vos idées !",
        "footer-copyright": "© 2025 Académie Moulay Driss. Tous droits réservés par le créateur du site Othman Seffar.",
        home: "Accueil",
        programs: "Programmes",
        "about-us-link": "À propos",
        contact: "Contact",
        "programs-title": "Nos programmes",
        "content-creation": "Création de contenu",
        "content-creation-desc": "Apprenez à créer du contenu engageant pour diverses plateformes.",
        activity: "Activité",
        "activity-desc": "Participez à des activités amusantes et éducatives.",
        "communication-skills": "Communication et compétences douces",
        "communication-skills-desc": "Développez des compétences essentielles en communication et en relations interpersonnelles.",
        "mental-games": "Jeux de développement mental",
        "mental-games-desc": "Améliorez vos capacités cognitives grâce à des jeux interactifs.",
        "contact-title": "Contactez-nous",
        "contact-email": "Email : seffarothman3@gmail.com",
        "contact-phone": "Téléphone : +212702533713",
        "activity-memory": "Activité et Mémoire ❤️",
        "believe": "Crois en toi",
        "please-auth": "Veuillez vous connecter ou nous rejoindre d'abord !"
      }
    };

    const $ = (selector) => document.querySelector(selector);
    const $$ = (selector) => document.querySelectorAll(selector);

    let isAuthenticated = false;

    function translatePage(lang) {
      document.documentElement.lang = lang;
      $$('[data-translate]').forEach(el => {
        const key = el.dataset.translate;
        el.innerHTML = translations[lang][key];
      });
      $$('[data-translate-placeholder]').forEach(el => {
        const key = el.dataset.translatePlaceholder;
        el.placeholder = translations[lang][key];
      });
      if (lang === 'ar') {
        document.body.style.direction = 'rtl';
      } else {
        document.body.style.direction = 'ltr';
      }
      updateActiveLanguage(lang);
    }

    function updateActiveLanguage(lang) {
      $$('.lang-btn').forEach(btn => {
        if (btn.dataset.lang === lang) {
          btn.classList.add('active');
        } else {
          btn.classList.remove('active');
        }
      });
    }

    function showModal(modalId) {
      $$('.modal, .about-us-modal').forEach(modal => modal.style.display = 'none');
      $(`#${modalId}`).style.display = 'block';
      $('#overlay').style.display = 'block';
    }

    function closeModal(modalId) {
      $(`#${modalId}`).style.display = 'none';
      $('#overlay').style.display = 'none';
      $$('.modal p').forEach(p => p.style.display = 'none');
    }

    const sanitizeInput = (input) => {
      const parser = new DOMParser();
      const doc = parser.parseFromString(input, 'text/html');
      return doc.body.textContent || '';
    };

    const validateEmail = (email) => /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email);

    function handleAuthSubmit(type) {
      const username = sanitizeInput($(`#${type}-username`).value.trim());
      const email = sanitizeInput($(`#${type}-email`).value.trim());
      const verifyEmail = sanitizeInput($(`#${type}-verify-email`).value.trim());
      const errorMessage = $(`#${type}-error`);
      const successMessage = $(`#${type}-success`);
      const lang = document.documentElement.lang || 'en';

      if (!username || !email || !verifyEmail || email !== verifyEmail || !validateEmail(email)) {
        errorMessage.textContent = translations[lang]["error-message"];
        errorMessage.style.display = 'block';
        successMessage.style.display = 'none';
        return;
      }

      errorMessage.style.display = 'none';
      successMessage.innerHTML = translations[lang][`${type}-success`];
      successMessage.style.display = 'block';
      isAuthenticated = true;
      setTimeout(() => closeModal(`${type}-modal`), 2000);
    }

    function loadSection(section) {
      const container = $('#content-container');
      const lang = document.documentElement.lang || 'en';
      container.innerHTML = '';

      if (section === 'home') {
        $('html').scrollTo({ top: 0, behavior: 'smooth' });
      } else if (section === 'programs') {
        container.innerHTML = `
          <section class="programs rounded">
            <h2 data-translate="programs-title">${translations[lang]["programs-title"]}</h2>
            <div class="program-item rounded"><h3 data-translate="content-creation">${translations[lang]["content-creation"]}</h3><p data-translate="content-creation-desc">${translations[lang]["content-creation-desc"]}</p></div>
            <div class="program-item rounded"><h3 data-translate="activity">${translations[lang]["activity"]}</h3><p data-translate="activity-desc">${translations[lang]["activity-desc"]}</p></div>
            <div class="program-item rounded"><h3 data-translate="communication-skills">${translations[lang]["communication-skills"]}</h3><p data-translate="communication-skills-desc">${translations[lang]["communication-skills-desc"]}</p></div>
            <div class="program-item rounded"><h3 data-translate="mental-games">${translations[lang]["mental-games"]}</h3><p data-translate="mental-games-desc">${translations[lang]["mental-games-desc"]}</p></div>
          </section>
        `;
        requestAnimationFrame(() => container.querySelector('.programs').classList.add('show'));
        container.scrollIntoView({ behavior: 'smooth' });
      } else if (section === 'about') {
        showModal('about-us-modal');
      } else if (section === 'contact') {
        container.innerHTML = `
          <section class="contact-info container rounded">
            <h2 data-translate="contact-title">${translations[lang]["contact-title"]}</h2>
            <p data-translate="contact-email">${translations[lang]["contact-email"]}</p>
            <p data-translate="contact-phone">${translations[lang]["contact-phone"]}</p>
          </section>
        `;
        container.scrollIntoView({ behavior: 'smooth' });
      }
    }

    document.addEventListener('DOMContentLoaded', () => {
      setTimeout(() => $('#preloader').classList.add('hidden'), 500);
      translatePage('en');

      $$('.lang-btn').forEach(btn => {
        btn.addEventListener('click', () => {
          const lang = btn.dataset.lang;
          translatePage(lang);
          loadSection(document.querySelector('footer a:focus')?.dataset.section || 'home');
        });
      });

      $$('.floating-bar .icon').forEach(icon => {
        icon.addEventListener('click', () => showModal(icon.dataset.modal));
        icon.addEventListener('keydown', (e) => {
          if (e.key === 'Enter' || e.key === ' ') showModal(icon.dataset.modal);
        });
      });

      $$('footer a').forEach(link => {
        link.addEventListener('click', (e) => {
          e.preventDefault();
          loadSection(link.dataset.section);
        });
      });

      $('#join-us-btn').addEventListener('click', () => showModal('join-modal'));
      $('#sign-in-btn').addEventListener('click', () => showModal('signin-modal'));
      $('#join-submit').addEventListener('click', () => handleAuthSubmit('join'));
      $('#signin-submit').addEventListener('click', () => handleAuthSubmit('signin'));
      $('#overlay').addEventListener('click', () => {
        closeModal('join-modal');
        closeModal('signin-modal');
        $$('.about-us-modal').forEach(modal => modal.style.display = 'none');
      });

      $$('.dot[data-close]').forEach(dot => {
        dot.addEventListener('click', (e) => {
          e.target.closest('.about-us-modal').style.display = 'none';
          $('#overlay').style.display = 'none';
        });
      });

      $$('.about-us-modal').forEach(modal => {
        modal.addEventListener('click', (e) => {
          if (e.target === modal) {
            modal.style.display = 'none';
            $('#overlay').style.display = 'none';
          }
        });
      });

      $('#get-started').addEventListener('click', () => {
        if (isAuthenticated) {
          $('.hero-section').style.display = 'none';
          $('#content-container').style.display = 'none';
          $('footer').style.display = 'none';
          $('#auth-window').style.display = 'block';
          setTimeout(() => {
            $$('.gallery, .video-section').forEach(el => el.classList.add('show'));
          }, 10);
          $('html').scrollTo({ top: 0, behavior: 'smooth' });
        } else {
          alert(translations[document.documentElement.lang || 'en']['please-auth']);
        }
      });

      $('#back-to-home').addEventListener('click', () => {
        $('#auth-window').style.display = 'none';
        $('.hero-section').style.display = 'block';
        $('#content-container').style.display = 'block';
        $('footer').style.display = 'block';
        $('html').scrollTo({ top: 0, behavior: 'smooth' });
      });

      // Gallery Image Enlargement
      $$('.gallery img').forEach(img => {
        img.addEventListener('click', () => {
          if (!img.classList.contains('enlarged')) {
            img.classList.add('enlarged');
            $('#image-overlay').style.display = 'block';
          }
        });
      });

      $('#image-overlay').addEventListener('click', () => {
        $$('.gallery img').forEach(img => img.classList.remove('enlarged'));
        $('#image-overlay').style.display = 'none';
      });
    });
  </script>
</body>
</html>
