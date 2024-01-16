<html>
<head>
  <title>Adam Kaufman's Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #fff; /* Set a white background */
      color: #333; /* Set text color to dark gray */
    }

    .header {
      padding: 20px;
      text-align: center;
    }

    .header h1 {
      margin: 0;
    }

    .nav {
      background-color: transparent; /* Remove background color */
      position: fixed; /* Fix navigation at the top */
      width: 100%;
      top: 0;
      padding: 10px 20px;
    }

    .nav a {
      color: #333; /* Set link color to dark gray */
      text-decoration: none;
      font-size: 16px;
      padding: 10px;
    }

    .nav a:hover {
      color: #000; /* Set hover color to black */
    }

    .main {
      padding: 20px;
    }

    .section {
      opacity: 0; /* Initially hide sections */
      transform: translateY(40px); /* Move sections up */
      transition: all 0.4s ease-in-out; /* Add transition for smooth reveal */
    }

    .section.active {
      opacity: 1; /* Show active section */
      transform: translateY(0); /* Bring active section into view */
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
      <p>Your content here...</p>
    </div>

    <div class="section" id="contact">
      <h2>Contact Information</h2>
      <p>Your content here...</p>
    </div>

    <div class="section" id="resume">
      <h2>Education, Experiences, and Resume</h2>
      <p>Your content here...</p>
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
    });
  </script>
</body>
</html>
