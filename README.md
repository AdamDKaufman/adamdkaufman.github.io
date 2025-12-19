<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Adam Kaufman, MSEd, LMHCA - Professional Mental Health Counseling</title>
  <meta name="description" content="Licensed mental health counselor in University Place, WA. Expert in depression, anxiety, trauma & relationship issues. Book your free consultation today." />
  <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
  <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
  <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
  <link rel="manifest" href="/site.webmanifest">
  <link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
  <meta name="msapplication-TileColor" content="#da532c">
  <meta name="theme-color" content="#ffffff">
  <meta property="og:image" content="FinalLogo.png" name="image">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html, body {
      width: 100%;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      line-height: 1.6;
      color: #1a1a1a;
      background: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)), url('rainier2.jpg') no-repeat center center fixed;
      background-size: cover;
      scroll-behavior: smooth;
    }

    .nav {
      width: 100%;
      background-color: rgba(255, 255, 255, 0.98);
      backdrop-filter: blur(10px);
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      text-align: center;
      padding: 16px 0;
      position: fixed;
      top: 0;
      left: 0;
      z-index: 1000;
    }

    .nav a {
      display: inline-block;
      color: #2c5282;
      font-weight: 600;
      text-align: center;
      padding: 12px 24px;
      text-decoration: none;
      font-size: 15px;
      transition: all 0.3s ease;
      border-radius: 6px;
    }

    .nav a:hover {
      background-color: #2c5282;
      color: white;
    }

    .nav a.cta {
      background-color: #2c5282;
      color: white;
    }

    .nav a.cta:hover {
      background-color: #1a365d;
      transform: translateY(-2px);
      box-shadow: 0 4px 12px rgba(44, 82, 130, 0.3);
    }

    .header {
      background-color: rgba(255, 255, 255, 0.98);
      border-radius: 16px;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.12);
      text-align: center;
      padding: 60px 40px;
      margin: 100px auto 50px auto;
      max-width: 900px;
    }

    .header img {
      width: 100%;
      max-width: 220px;
      border-radius: 50%;
      margin-bottom: 30px;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.15);
    }

    .header h1 {
      font-size: 36px;
      font-weight: 700;
      color: #1a365d;
      margin-bottom: 10px;
      letter-spacing: -0.5px;
    }

    .header h2 {
      font-size: 20px;
      font-weight: 500;
      color: #4a5568;
      margin-bottom: 20px;
    }

    .credentials {
      display: inline-block;
      background-color: #ebf4ff;
      color: #2c5282;
      padding: 8px 20px;
      border-radius: 20px;
      font-size: 14px;
      font-weight: 600;
      margin: 10px 5px;
    }

    .tagline {
      font-size: 18px;
      color: #2d3748;
      margin: 25px 0;
      font-weight: 400;
      line-height: 1.7;
    }

    .cta-button {
      display: inline-block;
      background-color: #2c5282;
      color: white;
      padding: 16px 40px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
      font-size: 16px;
      margin-top: 20px;
      transition: all 0.3s ease;
      box-shadow: 0 4px 12px rgba(44, 82, 130, 0.3);
    }

    .cta-button:hover {
      background-color: #1a365d;
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(44, 82, 130, 0.4);
    }

    .main {
      padding: 0 20px 60px 20px;
      max-width: 900px;
      margin: 0 auto;
    }

    .section {
      background-color: rgba(255, 255, 255, 0.98);
      border-radius: 16px;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.12);
      padding: 50px 60px;
      margin-bottom: 40px;
      opacity: 0.5;
      transform: translateY(20px);
      transition: opacity 0.6s ease-out, transform 0.6s ease-out;
    }

    .section.visible {
      opacity: 1;
      transform: translateY(0);
    }

    .section h2 {
      font-size: 32px;
      font-weight: 700;
      color: #1a365d;
      margin-bottom: 30px;
      text-align: center;
    }

    .section h3 {
      font-size: 20px;
      font-weight: 600;
      color: #2c5282;
      margin: 30px 0 15px 0;
    }

    .section p {
      font-size: 16px;
      line-height: 1.8;
      color: #2d3748;
      margin-bottom: 20px;
    }

    .section ul {
      margin: 20px 0 20px 20px;
    }

    .section li {
      font-size: 16px;
      line-height: 2;
      color: #2d3748;
      margin-bottom: 12px;
      list-style-type: none;
      position: relative;
      padding-left: 30px;
    }

    .section li:before {
      content: "✓";
      position: absolute;
      left: 0;
      color: #2c5282;
      font-weight: bold;
      font-size: 18px;
    }

    .highlight-box {
      background-color: #f7fafc;
      border-left: 4px solid #2c5282;
      padding: 25px 30px;
      margin: 30px 0;
      border-radius: 8px;
    }

    .contact-info {
      text-align: center;
      font-size: 18px;
      margin: 20px 0;
    }

    .contact-info a {
      color: #2c5282;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }

    .contact-info a:hover {
      color: #1a365d;
      text-decoration: underline;
    }

    #contactform {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
    }

    #contactform h2 {
      color: white;
      font-size: 36px;
      margin-bottom: 15px;
    }

    #contactform .form-intro {
      text-align: center;
      font-size: 18px;
      margin-bottom: 40px;
      color: #f7fafc;
    }

    form {
      max-width: 600px;
      margin: 0 auto;
    }

    label {
      display: block;
      font-weight: 600;
      margin-bottom: 8px;
      font-size: 15px;
    }

    input, select, textarea {
      width: 100%;
      padding: 14px 16px;
      margin-bottom: 24px;
      border: 2px solid rgba(255, 255, 255, 0.3);
      border-radius: 8px;
      font-size: 16px;
      font-family: 'Inter', sans-serif;
      background-color: rgba(255, 255, 255, 0.95);
      transition: all 0.3s ease;
    }

    input:focus, select:focus, textarea:focus {
      outline: none;
      border-color: #2c5282;
      background-color: white;
      box-shadow: 0 0 0 3px rgba(44, 82, 130, 0.1);
    }

    button[type="submit"] {
      width: 100%;
      background-color: white;
      color: #667eea;
      padding: 18px;
      border: none;
      border-radius: 8px;
      font-size: 18px;
      font-weight: 700;
      cursor: pointer;
      transition: all 0.3s ease;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
    }

    button[type="submit"]:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
      background-color: #f7fafc;
    }

    .footer {
      background-color: rgba(26, 32, 44, 0.95);
      color: #e2e8f0;
      text-align: center;
      padding: 30px 20px;
      margin-top: 60px;
    }

    @media (max-width: 768px) {
      html, body {
        background: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)), url('AdobeRainier.png') no-repeat center center fixed;
        background-size: cover;
      }

      .nav a {
        padding: 10px 12px;
        font-size: 13px;
      }

      .header {
        padding: 40px 25px;
        margin: 90px 15px 30px 15px;
      }

      .header h1 {
        font-size: 28px;
      }

      .header h2 {
        font-size: 18px;
      }

      .header img {
        max-width: 180px;
      }

      .main {
        padding: 0 15px 40px 15px;
      }

      .section {
        padding: 30px 25px;
        margin-bottom: 25px;
      }

      .section h2 {
        font-size: 26px;
      }

      .cta-button {
        padding: 14px 32px;
        font-size: 15px;
      }
    }
  </style>
