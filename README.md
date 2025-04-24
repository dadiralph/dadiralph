<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name | Cosmic Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: radial-gradient(ellipse at bottom, #0b0c1d 0%, #000000 100%);
      color: #00ffff;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 4rem 2rem;
    }
    header h1 {
      font-size: 2.5rem;
      text-shadow: 0 0 10px #00ffff;
    }
    .typing {
      font-size: 1.2rem;
      color: #ffffffcc;
      animation: typing 4s steps(30, end) infinite;
      white-space: nowrap;
      overflow: hidden;
      border-right: 3px solid #00ffff;
      width: 0;
    }
    @keyframes typing {
      0% { width: 0; }
      50% { width: 100%; }
      100% { width: 0; }
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      border-bottom: 2px solid #00ffff33;
      padding-bottom: 0.5rem;
    }
    .tech-icons img {
      width: 50px;
      margin: 0.5rem;
      transition: transform 0.3s;
    }
    .tech-icons img:hover {
      transform: scale(1.2);
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .card {
      background: #111;
      border: 1px solid #00ffff33;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 0 10px #00ffff33;
    }
    .card:hover {
      box-shadow: 0 0 20px #00ffff;
    }
    .contact {
      text-align: center;
      margin-top: 3rem;
    }
    .contact a {
      color: #00ffff;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      text-align: center;
      font-size: 0.9rem;
      padding: 2rem;
      color: #555;
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <h1>Hi, I'm Your Name 🚀</h1>
    <div class="typing">Web Developer | Space Enthusiast | Creative Thinker</div>
  </header>

  <section>
    <h2>🧠 About Me</h2>
    <p>Passionate about front-end development and crafting interactive UIs. I love blending design with logic, and when I’m not coding, I’m probably stargazing 🌌 or gaming 🎮.</p>
  </section>

  <section>
    <h2>🚀 Tech Stack</h2>
    <div class="tech-icons">
      <img src="https://skillicons.dev/icons?i=html" alt="HTML">
      <img src="https://skillicons.dev/icons?i=css" alt="CSS">
      <img src="https://skillicons.dev/icons?i=js" alt="JavaScript">
      <img src="https://skillicons.dev/icons?i=php" alt="PHP">
      <img src="https://skillicons.dev/icons?i=react" alt="React">
      <img src="https://skillicons.dev/icons?i=github" alt="GitHub">
    </div>
  </section>

  <section>
    <h2>✨ Featured Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>🎨 Creative Portfolio</h3>
        <p>A cosmic-themed personal portfolio site built with HTML, CSS, JS & PHP.</p>
      </div>
      <div class="card">
        <h3>🛰 StarLink Dashboard</h3>
        <p>Track satellites in real-time using open APIs and a clean UI.</p>
      </div>
      <div class="card">
        <h3>🪄 GlowForm</h3>
        <p>Modern glowing contact form with PHP backend and JavaScript animations.</p>
      </div>
    </div>
  </section>

  <section class="contact">
    <h2>📫 Connect with Me</h2>
    <p>
      <a href="mailto:your.email@example.com">Gmail</a> |
      <a href="https://linkedin.com/in/YOURNAME">LinkedIn</a> |
      <a href="https://github.com/YOURUSERNAME">GitHub</a>
    </p>
  </section>

  <footer>
    🛸 “Code like the stars are watching.”
  </footer>
</body>
</html>
