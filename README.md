<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HUGUES IGOR | Professional Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  /* Global Styles */
  body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    background: url('https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=1470&q=80') no-repeat center center fixed;
    background-size: cover;
    color: #333;
    scroll-behavior: smooth;
    position: relative;
  }
  body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.65);
    z-index: -1;
  }

  /* Header/Hero Section */
  header {
    text-align: center;
    padding: 100px 20px 120px;
    color: #fff;
  }
  header img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 2px solid #00aaff;
    transition: transform 0.4s ease;
  }
  header img:hover { transform: scale(1.05); }
  header h1 { font-size: 3em; color: #00aaff; margin: 15px 0 10px; font-weight: 700; }
  header p { font-size: 1.2em; color: #ddd; margin-bottom: 25px; }
  .btn-resume {
    display: inline-block;
    padding: 14px 28px;
    background-color: #00aaff;
    color: #fff;
    border-radius: 6px;
    text-decoration: none;
    font-weight: 600;
    transition: background 0.3s ease, transform 0.3s ease;
  }
  .btn-resume:hover { background-color: #0077cc; transform: translateY(-2px); }

  /* Section Styles */
  section {
    max-width: 950px;
    margin: 60px auto;
    padding: 50px;
    background: rgba(255,255,255,0.95);
    border-radius: 12px;
    box-shadow: 0 12px 25px rgba(0,0,0,0.12);
    opacity: 0;
    transform: translateY(40px);
    transition: opacity 1s ease, transform 1s ease;
  }
  section.visible { opacity: 1; transform: translateY(0); }
  h2 { color: #00aaff; border-bottom: 2px solid #00aaff; padding-bottom: 10px; margin-bottom: 30px; font-size: 2em; }

  /* About Section */
  .about-container { display: flex; align-items: center; gap: 20px; flex-wrap: wrap; }
  .about-container img { width: 220px; border-radius: 12px; }
  .about-container p { flex: 1; line-height: 1.7em; }

  ul { list-style:none; padding:0; }
  li { margin:10px 0; }

  /* Projects Grid */
  .projects-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px,1fr)); gap:20px; }
  .project-card { background:#f8f9fa; border-radius:10px; padding:15px; transition: transform 0.3s ease, box-shadow 0.3s ease; }
  .project-card:hover { transform: translateY(-5px); box-shadow: 0 0 20px #00aaff; }
  .project-card img { width:100%; border-radius:8px; margin-bottom:12px; }

  /* Testimonials */
  .testimonial-card { background:#e6f2ff; padding:20px; border-radius:10px; box-shadow:0 6px 18px rgba(0,0,0,0.08); margin-bottom:15px; }

  /* Contact */
  .contact a { color:#00aaff; text-decoration:none; }
  .contact a:hover { color:#0077cc; }

  /* Footer */
  footer { text-align:center; padding:30px; background: rgba(26,26,26,0.85); color:#ccc; font-size:0.9em; }

  /* Responsive */
  @media(max-width:768px){ .about-container{ flex-direction: column; text-align:center; } .about-container img{ margin-bottom:20px; } section{ margin:40px 20px; padding:35px; } header h1{ font-size:2.4em; } }
</style>
</head>
<body>

<header>
  <img src="https://avatars.githubusercontent.com/u/9919?s=280&v=4" alt="Hugues Igor">
  <h1>HUGUES IGOR</h1>
  <p>Professional Web Designer & Front-End Developer</p>
  <a href="#" class="btn-resume">Download Resume</a>
</header>

<section class="about">
  <h2>About Me</h2>
  <div class="about-container">
    <img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d?auto=format&fit=crop&w=900&q=80" alt="Working on design">
    <p>Hi! I'm <strong>Hugues Igor</strong>, a professional web designer and front-end developer. I create minimal, elegant, and user-friendly websites focused on accessibility, responsiveness, and modern design trends. I help businesses and creatives present themselves professionally online.</p>
  </div>
</section>

<section class="education-experience">
  <h2>Education & Experience</h2>
  <ul>
    <li>B.Sc. Computer Science - Kigali Institute of Technology, 2020</li>
    <li>Front-End Developer Intern - TechNova Solutions, 2021</li>
    <li>Junior Web Designer - Creative Minds Studio, 2022</li>
    <li>Freelance Web Designer - 2023-Present</li>
  </ul>
</section>

<section class="services">
  <h2>Services</h2>
  <ul>
    <li>Web Design - Modern, responsive, minimal</li>
    <li>Front-End Development - HTML, CSS, JavaScript, React</li>
    <li>UI/UX & Branding</li>
    <li>SEO Optimization</li>
  </ul>
</section>

<section class="projects">
  <h2>Projects</h2>
  <div class="projects-grid">
    <div class="project-card">
      <img src="https://images.unsplash.com/photo-1557804506-669a67965ba0?auto=format&fit=crop&w=800&q=80" alt="Portfolio">
      <h3>Portfolio Website</h3>
    </div>
    <div class="project-card">
      <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?auto=format&fit=crop&w=800&q=80" alt="Coffee Shop">
      <h3>Coffee Shop Landing</h3>
    </div>
    <div class="project-card">
      <img src="https://images.unsplash.com/photo-1581090700227-7e3dbd2e0f97?auto=format&fit=crop&w=800&q=80" alt="E-Commerce">
      <h3>Sample E-Commerce</h3>
    </div>
  </div>
</section>

<section class="testimonials">
  <h2>Testimonials</h2>
  <div class="testimonial-card">
    <p>“Hugues created a sleek, professional website for our café. Highly recommended!” - Claire M.</p>
  </div>
  <div class="testimonial-card">
    <p>“Our online portfolio has never looked better. Hugues delivered on time and with incredible attention to detail.” - James K.</p>
  </div>
</section>

<section class="contact">
  <h2>Contact</h2>
  <p>Email: <a href="mailto:huguesigor@gmail.com">huguesigor@gmail.com</a></p>
  <p>GitHub: <a href="https://github.com/huguesigor" target="_blank">github.com/huguesigor</a></p>
  <p>LinkedIn: <a href="https://linkedin.com/in/huguesigor" target="_blank">linkedin.com/in/huguesigor</a></p>
</section>

<footer>
  <p>&copy; 2025 Hugues Igor. All rights reserved.</p>
</footer>

<script>
  const sections = document.querySelectorAll('section');
  const revealOnScroll = () => {
    const triggerBottom = window.innerHeight * 0.85;
    sections.forEach(section => {
      const sectionTop = section.getBoundingClientRect().top;
      if(sectionTop < triggerBottom) { section.classList.add('visible'); }
    });
  };
  window.addEventListener('scroll', revealOnScroll);
  revealOnScroll();
</script>

</body>
</html>
  
