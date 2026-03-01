<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Ayham Basheer Portfolio</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #202569;
      color: #5f2a2a;
      margin: 0;
      padding: 0;
    }

    /* NAVIGATION BAR */
    .topnav {
      background-color: #1f2933;
      overflow: hidden;
      border-bottom: 2px solid #04aa6d;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .topnav a {
      float: left;
      display: block;
      color: #f9fafb;
      text-align: center;
      padding: 14px 18px;
      text-decoration: none;
      font-size: 16px;
      transition: background-color 0.2s ease, color 0.2s ease;
    }

    .topnav a:hover {
      background-color: #374151;
      color: white;
    }

    .topnav a.active {
      background-color: #04aa6d;
      color: white;
    }

    header {
      background-color: #18521b;
      color: white;
      padding: 30px;
      text-align: center;
    }

    section {
      background-color: white;
      margin: 20px;
      padding: 20px;
      border-radius: 8px;
    }

    h2 {
      color: #2e7d32;
    }

    ul {
      padding-left: 20px;
    }

    footer {
      text-align: center;
      padding: 15px;
      font-size: 14px;
      color: #0a0505;
    }
  </style>
</head>
<body>

  <!-- NAVIGATION BAR -->
  <nav class="topnav">
    <a href="#projects" class="active">Projects</a>
    <a href="#about">About</a>
    <a href="#family">Family</a>
    <a href="#hobbies">Hobbies</a>
    <a href="#goals">Goals</a>
  </nav>

  <!-- HEADER -->
  <header id="home">
    <h1>Ayham Basheer</h1>
    <p>Year 11 Student | Western Springs College</p>
    <p>Auckland, New Zealand</p>
  </header>

  <!-- PROJECTS SECTION -->
  <section id="projects">
    <h2>Projects</h2>
    <p>Here are some of the projects I have worked on:</p>
  <ul>
  <li>
    <a href="http://127.0.0.1:3000/kea1.html?serverWindowId=e9ca93f5-d5d1-4584-a802-d6b49130f485" target="_blank">
      My project
    </a>
  </li>
</ul>
  </section>

  <!-- ABOUT SECTION -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      My name is Ayham Basheer. I am 16 years old and currently in Year 11 at
      Western Springs College. I live in Auckland CBD with my family.
    </p>
    <p>
      I was born in Syria, then moved to Malaysia when I was four years old.
      After spending ten years there, my family moved to New Zealand.
      Living in different countries has helped me become more adaptable
      and open-minded.
    </p>
  </section>

  <!-- FAMILY SECTION -->
  <section id="family">
    <h2>Family</h2>
    <p>
      I live with my parents and two brothers. My dad is an IT engineer and
      my mum is a maths teacher. They both inspire me to work hard and
      improve my skills.
    </p>
  </section>

  <!-- HOBBIES SECTION -->
  <section id="hobbies">
    <h2>Hobbies & Interests</h2>
    <ul>
      <li>Gardening – I enjoy taking care of plants and watching them grow.</li>
      <li>Art – I like drawing and creating visual ideas.</li>
      <li>Learning about different cultures.</li>
    </ul>
  </section>

  <!-- GOALS SECTION -->
  <section id="goals">
    <h2>Future Goals</h2>
    <p>
      In the future, I want to build skills in both creativity and technology.
      I am still exploring different career options and interests.
    </p>
  </section>

  <!-- FOOTER -->
  <footer>
    Made on 2/3/2026
  </footer>

</body>
</html>