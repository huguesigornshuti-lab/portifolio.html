<!doctype html>
<html ⚡ lang="en">
  <head>
    <meta charset="utf-8">
    <title>HUGUES IGOR | Portfolio</title>
    <link rel="canonical" href="index.html" />
    <meta name="viewport" content="width=device-width,minimum-scale=1,initial-scale=1">
    <meta name="description" content="HUGUES IGOR - Personal Portfolio showcasing skills, projects, and creativity.">
    <script async src="https://cdn.ampproject.org/v0.js"></script>
    <style amp-custom>
      * {
        box-sizing: border-box;
        scroll-behavior: smooth;
      }
      body {
        font-family: 'Poppins', sans-serif;
        color: white;
        margin: 0;
        background-image: url('https://images.unsplash.com/photo-1503264116251-35a269479413?auto=format&fit=crop&w=1600&q=80');
        background-size: cover;
        background-position: center;
        background-attachment: fixed;
      }
      header {
        text-align: center;
        padding: 100px 20px;
        background: rgba(0, 0, 0, 0.6);
      }
      header h1 {
        font-size: 3em;
        margin: 0;
      }
      header p {
        font-size: 1.3em;
        margin-top: 10px;
      }
      nav {
        text-align: center;
        background-color: rgba(0, 0, 0, 0.7);
        padding: 10px 0;
      }
      nav a {
        color: #fff;
        margin: 0 15px;
        text-decoration: none;
        font-weight: 600;
      }
      nav a:hover {
        color: #00e6e6;
      }
      section {
        padding: 60px 20px;
        text-align: center;
        background: rgba(0, 0, 0, 0.5);
        margin: 20px;
        border-radius: 15px;
      }
      h2 {
        color: #00e6e6;
        font-size: 2em;
        margin-bottom: 20px;
      }
      .projects {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
      }
      .project {
        background: rgba(255, 255, 255, 0.1);
        border-radius: 10px;
        padding: 20px;
        width: 280px;
        transition: 0.3s;
      }
      .project:hover {
        background: rgba(0, 230, 230, 0.2);
      }
      .skills {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 15px;
      }
      .skill {
        background: rgba(255, 255, 255, 0.15);
        padding: 10px 20px;
        border-radius: 25px;
        font-weight: bold;
      }
      form {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 10px;
        width: 100%;
        max-width: 400px;
        margin: 0 auto;
      }
      input, textarea {
        width: 100%;
        padding: 10px;
        border-radius: 10px;
        border: none;
        outline: none;
      }
      button {
        background-color: #00e6e6;
        color: black;
        font-weight: bold;
        padding: 10px 20px;
        border: none;
        border-radius: 25px;
        cursor: pointer;
        transition: 0.3s;
      }
      button:hover {
        background-color: white;
        color: black;
      }
      footer {
        text-align: center;
        padding: 20px;
        background: rgba(0, 0, 0, 0.8);
      }
    </style>
  </head>

  <body>
    <header id="home">
      <h1>HUGUES IGOR</h1>
      <p>Web Designer | Developer | Creative Innovator</p>
    </header>

    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>

    <section id="about">
      <h2>About Me</h2>
      <p>Hello! I'm <strong>HUGUES IGOR</strong>, a passionate web designer and developer who loves creating beautiful, responsive, and interactive websites. My goal is to make technology more visually engaging and user-friendly for everyone.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="projects">
        <div class="project">
          <h3>School Website</h3>
          <p>Developed a responsive school website with image galleries and contact forms.</p>
        </div>
        <div class="project">
          <h3>Coffee Shop Page</h3>
          <p>Created a modern landing page for a local coffee business using AMP technology.</p>
        </div>
        <div class="project">
          <h3>Portfolio Design</h3>
          <p>Designed personal portfolio templates using HTML, CSS, and Google AMP for performance.</p>
        </div>
      </div>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <div class="skills">
        <div class="skill">HTML5</div>
        <div class="skill">CSS3</div>
        <div class="skill">JavaScript</div>
        <div class="skill">AMP Framework</div>
        <div class="skill">Responsive Design</div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <form method="post" action="https://example.com/contact">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>

    <footer>
      <p>© 2025 HUGUES IGOR. All rights reserved.</p>
    </footer>
  </body>
</html>
   
