<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio Website</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
      integrity="sha512-Fo3rlrZj/k7ujTnHg4fN5Kw6XDPFVNpKGeF1VZb30+/ca1Y9qgKhkT/Jg00kpFhI7sK2ueA/+ux+HbHmIWfsHw=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <style>
      :root {
        --primary-color: #0089b7;
        --secondary-color: #003d62;
        --accent-color: #fff700;
        --light-color: #f4f4f4;
        --dark-color: #222;
      }
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }
      body {
        font-family: 'Poppins', sans-serif;
        line-height: 1.6;
        color: var(--dark-color);
      }
      header {
        background: var(--primary-color);
        padding: 1rem;
        display: flex;
        justify-content: space-between;
        align-items: center;
        color: white;
      }
      header .logo {
        font-size: 2rem;
        font-weight: bold;
      }
      header nav ul {
        display: flex;
        list-style: none;
        gap: 1.5rem;
      }
      header nav ul li a {
        color: white;
        text-decoration: none;
        font-size: 1.2rem;
        transition: color 0.3s;
      }
      header nav ul li a:hover {
        color: var(--accent-color);
      }
      #hero {
        background: var(--secondary-color);
        color: white;
        text-align: center;
        padding: 5rem 2rem;
      }
      #hero h1 {
        font-size: 3.5rem;
        margin-bottom: 1rem;
      }
      #hero p {
        font-size: 1.5rem;
      }
      #about {
        padding: 4rem 2rem;
        background: var(--light-color);
        text-align: center;
      }
      #about h2 {
        font-size: 2.5rem;
        margin-bottom: 1rem;
        color: var(--primary-color);
      }
      #about p {
        max-width: 800px;
        margin: 0 auto;
        font-size: 1.2rem;
      }
      #projects {
        padding: 4rem 2rem;
        text-align: center;
      }
      #projects h2 {
        font-size: 2.5rem;
        margin-bottom: 2rem;
        color: var(--primary-color);
      }
      .project-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 2rem;
      }
      .project {
        background: white;
        padding: 1.5rem;
        border-radius: 10px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      }
      .project img {
        height: 70%;
        width: 100%;
        border-radius: 10px;
        margin-bottom: 1rem;
      }
      .project h3 {
        margin-bottom: 0.5rem;
        color: var(--secondary-color);
      }
      .project p {
        font-size: 1rem;
      }
      #skills {
        background: var(--light-color);
        padding: 4rem 2rem;
        text-align: center;
      }
      #skills h2 {
        font-size: 2.5rem;
        margin-bottom: 1.5rem;
        color: var(--primary-color);
      }
      .skills-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
        gap: 2rem;
      }
      .skill {
        background: white;
        padding: 1rem;
        border-radius: 10px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        text-align: center;
      }
      .skill i {
        font-size: 2.5rem;
        color: var(--secondary-color);
        margin-bottom: 0.5rem;
      }
      .skill h3 {
        font-size: 1.2rem;
      }
      #contact {
        padding: 4rem 2rem;
        text-align: center;
      }
      #contact h2 {
        font-size: 2.5rem;
        margin-bottom: 1rem;
        color: var(--primary-color);
      }
      footer {
        background: var(--secondary-color);
        color: white;
        text-align: center;
        padding: 1rem;
        font-size: 1rem;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">My Portfolio</div>
      <nav>
        <ul>
          <li><a href="#hero">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>

    <section id="hero">
      <h1>Welcome to My Portfolio</h1>
      <p>I am a Frontend Developer passionate about building beautiful and functional websites.</p>
    </section>

    <section id="about">
      <h2>About Me</h2>
      <p>
        Hello! I'm Divya dhare, a dedicated frontend developer with a love for creating interactive and user-friendly web applications. With experience in HTML, CSS, and JavaScript, I aim to deliver top-notch solutions to every project I undertake.
      </p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="project-grid">
        <div class="project">
          <img src="project 2.png" alt="Project 1" />
          <h3>Job application website</h3>
          <p>A responsive Job application website built using HTML, CSS, and JavaScript.</p>
        </div>
        <div class="project">
          <img src="project 3.png" alt="Project 2" />
          <h3>Parallax website</h3>
          <p>A parallex website is typically created using a combination of HTML,CSS, JavaScript  </p>
        </div>
        <div class="project">
          <img src="project1.png" alt="Project 3" />
          <h3>Tribute application</h3>
          <p>A responsive tribute application to A.P.J. abdul kalam built using HTML, CSS, and JavaScript.</p>
        </div>
        <div class="project">
          <img src="project4.png" alt="Project 4" />
          <h3>portfolio website</h3>
          <p>A responsive personal portfolio built using HTML, CSS, and JavaScript.</p>
        </div>
      </div>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <div class="skills-grid">
        <div class="skill">
          <i class="fab fa-html5"></i>
          <h3>HTML</h3>
        </div><div class="skill">
          <i class="fab fa-html5"></i>
          <h3>CSS</h3>
        </div>
        <div class="skill">
          <i class="fab fa-css3-alt"></i>
          <h3>Java script</h3>
          
        </div><div class="skill">
          <i class="fab fa-html5"></i>
          <h3>Python</h3>
        </div>
        <div class="skill">
          <i class="fab fa-js"></i>
          <h3>SQL</h3>
        </div><div class="skill">
          <i class="fab fa-js"></i>
          <h3>DBMS</h3>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <H4>dharedivya4922@gmail.com</H4>
      <p>Feel free to reach out to discuss projects or opportunities!</p>
       
    </section>

    <footer>
      <p>&copy; 2024 Divya dhare. All Rights Reserved.</p>
    </footer>
  </body>
</html>
# Portfolio-
