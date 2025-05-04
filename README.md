<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Chethan Thubharahalli Ramesh - Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      background: #121212;
      color: #e0e0e0;
      overflow-x: hidden;
    }

    #particleCanvas {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      z-index: -1;
      pointer-events: none;
    }

    header, nav, section, footer {
      position: relative;
      z-index: 1;
    }

    header {
      text-align: center;
      padding: 3rem 0;
    }

    header h1 {
      font-size: 3.5rem;
      margin-bottom: 0.5rem;
      color: #00bcd4;
    }

    header p {
      font-size: 1.4rem;
      font-weight: 600;
      color: #b0b0b0;
    }

    .social-icons {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      margin-top: 1rem;
    }

    .social-icons a {
      color: #b0b0b0;
      font-size: 1.5rem;
      transition: color 0.3s ease;
    }

    .social-icons a:hover {
      color: #00bcd4;
    }

    nav {
      display: flex;
      justify-content: center;
      padding: 1rem 0;
      background: rgba(0, 0, 0, 0.8);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 2rem;
    }

    nav ul li a {
      text-decoration: none;
      color: #b0b0b0;
      font-weight: 600;
      text-transform: uppercase;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: #00bcd4;
    }

    section {
      padding: 4rem 5%;
      text-align: center;
    }

    h2 {
      font-size: 2.5rem;
      margin-bottom: 2rem;
      color: #00bcd4;
    }

    p {
      font-size: 1.1rem;
      color: #b0b0b0;
      margin-bottom: 1.5rem;
    }

    footer {
      text-align: center;
      padding: 2rem 0;
      background: #1e1e1e;
      color: #e0e0e0;
    }

    footer .social-icons {
      margin-top: 1rem;
    }

    footer .social-icons a {
      color: #e0e0e0;
      transition: color 0.3s ease;
    }

    footer .social-icons a:hover {
      color: #00bcd4;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      justify-items: center;
    }

    .card {
      background: #2a2a2a;
      padding: 2rem;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      text-align: center;
      color: #e0e0e0;
      border: 1px solid #333;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
    }

    .card i {
      font-size: 2.5rem;
      color: #00bcd4;
      margin-bottom: 1rem;
      transition: color 0.3s ease;
    }

    .card:hover i {
      color: #03dac5;
    }

    .card h3 {
      font-size: 1.8rem;
      margin-bottom: 1rem;
      color: #00bcd4;
    }

    .card p {
      font-size: 1rem;
      color: #b0b0b0;
      line-height: 1.6;
    }
  </style>
</head>
<body>
<canvas id="particleCanvas"></canvas>

<header>
  <h1>Chethan Thubharahalli Ramesh</h1>
  <p>AEM and JAVA Developer </p>
  <div class="social-icons">
    <a href="https://linkedin.com/in/chethan-t-r-935403170" target="_blank"><i class="fab fa-linkedin"></i></a>
    <a href="https://github.com/chethan747" target="_blank"><i class="fab fa-github"></i></a>
    <a href="https://www.hackerrank.com/trchethan555" target="_blank"><i class="fab fa-hackerrank"></i></a>
  </div>
</header>

<nav>
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#achievements">Achievements</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<section id="about">
  <h2>About Me</h2>
  <p>I am Java and AEM Developer with 2.6 years of experience in building and maintaining web applications. Skilled in Adobe
    Experience Manager (AEM 6.4+), including creating components, templates, workflows, and integrating with other
    systems. Strong knowledge of Core Java, JSP, and web technologies like HTML, CSS, and JavaScript. Comfortable
    working in Agile teams and focused on delivering user-friendly and efficient solutions.</p>
</section>

<section id="experience">
  <h2>Experience</h2>
  <div class="grid">
    <div class="card">
      <h3>Java/AEM Developer</h3>
      <p><strong>Faser Engineering, Bangalore, India</strong></p>
      <p><em>01/2022 – 08/2023</em></p>
      <ul style="text-align: left; margin-top: 1rem; color: #b0b0b0;">
        <li>Developed and maintained AEM components, templates, custom workflows, and services using AEM 6.3–6.5; converted Classic UI to Touch UI and integrated with other systems.</li>
        <li>Provided technical support for AEM Sites and Assets, handled user/group administration, and ensured smooth deployment using tools like CRXDE, Eclipse, and IntelliJ.</li>
        <li>Worked across full AEM implementation lifecycle, including asset workflow development, metadata tagging, and reusable component creation, in Agile environments using Java 8, Maven, HTL, and JIRA.</li>
      </ul>
    </div>
    <div class="card">
      <h3>Junior Java/AEM Developer - Intern</h3>
      <p><strong>Faser Engineering, Bangalore, India</strong></p>
      <p><em>03/2021 – 12/2021</em></p>
      <ul style="text-align: left; margin-top: 1rem; color: #b0b0b0;">
        <li>Assisted in building and deploying AEM components and templates, gaining hands-on experience with Sling, JCR, and OSGi.</li>
        <li>Participated in AEM maintenance tasks, including user/group management and content updates in DAM.</li>
        <li>Supported Agile team activities such as daily stand-ups, sprint planning, and collaborated using JIRA and Confluence.</li>
      </ul>
    </div>
  </div>
</section>

