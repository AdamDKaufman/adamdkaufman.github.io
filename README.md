<html>
<head>
  <title>Adam Kaufman's Website</title>
  <style>
    body {
      font-family: sans-serif; /* Use a modern, clean font */
      margin: 0;
      background-color: #fff; /* Set white background */
      color: #333; /* Darker text for contrast */
    }

    .header {
      padding: 20px;
      text-align: center;
    }

    .header h1 {
      margin: 0;
      font-weight: bold;
    }

    .nav {
      position: fixed; /* Keep nav at top */
      top: 0;
      left: 0;
      width: 100%;
      background-color: rgba(255, 255, 255, 0.9); /* Semi-transparent */
      transition: background-color 0.3s ease-in-out;
      padding: 10px 20px;
      z-index: 1; /* Ensure nav stays above content */
    }

    .nav a {
      color: #333;
      text-decoration: none;
      font-size: 16px;
      padding: 10px 15px;
    }

    .nav a:hover {
      color: #000;
    }

    .main {
      padding: 40px 20px; /* Increased padding for content */
      margin-top: 80px; /* Account for fixed nav */
    }

    .main > * {
      opacity: 0; /* Hide content initially */
      transition: opacity 0.5s ease-in-out;
    }

    .main > *:first-child {
      opacity: 1; /* Show first content block by default */
    }

    .main a[name]:target ~ * {
      opacity: 0; /* Hide previous content blocks when a new one is targeted */
    }

    .main a[name]:target {
      opacity: 1; /* Show the targeted content block */
    }

    .footer {
      text-align: center;
      padding: 10px;
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
  <a name="about"></a>
  <h2>About Me</h2>
  <p>[...]</p>

  <a name="contact"></a>
  <h2>Contact Information</h2>
  <p>[...]</p>

  <a name="resume"></a>
  <h2>Education, Experiences, and Resume</h2>
  <p>[...]</p>
</div>

<div class="footer">
  <p>Adam Kaufman, MSEd</p>
</div>

</body>
</html>
