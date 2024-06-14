<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Adam Kaufman's Website</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
  <style>
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      color: #333;
      background: url('Manhattan.jpg') no-repeat center center fixed;
      background-size: cover;
      scroll-behavior: smooth;
    }
    .nav {
      display: flex;
      justify-content: center;
      background-color: rgba(255, 255, 255, 0.99);
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      padding: 10px 20px;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
    }
    .nav a {
      color: black;
      font-weight: bold;
      padding: 14px 20px;
      text-decoration: none;
      font-size: 17px;
      transition: background-color 0.3s ease;
    }
    .nav a:hover {
      background-color: #ddd;
    }
    .header {
      background-color: rgba(255, 255, 255, 0.99);
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      text-align: center;
      padding: 60px 20px;
      margin: 80px 40px 40px;
      border-radius: 10px;
    }
    .header h1 {
      margin: 0;
    }
    .main {
      padding: 0 40px;
    }
    .section {
      background-color: rgba(255, 255, 255, 0.99);
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      padding: 20px;
      margin-bottom: 40px;
      opacity: 0.5;
      transform: translateY(20px);
      transition: opacity 0.6s ease-out, transform 0.6s ease-out;
    }
    .section.visible {
      opacity: 1;
      transform: translateY(0);
    }
    .footer {
      background-color: rgba(0, 0, 0, 0.75);
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    @media (max-width: 768px) {
      .nav {
        flex-direction: column;
        padding: 10px;
      }
      .nav a {
        padding: 10px;
        font-size: 15px;
      }
      .header {
        padding: 40px 20px;
        margin: 100px 20px 30px;
      }
      .main {
        padding: 0 20px;
      }
      .section {
        padding: 15px;
        margin-bottom: 30px;
      }
      .header h1 {
        font-size: 24px;
      }
      .header img {
        max-width: 80%;
        margin-bottom: 15px;
      }
      .footer {
        padding: 10px 20px;
      }
    }
  </style>
</head>
<body>
  <nav class="nav">
    <a href="#about">About Me</a>
    <a href="#contact">Contact Information</a>
    <a href="#contactform">Leave a Message</a>
  </nav>

  <header class="header">
    <img src="photo5.jpg" alt="Adam Kaufman" style="width:100%;max-width:300px;margin-bottom:20px;">
    <h1>Adam Kaufman, MSEd</h1>
    <h2>Counselor Under Supervision</h2>
  </header>

  <main class="main">
    <section class="section" id="about">
      <h2>About Me</h2>
      <p>As a passionate mental health counselor with a limited permit to practice psychotherapy in New York, I am committed to supporting your journey toward well-being. My therapeutic approach is deeply rooted in psychodynamic theories, helping you uncover how your past experiences and relationships influence your present thoughts, behaviors, and emotions. With extensive experience in addressing a variety of mental health challenges—such as depression, anxiety, stress, trauma, and relationship issues—I am here to provide a safe and understanding environment for you to explore and overcome your difficulties. Let’s work together to create a path towards a healthier and more fulfilling life. Please leave a message below or contact me via phone or email to book your free 15-minute phone consultation to see if we’re a good fit.</p>
      <p>Certifications: Pursuing a certificate in psychodynamic psychotherapy from the Training Institute for Mental Health (to be completed by 2027).</p>
      <p>Services Offered: Individual therapy (in-person or telehealth) for people of all ages who are experiencing stress and/or symptoms of depression, anxiety disorders, grief, and post-traumatic stress disorder.</p>
    </section>

    <section class="section" id="contact">
      <h2>Contact Information</h2>
      <p>Email: <a href="mailto:AdamDKaufmanTherapy@Gmail.com">AdamDKaufmanTherapy@Gmail.com</a></p>
      <p>Phone: <a href="tel:+13602960308">360-296-0308</a></p>
    </section>

    <section class="section" id="contactform">
      <h2>Leave a Message</h2>
      <form id="contact-form" method="post" action="https://formspree.io/f/mleqyjkz">
        <p>Please fill out the form below to schedule a free 15-minute phone consultation or to book an appointment. I’ll get back to you within one business day.</p>
        <label for="communication_preference">Preferred Method of Contact:</label>
        <select id="communication_preference" name="communication_preference" required>
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
    </section>
  </main>

  <footer class="footer">
    <p>&copy; 2024 Adam Kaufman, MSEd</p>
  </footer>

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
