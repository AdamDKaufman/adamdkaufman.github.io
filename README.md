<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>My Website</title>
	<style>
		body {
			background-color: #1a1a1a;
			color: white;
			font-family: "Times New Roman", Times, serif;
			margin: 0;
			padding: 0;
		}
		header {
			display: flex;
			align-items: center;
			justify-content: space-between;
			padding: 20px;
			background-color: #1a1a1a;
			position: fixed;
			top: 0;
			width: 100%;
			z-index: 1;
		}
		nav ul {
			display: flex;
			list-style: none;
			margin: 0;
			padding: 0;
		}
		nav li {
			margin-left: 20px;
		}
		nav a {
			color: white;
			text-decoration: none;
			font-size: 20px;
			font-weight: bold;
			transition: all 0.3s ease-in-out;
		}
		nav a:hover {
			color: #f2f2f2;
		}
		main {
			margin-top: 100px;
			padding: 50px;
			background-color: #f2f2f2;
		}
		section {
			margin-bottom: 50px;
		}
		h1 {
			font-size: 36px;
			margin-bottom: 20px;
		}
		p {
			font-size: 20px;
			line-height: 1.5;
			margin-bottom: 20px;
		}
		a {
			color: #1a1a1a;
			background-color: white;
			padding: 10px 20px;
			border-radius: 5px;
			text-decoration: none;
			font-size: 20px;
			font-weight: bold;
			transition: all 0.3s ease-in-out;
		}
		a:hover {
			background-color: #f2f2f2;
		}
	</style>
</head>
<body>
	<header>
		<img src="Professional Photo.jpeg" alt="My Image" height="50" width="50">
		<nav>
			<ul>
				<li><a href="#about-me">About Me</a></li>
				<li><a href="#education">Education and Experiences</a></li>
				<li><a href="#contact-info">Contact Information</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section id="about-me">
			#about-me {
  			  background-color: gray;
			}

			<h1>About Me</h1>
			<p>I am a mental health counseling Master's student at Hunter College interning and training at the Training Institute for Mental Health.</p>
			<a href="Adam Kaufman Professional Resume July_10_2023.pdf">See Resume</a>
		</section>
		<section id="education">
			<h1>Education and Experiences</h1>
			<!-- Add your education and experiences here -->
		</section>
		<section id="contact-info">
			<h1>Contact Information</h1>
			<p>Email: <a href="mailto:AdamDKaufmanTherapy@Gmail.com">AdamDKaufmanTherapy@Gmail.com</a></p>
		</section>
	</main>
</body>
</html>