</head>
<body>

<div class="nav">
  <a href="#about">About</a>
  <a href="#services">Specialties</a>
  <a href="#contact">Contact</a>
  <a href="#contactform" class="cta">Book Consultation</a>
</div>

<div class="header">
  <img src="photo5.jpg" alt="Adam Kaufman, Licensed Mental Health Counselor">
  <h1>Adam Kaufman, MSEd, LMHCA</h1>
  <h2>Licensed Mental Health Counselor Associate</h2>
  <div>
    <span class="credentials">CUNY Hunter College MSEd</span>
    <span class="credentials">TEAM-CBT Certified</span>
    <span class="credentials">Psychodynamic Training</span>
  </div>
  <p class="tagline">Helping you navigate life's challenges with evidence-based therapy that combines depth, insight, and practical solutions.</p>
  <a href="#contactform" class="cta-button">Schedule Your Free Consultation</a>
  <div style="margin-top: 25px;">
    <!-- Professional verification provided by Psychology Today -->
    <a href="https://www.psychologytoday.com/profile/1422560" class="sx-verified-seal"></a>
    <script type="text/javascript" src="https://member.psychologytoday.com/verified-seal.js" data-badge="13" data-id="1422560" data-code="aHR0cHM6Ly93d3cucHN5Y2hvbG9neXRvZGF5LmNvbS9hcGkvdmVyaWZpZWQtc2VhbC9zZWFscy8xMy9wcm9maWxlLzE0MjI1NjA/Y2FsbGJhY2s9c3hjYWxsYmFjaw=="></script>
    <!-- End Verification -->
  </div>
