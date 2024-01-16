<html>
<head>
  <title>Adam Kaufman's Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #fff;
      color: #333;
    }

    .header {
      padding: 20px;
      text-align: center;
    }

    .header h1 {
      margin: 0;
    }

    .nav {
      background-color: transparent;
      position: fixed;
      width: 100%;
      top: 0;
      padding: 10px 20px;
    }

    .nav a {
      color: #333;
      text-decoration: none;
      font-size: 16px;
      padding: 10px;
    }

    .nav a:hover {
      color: #000;
    }

    .main {
      padding: 20px;
    }

    .section {
      opacity: 0;
      transform: translateY(40px);
      transition: all 0.4s ease-in-out;
    }

    .section.active {
      opacity: 1;
      transform: translateY(0);
    }

    .footer {
      padding: 10px;
      text-align: center;
    }
  </style>
</head>
<body>

  <div class="header">
    <img src="Professional Photo.jpeg" alt="Professional Photo" style="width:100%;max-width:300px">
    <h1>Adam Kaufman, MSEd</h1>
  </div>

  <div class="nav">
    <a href="#about">About Me</a>
    <a href="#contact">Contact Information</a>
    <a href="#resume">Education, Experiences, and Resume</a>
  </div>

  <div class="main">
    <div class="section" id="about">
      <h2>About Me</h2>
      <p>I am a mental health counseling student at CUNY Hunter College with an interest in psychodynamic psychotherapy. Throughout graduate school, my counseling skills have developed through my eclectic experiences at both my practicum and my internship sites. For my practicum, I was employed at the Renaissance Charter School in Jackson Heights, Queens, where I provided mental health counseling services to students from K-12th grade. Here, I conducted a dialectical behavioral therapy (DBT) group guided by the Child Mind Institute and provided individual 1:1 mental health counseling services. After my practicum ended, I began my internship at the Training Institute for Mental Health, a site where I currently attend weekly didactic and group clinical case seminars while providing mental health counseling services guided by psychoanalytic thought.</p>
    </div>

    <div class="section" id="contact">
      <h2>Contact Information</h2>
      <p>Email: AdamDKaufmanTherapy@Gmail.com</p>
    </div>

    <div class="section" id="resume">
      <h2>Education, Experiences, and Resume</h2>
      <p>See <a href="Adam Kaufman Professional Resume July_10_2023.pdf">Resume.</a></p>
    </div>
  </div>

  <div class="footer">
    <p>Adam Kaufman, MSEd</p>
  </div>

  <script>
    // JavaScript for smooth scrolling and section reveal
    const sections = document.querySelectorAll('.section');
    const navLinks = document.querySelectorAll('.nav a');

    navLinks.forEach(link => {
      link.addEventListener('click', () => {
        const targetId = link.href.split('#')[1];
        const targetSection = document.querySelector(`#${targetId}`);

        sections.forEach(section => {
          section.classList.remove('active');
        });

        targetSection.classList.add('active');

        window.scrollTo({
          top: targetSection.offsetTop,
          behavior: 'smooth'
        });
      });