<section id="skills">
  <h2>My Skills</h2>
  <div class="grid">
    <div class="card">
      <i class="fas fa-cogs"></i>
      <h3>AEM</h3>
      <p>AEM 6.3, 6.4, 6.5, Sites, Assets, Workflows, DAM, OSGi, CRXDE, Sling, JCR</p>
    </div>
    <div class="card">
      <i class="fab fa-java"></i>
      <h3>Java</h3>
      <p>Core Java, JSP, Servlets, J2EE, Apache Maven, Java API</p>
    </div>
    <div class="card">
      <i class="fas fa-code"></i>
      <h3>Frontend</h3>
      <p>HTML5, CSS3, JavaScript, jQuery, HTL (Sightly)</p>
    </div>
    <div class="card">
      <i class="fas fa-tools"></i>
      <h3>Tools</h3>
      <p>Eclipse, IntelliJ IDEA, JIRA, Git, GitHub, Confluence, VS Code</p>
    </div>
    <div class="card">
      <i class="fas fa-brain"></i>
      <h3>AI / ML</h3>
      <p>SQL Server, Python, Machine Learning, API key integration, AI, Generative AI, React</p>
    </div>
  </div>
</section>

<section id="projects">
  <h2>Explore My Projects</h2>
  <div class="grid">
    <div class="card">
      <i class="fas fa-robot"></i>
      <h3>Automation Framework</h3>
      <p>A robust framework for automating workflows and processes.</p>
    </div>
    <div class="card">
      <i class="fas fa-folder-open"></i>
      <h3>Asset Library</h3>
      <p>A centralized library for managing digital assets efficiently.</p>
    </div>
    <div class="card">
      <i class="fas fa-globe"></i>
      <h3>Portfolio Website</h3>
      <p>A personal portfolio showcasing my skills and projects.</p>
    </div>
  </div>
</section>

<section id="achievements">
  <h2>Achievements</h2>
  <div class="grid">
    <div class="card">
      <i class="fas fa-award"></i>
      <h3>Published Paper</h3>
      <p>Published a research paper on IEEE titled <strong>"Attendance Maintenance System with Intelligent Security"</strong>.</p>
      <a href="https://ieeexplore.ieee.org/document/10592721" target="_blank" style="display: inline-block; margin-top: 1rem; padding: 0.8rem 1.5rem; background: #00bcd4; color: #fff; text-decoration: none; border-radius: 8px; font-weight: 600; transition: background 0.3s ease;">View Paper</a>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: <a href="mailto:trchethan555@gmail.com">trchethan555@gmail.com</a></p>
  <form action="https://formspree.io/f/your-form-id" method="POST" style="max-width: 600px; margin: 0 auto; text-align: left;">
    <div class="form-group">
      <label for="name" style="display: block; margin-bottom: 0.5rem; font-weight: 600;">Name</label>
      <input type="text" id="name" name="name" placeholder="Your Name" required style="width: 100%; padding: 0.8rem; border: 1px solid #333; border-radius: 8px; background: #2a2a2a; color: #e0e0e0; font-size: 1rem;">
    </div>
    <div class="form-group">
      <label for="email" style="display: block; margin-bottom: 0.5rem; font-weight: 600;">Email</label>
      <input type="email" id="email" name="_replyto" placeholder="Your Email" required style="width: 100%; padding: 0.8rem; border: 1px solid #333; border-radius: 8px; background: #2a2a2a; color: #e0e0e0; font-size: 1rem;">
    </div>
    <div class="form-group">
      <label for="message" style="display: block; margin-bottom: 0.5rem; font-weight: 600;">Message</label>
      <textarea id="message" name="message" rows="5" placeholder="Your Message" required style="width: 100%; padding: 0.8rem; border: 1px solid #333; border-radius: 8px; background: #2a2a2a; color: #e0e0e0; font-size: 1rem;"></textarea>
    </div>
    <div class="form-group">
      <button type="submit" style="padding: 0.8rem 2rem; background: #00bcd4; color: #fff; border: none; border-radius: 8px; font-size: 1rem; cursor: pointer; transition: background 0.3s ease;">Send Message</button>
    </div>
  </form>
</section>

<footer>
  <p>&copy; 2025 Chethan Thubharahalli Ramesh. All Rights Reserved.</p>
  <div class="social-icons">
    <a href="https://linkedin.com/in/chethan-t-r-935403170"><i class="fab fa-linkedin"></i></a>
    <a href="https://github.com/chethan747"><i class="fab fa-github"></i></a>
    <a href="https://www.hackerrank.com/trchethan555"><i class="fab fa-hackerrank"></i></a>
  </div>
</footer>

<script>
  const canvas = document.getElementById("particleCanvas");
  const ctx = canvas.getContext("2d");
  let particlesArray;

  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;

  window.addEventListener('resize', () => {
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
    initParticles();
  });

  function Particle(x, y, dx, dy, size, color) {
    this.x = x;
    this.y = y;
    this.dx = dx;
    this.dy = dy;
    this.size = size;
    this.color = color;

    this.draw = () => {
      ctx.beginPath();
      ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
      ctx.fillStyle = this.color;
      ctx.fill();
    };

    this.update = () => {
      if (this.x + this.size > canvas.width || this.x - this.size < 0) this.dx *= -1;
      if (this.y + this.size > canvas.height || this.y - this.size < 0) this.dy *= -1;
      this.x += this.dx;
      this.y += this.dy;
      this.draw();
    };
  }

  function initParticles() {
    particlesArray = [];
    const numberOfParticles = (canvas.width * canvas.height) / 8000;
    for (let i = 0; i < numberOfParticles; i++) {
      const size = Math.random() * 2 + 1;
      const x = Math.random() * canvas.width;
      const y = Math.random() * canvas.height;
      const dx = (Math.random() - 0.5) * 1;
      const dy = (Math.random() - 0.5) * 1;
      const color = 'rgba(255,255,255,0.7)';
      particlesArray.push(new Particle(x, y, dx, dy, size, color));
    }
  }

  function animateParticles() {
    requestAnimationFrame(animateParticles);
    ctx.clearRect(0, 0, canvas.width, canvas.height);
    particlesArray.forEach(p => p.update());
  }
  initParticles();
  animateParticles();
</script>
</body>
</html>
