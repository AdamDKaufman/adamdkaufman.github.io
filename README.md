<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Adam Kaufman's Website</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }
    .container {
      max-width: 800px;
      margin: auto;
      padding: 0 20px;
    }
    .header {
      text-align: center;
      padding: 40px 0;
      margin-bottom: 40px;
    }
    .header img {
      max-width: 100%;
      height: auto;
      margin-bottom: 20px;
      border-radius: 50%;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    }
    .header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #333;
    }
    .nav {
      text-align: center;
      margin-bottom: 40px;
    }
    .nav a {
      display: inline-block;
      color: #333;
      text-decoration: none;
      padding: 10px 20px;
      margin: 0 10px;
      border-radius: 5px;
      background-color: #f0f0f0;
      transition: background-color 0.3s ease;
    }
    .nav a:hover {
      background-color: #ddd;
    }
    .main {
      padding: 0 20px;
      margin-bottom: 40px;
    }
    .section {
      background-color: #fff;
      padding: 30px;
      margin-bottom: 40px;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    }
    .section h2 {
      margin-top: 0;
      font-size: 2rem;
      color: #333;
    }
    .footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 20px 0;
    }
  </style>
</head>
<body>

<div class="container">
  <div class="header">
    <img src="photo5.jpg" alt="Photo">
    <h1>Adam Kaufman, MSEd</h1>
  </div>

  <div class="nav">
    <a href="#about">About Me</a>
    <a href="#contact">Contact Information</a>
    <a href="#contactform">Leave a Message</a>
  </div>

  <div class="main">
    <div class="section" id="about">
      <h2>About Me</h2>
      <p>I am a graduate of Hunter College with a master's degree in mental health counseling. My therapeutic work is greatly influenced by psychodynamic theories, with an emphasis on how one's unconscious and their past experiences and relationships might inform their current cognitions, behaviors, and symptomatology. Moreover, I believe the therapeutic relationship to be of utmost importance. Please leave a message below or contact me via phone or email to schedule a consultation and to determine if we could work together.</p>
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
        <label for="communication_preference">Preferred Method of Contact:</label><br>
        <select id="communication_preference" name="communication_preference">
          <option value="email">Email</option>
          <option value="phone">Phone</option>
        </select><br><br>

        <label for="name">Your Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Your Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="phone">Your Phone Number:</label><br>
        <input type="tel" id="phone" name="phone" required><br><br>
        <label for="message">Send a Message:</label><br>
        <textarea id="message" name="message" rows="5" required></textarea><br><br>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </div>

  <div class="footer">
    <p>Adam Kaufman, MSEd</p>
  </div>
</div>
