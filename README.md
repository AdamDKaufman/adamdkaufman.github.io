<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Adam David Kaufman, MSEd - Mental Health Counseling</title>
  <meta name="description" content="Adam David Kaufman is a mental health counselor associate who works with clients of all ages and all walks of life in University Place, Washington." />
  <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
  <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
  <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
  <link rel="manifest" href="/site.webmanifest">
  <link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
  <meta name="msapplication-TileColor" content="#da532c">
  <meta name="theme-color" content="#ffffff">
  <meta property="og:image" content="FinalLogo.png" name="image">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
  <style>
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      color: #333;
      background: url('rainier2.jpg') no-repeat center center fixed;
      background-size: cover;
      scroll-behavior: smooth;
    }
    .nav {
      width: 100%;
      background-color: rgba(0, 0, 0, 0.75); /* Translucent black */
      color: #f0f0f0;
      text-align: center;
      padding: 10px 0;
      box-sizing: border-box;
      position: absolute;
      top: 0;
      left: 0;
      z-index: 1000;
    }
    .nav a {
      display: inline-block;
      color: inherit;
      font-weight: bold;
      text-align: center;
      padding: 14px 20px;
      text-decoration: none;
      font-size: 17px;
      transition: color 0.3s ease;
    }
    .nav a:hover {
      color: rgb(56, 182, 255);
    }
    .header {
      background-color: rgba(255, 255, 255, .99); /* Translucent white */
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      text-align: center;
      padding: 40px 0;
      margin: 80px 40px 40px 40px; /* Margin: 80px from the nav, 40px from sections */
    }
    .header h1 {
      margin: 0;
    }
    .main {
      padding: 0 40px 40px 40px;
    }
    .section {
      background-color: rgba(255, 255, 255, .99); /* Translucent white */
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      padding: 20px;
      margin-bottom: 40px; /* Updated margin to equalize spacing */
      opacity: 0.5; /* Initial opacity to be semi-visible */
      transform: translateY(20px);
      transition: opacity 0.6s ease-out, transform 0.6s ease-out;
      box-sizing: border-box; /* Added box-sizing */
    }
    .section.visible {
      opacity: 1;
      transform: translateY(0);
    }
    .footer {
      background-color: rgba(0, 0, 0, .75); /* Translucent black */
      color: #fff;
      text-align: center;
      padding: 10px;
      margin-top: 40px; /* Ensure space between last section and footer */
    }
    @media (max-width: 768px) {
      html, body {
        background: url('AdobeRainier.png') no-repeat center center fixed;
        background-size: cover;
      }
      .nav {
        width: 100%; 
        margin: 0; 
      }
      .nav a {
        padding: 10px;
        font-size: 15px;
      }
      .header {
        padding: 20px 0;
        margin: 80px 10px 30px 10px; /* Adjusted margin for smaller screens */
      }
      .main {
        padding: 0 10px 30px 10px; /* Adjusted padding for smaller screens */
      }
      .section {
        padding: 15px;
        margin-bottom: 20px; /* Reduced margin for smaller screens */
      }
      .header h1 {
        font-size: 24px; /* Smaller font size for the header */
      }
      .header img {
        max-width: 80%; /* Adjust image size for smaller screens */
        margin-bottom: 15px; /* Reduce bottom margin for smaller screens */
      }
      .footer {
        padding: 10px 10px; /* Adjust footer padding for smaller screens */
      }
    }
  </style>
</head>
<body>

<div class="nav">
  <a href="#services">Services</a>
  <a href="#contact">Contact Information</a>
  <a href="#contactform">Leave a Message</a>
</div>

<div class="header">
  <img src="photo5.jpg" alt="Photo" style="width:100%;max-width:300px;margin-bottom:20px;">
  <h1>Adam Kaufman, MSEd</h1>
  <h1>Mental Health Counselor Associate</h1>
</div>

<div class="main">
  <div class="section" id="services">
    <h2>Services Offered</h2>
    <p>As a passionate mental health counselor with a limited permit to practice psychotherapy in Washington State, I am committed to supporting your journey toward well-being. I provide mental health counseling services to people from all walks of life and all ages. My therapeutic approach is deeply rooted in psychodynamic theories, helping you uncover how your past experiences and relationships influence your present thoughts, behaviors, and emotions. With extensive experience in addressing a variety of mental health challenges—such as depression, anxiety, stress, trauma, and relationship issues—I am here to provide a safe and understanding environment for you to explore and overcome your difficulties. Let’s work together to create a path towards a healthier and more fulfilling life. Please leave a message below or contact me via phone or email to book your free 15-minute phone consultation to see if we’re a good fit.</p>
    <p>Certifications: Pursuing a certificate in psychodynamic psychotherapy from the Training Institute for Mental Health (to be completed by 2027).</p>
  </div>

  <div class="section" id="contact">
    <h2>Contact Information</h2>
    <p>Email: AdamDKaufmanTherapy@Gmail.com</p>
    <p>Phone Number: 360-296-0308</p>
  </div>

  <div class="section" id="contactform">
    <h2>Leave a Message</h2>
    <form id="contact-form" method="post" action="https://formspree.io/f/mleqyjkz">
      <p>Please fill out the form below to schedule a free 15-minute phone consultation or to book an appointment. I’ll get back to you within one business day.</p>
      <label for="communication_preference">Preferred Method of Contact:</label>
      <select id="communication_preference" name="communication_preference">
        <option value="email">Email</option>
        <option value="phone">Phone</option>
      </select><br><br>

      <label for="name">Your Name:</label><br>
      <input type="text" id="name" name="name" required placeholder="Jane Doe"><br><br>
      <label for="email">Your Email:</label><br>
      <input type="email" id="email" name="email" required placeholder="JaneDoe@Gmail.com"><br><br>
      <label for="phone">Your Phone Number:</label><br>
      <input type="tel" id="phone" name="phone" required placeholder="123-456-7890"><br><br>
      <label for="message">Send a Message:</label><br>
      <textarea id="message" name="message" rows="5" required placeholder="Your Message Here"></textarea><br><br>
      <button type="submit">Send Message</button>
    </form>
  </div>

  <div class="footer">
    <p>Adam Kaufman, MSEd</p>
  </div>

  <script>
    document.addEventListener('DOMContentLoaded', function () {
      const sections = document.querySelectorAll('.section');
      const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            entry.target.classList.add('visible');
          }
        });
      }, {
        threshold: 0.1
      });

      sections.forEach(section => {
        observer.observe(section);
      });
    });
  </script>
