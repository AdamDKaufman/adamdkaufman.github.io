<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>My Website</title>
	<style>
		body {
			background-color: #f2f2f2;
			color: #1a1a1a;
			font-family: Arial, sans-serif;
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
			background-color: #1a1a1a;
		}
		section {
			margin-bottom: 50px;
		}
		h1 {
			font-size: 36px;
			margin-bottom: 20px;
			color: #f2f2f2;
		}
		p {
			font-size: 20px;
			line-height: 1.5;
			margin-bottom: 20px;
			color: #f2f2f2;
		}
		a {
			color: #f2f2f2;
			background-color: #1a1a1a;
			padding: 10px 20px;
			border-radius: 5px;
			text-decoration: none;
			font-size: 20px;
			font-weight: bold;
			transition: all 0.3s ease-in-out;
		}
		a:hover {
			background-color: #f2f2f2;
			color: #1a1a1a;
		}
		/* Added CSS */
		header {
			background-color: #ff0000;
		}
		nav a {
			color: #f2f2f2;
			text-decoration: none;
			font-size: 20px;
			font-weight: bold;
			transition: all 0.3s ease-in-out;
			/* Added CSS */
			filter: brightness(150%);
		}
		nav a:hover {
			color: #1a1a1a;
			/* Added CSS */
			background-color: #f2f2f2;
			filter: brightness(100%);
		}
		main {
			background-color: #ff0000;
			/* Added CSS */
			filter: brightness(150%);
		}
		h1 {
			color: #f2f2f2;
			/* Added CSS */
			filter: brightness(150%);
		}
		p {
			color: #f2f2f2;
			/* Added CSS */
			filter: brightness(150%);
		}
		a {
			color: #f2f2f2;
			background-color: #1a1a1a;
			padding: 10px 20px;
			border-radius: 5px;
			text-decoration: none;
			font-size: 20px;
			font-weight: bold;
			transition: all 0.3s ease-in-out;
			/* Added CSS */
			filter: brightness(150%);
		}
		a:hover {
			background-color: #f2f2f2;
			color: #1a1a1a;
			/* Added CSS */
			filter: brightness(100%);
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

			<h1>About Me</h1>
			<p>I am a mental health counseling
