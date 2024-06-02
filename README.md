<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Adam Kaufman's Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f0f0;
      color: #333;
    }
    .header {
      background-color: rgba(255, 255, 255, 0.9); /* Translucent white */
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      text-align: center;
      padding: 40px 0;
      margin-bottom: 20px;
    }
    .header h1 {
      margin: 0;
    }
    .nav {
      overflow: hidden;
      background-color: rgba(0, 0, 0, 0.5); /* Translucent black */
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      text-align: center;
      padding: 10px 0;
      margin-bottom: 20px;
    }
    .nav a {
      display: inline-block;
      color: white;
      text-align: center;
      padding: 14px 20px;
      text-decoration: none;
      font-size: 17px;
    }
    .nav a:hover {
      background-color: #ddd;
      color: black;
    }
    .main {
      padding: 40px;
    }
    .section {
      background-color: rgba(255, 255, 255, 0.9); /* Translucent white */
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      padding: 20px;
      margin-bottom: 20px;
    }
    .footer {
      background-color: rgba(0, 0, 0, 0.5); /* Translucent black */
      color: #fff;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>

<div class="header">
  <img src="photo5.jpg" alt="Photo" style="width:100%;max-width:300px;margin-bottom:20px;">
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
    <p>I am a graduate of Hunter College with a master's degree in mental health counseling. My therapeutic work is greatly influenced by psychodynamic theories, with an emphasis on how one's unconscious and their past experiences and relationships might inform their current cognitions, behaviors, and symptomatology.</p>
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
  <p>Preferred Method of Contact: </p>
  <label for="communication_preference">Email or Phone</label>
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

<div class="footer">
  <p>Adam Kaufman, MSEd</p>
</div>