</div>

<div class="main">
  <div class="section visible" id="about">
    <h2>Welcome</h2>
    <p>I'm currently accepting new clients. As a Licensed Mental Health Counselor Associate with specialized training in both psychodynamic therapy and TEAM-CBT, I offer a unique therapeutic approach that adapts to your individual needs.</p>

    <div class="highlight-box">
      <p style="margin-bottom: 0; font-size: 17px;"><strong>My approach combines:</strong> Deep self-exploration with practical, results-focused interventions. You'll gain both insight into your patterns and concrete skills to create meaningful change.</p>
    </div>

    <p>Therapy with me is a collaborative journey of self-exploration and meaning-making. I create a safe, supportive environment where you can share openly, resolve current conflicts, and discover the life you want to lead.</p>
  </div>

  <div class="section" id="services">
    <h2>Areas of Expertise</h2>

    <h3>I specialize in helping with:</h3>
    <ul>
      <li>Depression and persistent low mood</li>
      <li>Anxiety and stress management</li>
      <li>Trauma and PTSD</li>
      <li>Relationship challenges</li>
      <li>Life transitions and identity exploration</li>
      <li>Self-understanding and personal growth</li>
    </ul>

    <h3>Professional Training & Certifications</h3>
    <ul>
      <li><strong>Master of Science in Education (MSEd)</strong> in Mental Health Counseling from CUNY Hunter College</li>
      <li><strong>Two years of intensive training</strong> in Psychoanalytic Psychotherapy at the Training Institute for Mental Health (NYC)</li>
      <li><strong>TEAM-CBT Certified</strong> (pursuing advanced certification) — an evidence-based, integrative adaptation of cognitive behavioral therapy</li>
    </ul>

    <div style="text-align: center; margin-top: 40px;">
      <a href="#contactform" class="cta-button">Ready to Begin? Schedule Your Consultation</a>
    </div>
  </div>

  <div class="section" id="contact">
    <h2>Get In Touch</h2>
    <div class="contact-info">
      <p><strong>Email:</strong> <a href="mailto:AdamDKaufmanTherapy@Gmail.com">AdamDKaufmanTherapy@Gmail.com</a></p>
      <p><strong>Phone:</strong> <a href="tel:360-296-0308">360-296-0308</a></p>
    </div>
    <p style="text-align: center; margin-top: 30px; color: #4a5568;">I typically respond within one business day. For fastest service, use the consultation form below.</p>
  </div>

  <div class="section" id="contactform">
    <h2>Schedule Your Free 15-Minute Consultation</h2>
    <p class="form-intro">Take the first step toward positive change. Fill out the form below and I'll get back to you within one business day to schedule your free consultation.</p>

    <form id="contact-form" method="post" action="https://formspree.io/f/mleqyjkz">
      <label for="communication_preference">How would you prefer to be contacted?</label>
      <select id="communication_preference" name="communication_preference" required>
        <option value="">Select one...</option>
        <option value="email">Email</option>
        <option value="phone">Phone</option>
      </select>

      <label for="name">Your Name *</label>
      <input type="text" id="name" name="name" required placeholder="Your full name">

      <label for="email">Your Email Address *</label>
      <input type="email" id="email" name="email" required placeholder="you@example.com">

      <label for="phone">Your Phone Number *</label>
      <input type="tel" id="phone" name="phone" required placeholder="(123) 456-7890">

      <label for="message">How can I help you? *</label>
      <textarea id="message" name="message" rows="5" required placeholder="Tell me a bit about what brings you to therapy..."></textarea>

      <button type="submit">Request My Free Consultation</button>
    </form>
  </div>
</div>

<div class="footer">
  <p>&copy; 2024 Adam Kaufman, MSEd, LMHCA | Licensed Mental Health Counselor Associate | University Place, Washington</p>
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
