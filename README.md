<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Adam Kaufman's Website</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,600">
  <style>
    body {
      font-family: 'Source Sans Pro', Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #333;
      color: #fff;
    }
    .header {
      background-color: #1a1a1a;
      padding: 80px 0;
      text-align: center;
      margin-bottom: 40px;
    }
    .header img {
      border-radius: 50%;
      margin-bottom: 20px;
    }
    .header h1 {
      margin: 0;
      font-weight: 300;
      font-size: 2.5em;
    }
    .nav {
      background-color: #444;
      text-align: center;
      padding: 20px 0;
      margin-bottom: 40px;
    }
    .nav a {
      color: #fff;
      text-decoration: none;
      padding: 10px 20px;
      font-weight: 600;
      text-transform: uppercase;
    }
    .nav a:hover {
      background-color: #666;
    }
    .main {
      padding: 20px;
      max-width: 1000px;
      margin: 0 auto;
    }
    .section {
      background-color: #1a1a1a;
      padding: 30px;
      border-radius: 10px;
      margin-bottom: 40px;
    }
    .section h2 {
      font-weight: 300;
      font-size: 2em;
      margin-top: 0;
    }
    .footer {
      background-color: #444;
      color: #bbb;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
    form {
      display: grid;
      gap: 10px;
    }
    input, textarea, select {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 5px;
      margin-top: 5px;
    }
    button {
      background-color: #1a1a1a;
      color: #fff;
      border: none;
      padding: 15px;
      cursor: pointer;
      border-radius: 5px;
      font-size: 1em;
      text-transform: uppercase;
    }
    button:hover {
      background-color: #333;
    }
  </style>
</head>
<body>

<div class="header">
  <img src="photo5.jpg" alt="Photo" style="width:150px;">
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
    <p>I am a mental health counselor based in New York, New York. My therapeutic work is greatly influenced by psychodynamic theories, emphasizing how one's unconscious and past experiences might inform their current behaviors and symptoms. The therapeutic relationship is of utmost importance. Contact me to book a free, 15-minute phone consultation.</p>
    <p>Qualifications/Certifications: MSEd in mental health counseling; Pursuing a certificate in psychodynamic psychotherapy from the Training Institute for Mental Health (to be completed by 2027).</p>
    <p>Services Offered: Individual therapy (in-person or telehealth) for people of all ages experiencing stress, depression, anxiety disorders, grief, and PTSD.</p>
  </div>

  <div class="section" id="contact">
    <h2>Contact Information</h2>
    <p>Email: AdamDKaufmanTherapy@Gmail.com</p>
    <p>Phone: 360-296-0308</p>
  </div>

  <div class="section" id="contactform">
    <h2>Leave a Message</h2>
    <form id="contact-form" method="post" action="https://formspree.io/f/mleqyjkz">
      <p>Please fill out the form below to schedule a free, 15-minute phone consultation or to book an appointment. I’ll get back to you within one business day.</p>
      <label for="communication_preference">Preferred Method of Contact:</label>
      <select id="communication_preference" name="communication_preference">
        <option value="email">Email</option>
        <option value="phone">Phone</option>
      </select>
      <label for="name">Your Name:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">Your Email:</label>
      <input type="email" id="email" name="email" required>
      <label for="phone">Your Phone Number:</label>
      <input type="tel" id="phone" name="phone" required>
      <label for="message">Send a Message:</label>
      <textarea id="message" name="message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>
</div>

<div class="footer">
  <p>Adam Kaufman, MSEd</p>
</div>

</body>
</html>
