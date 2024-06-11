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
      line-height: 1.6
      color: #333;
      background: url('Manhattan.jpg') no-repeat center center fixed;
      background-size: cover;
      scroll-behavior: smooth;
    }
    .nav {
      width: calc(100% - 80px); /* 40px margin on each side */
      margin: 0 40px;
      border-radius: 10px;
      overflow: hidden;
      background-color: rgba(255, 255, 255, .99); /* Translucent white */
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      text-align: center;
      padding: 10px 0;
      box-sizing: border-box;
    }
    .nav a {
      display: inline-block;
      color: black;
      font-weight: bold;
      text-align: center;
      padding: 14px 20px;
      text-decoration: none;
      font-size: 17px;
    }
    .nav a:hover {
      background-color: #ddd;
      color: black;
    }
    .header {
      background-color: rgba(255, 255, 255, .99); /* Translucent white */
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      text-align: center;
      padding: 40px 0;
      margin: 20px 40px 40px 40px; /* Margin: 20px from the nav, 40px from sections */
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
    }
    .footer {
      background-color: rgba(0, 0, 0, .75); /* Translucent black */
      color: #fff;
      text-align: center;
      padding: 10px;
    }
    @media (max-width: 768px) {
      .nav {
        width: calc(100% - 40px); /* Reduced margin for smaller screens */
        margin: 0 20px;
      }
      .nav a {
        padding: 10px;
        font-size: 15px;
      }
      .header {
        padding: 20px 0;
        margin: 20px 20px 30px 20px; /* Adjusted margin for smaller screens */
      }
      .main {
        padding: 0 20px 30px 20px;
      }
      .section {
        padding: 15px;
        margin-bottom: 30px; /* Reduced margin for smaller screens */
      }
      .header h1 {
        font-size: 24px; /* Smaller font size for the header */
      }
      .header img {
        max-width: 80%; /* Adjust image size for smaller screens */
        margin-bottom: 15px; /* Reduce bottom margin for smaller screens */
      }
      .footer {
        padding: 10px 20px; /* Adjust footer padding for smaller screens */
      }
    }
  </style>
</head>
<body>

<div class="nav">
  <a href="#about">About Me</a>
  <a href="#contact">Contact Information</a>
  <a href="#contactform">Leave a Message</a>
</div>

<div class="header">
  <img src="photo5.jpg" alt="Photo" style="width:100%;max-width:300px;margin-bottom:20px;">
  <h1>Adam Kaufman, MSEd</h1>
</div>

<div class="main">
  <div class="section" id="about">
    <h2>About Me</h2>
    <p>I am a mental health counselor who holds a limited permit to practice psychotherapy in the state of New York. My therapeutic work is greatly influenced by psychodynamic theories, with an emphasis on how one's unconscious and their past experiences and relationships might inform their current cognitions, behaviors, and symptomatology. I have experience working with individuals struggling with a range of mental health difficulties, including depression, anxiety, stress, trauma, and relationship difficulties. Moreover, I am committed to affordable, exceptional, and multiculturally-competent mental health treatment. Please leave a message below or contact me via phone or email to book your free 15-minute phone consultation to see if we’re a good fit.</p>
    <p>Qualifications/Certifications: MSEd in mental health counseling; Pursuing a certificate in psychodynamic psychotherapy from the Training Institute for Mental Health (to be completed by 2027).</p>
    <p>Services Offered: Individual therapy (in-person or telehealth) for people of all ages who are experiencing stress and/or symptoms of depression, anxiety disorders, grief, and post-traumatic stress disorder.</p>
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
