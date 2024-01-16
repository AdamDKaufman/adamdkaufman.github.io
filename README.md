<html>
<head>
  <title>Adam Kaufman's Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: white;
      color: #333;
      overflow-x: hidden;
    }

    .header {
      padding: 20px;
      text-align: center;
    }

    .header img {
      width: 100%;
      max-width: 300px;
      border-radius: 50%;
    }

    .nav {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: white;
      padding: 10px 20px;
      z-index: 100;
      box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
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
      opacity: 0;
      transform: translateY(50px);
      transition: opacity 0.5s ease-in-out, transform 0.5s ease-in-out;
    }

    .section.active {
      opacity: 1;
      transform: translateY(0);
    }

    .section h2 {
      margin-top: 0;
      font-weight: 300;
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
    <p>I am a mental health counseling student at CUNY Hunter College with an interest in psychodynamic psychotherapy. Throughout graduate school, my counseling skills have developed through my eclectic experiences at both my practicum and internship sites. For my practicum, I was employed at the Renaissance Charter School in Jackson Heights, Queens, where I provided mental health counseling services to students from K-12th grade. Here, I conducted a dialectical behavioral therapy (DBT) group guided by the Child Mind Institute and provided individual 1:1 mental health counseling services. After my practicum ended, I began my internship at the Training Institute for Mental Health, a site where I currently attend weekly didactic and group clinical case seminars while providing mental health counseling services guided by psychoanalytic thought.</p>
  </section>

  <section id="contact" class="section">
    <h2>Contact Information</h2>
    <p>Email: <a href="mailto:AdamDKaufmanTherapy@Gmail.com">AdamDKaufmanTherapy@Gmail.com</a></p>
    <p>Phone Number: 360-296-0308</p>
  </section>

  <section id="resume" class="section">
    <h2>Education, Experiences, and Resume</h2>
    <p><a href="Adam Kaufman Professional Resume July_10_2023.pdf">See Resume</a></p>
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
      const targetId
