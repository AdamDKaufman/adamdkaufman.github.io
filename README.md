<html>
<head>
  <title>Adam Kaufman's Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: white;
      color: #333; /* Ensure text is readable on white background */
      overflow-x: hidden; /* Prevent horizontal scroll on small screens */
    }

    .header {
      padding: 20px;
      text-align: center;
    }

    .header img {
      width: 100%;
      max-width: 300px;
      border-radius: 50%; /* Add a rounded border to the image */
    }

    .nav {
      position: fixed; /* Keep navigation bar at the top */
      top: 0;
      width: 100%;
      background-color: white;
      padding: 10px 20px;
      z-index: 100; /* Keep nav above other content */
      box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1); /* Add a subtle shadow */
    }

    .nav a {
      color: #333;
      text-decoration: none;
      font-size: 16px;
      padding: 10px 15px;
      transition: background-color 0.2s ease-in-out;
    }

    .nav a:hover {
      background-color: #f1f1f1;
    }

    .main {
      padding: 30px 20px;
    }

    .section {
      opacity: 0; /* Initially hide sections */
      transform: translateY(50px); /* Slightly offset sections */
      transition: opacity 0.5s ease-in-out, transform 0.5s ease-in-out;
    }

    .section.active {
      opacity: 1;
      transform: translateY(0);
    }

    .section h2 {
      margin-top: 0;
      font-weight: 300; /* Use a lighter font weight for headers */
    }

    .footer {
      padding: 10px 20px;
      text-align: center;
    }
  </style>
</head>
<body>

<div class="header">
  <img src="Professional Photo.jpeg" alt="Professional Photo">
  <h1>Adam Kaufman, MSEd</h1>
</div>

<div class="nav">
  <a href="#about">About Me</a>
  <a href="#contact">Contact Information</a>
  <a href="#resume">Education, Experiences, and Resume</a>
</div>

<div class="main">
  <section id="about" class="section active">
    <h2>About Me</h2>
    </section>

  <section id="contact" class="section">
    <h2>Contact Information</h2>
    </section>

  <section id="resume" class="section">
    <h2>Education, Experiences, and Resume</h2>
    </section>
</div>

<div class="footer">
  <p>Adam Kaufman, MSEd</p>
</div>

<script>
  // JavaScript for scrolling animation
  const sections = document.querySelectorAll('.section');
  const navLinks = document.querySelectorAll('.nav a');

  navLinks.forEach(link => {
    link.addEventListener('click', () => {
      const targetId = link.getAttribute('href');
      const targetSection = document.querySelector(targetId);

      sections.forEach(section => {
        section.classList.remove('active');
      })

      targetSection.classList.add('active');

      window.scrollTo({
        top: targetSection.offsetTop,
        behavior: 'smooth'
      });
    
