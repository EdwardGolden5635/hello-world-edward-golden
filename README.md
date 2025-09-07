<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="description" content="Welcome to my personal homepage! Learn more about me, see my projects, and get in touch." />
<meta name="keywords" content="portfolio, projects, contact, homepage, HTML examples" />
<meta name="author" content="Edward Golden" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />

<link rel="stylesheet" href="style.css" />

<title>My Homepage</title>
</head>

<body>

<!--Header section with a welcome message -->
<header>
<h1>Welcome To My Homepage!!</h1>
</header>

<!-- Navigational menu that uses a bullet list -->

<nav>
<ul class="nav-flex">
<li><a href="about.html">About</a></li>
<li><a href="projects.html">Projects</a></li>
<li><a href="contact.html
">Contact</a></li>
</ul>
</Nav>

<!-- The main content area -->

<main class="main-flex">

<section id="about">
<h2>About Me</h2>
<p>Hello I am on a journey to learn HTML, CSS, and JavaScript. I am trying to develop amazing websites!</p>
</section>

<section id="projects">
<h2>My Projects</h2>

<table>
<caption>Sample Projects</caption>
<colgroup>
<col style="background-color: #F0F8FF; />
<col>
<col style="background-color: F0F8GG; />

<thead>

<tr>
<th>Project Name</th>
<th>Description</th>
<th>Image</th>
</tr>

<tbody>

<tr>
<td>Portfolio Website</td>
<td>A Personal Website To Showcase My Work And Skills.</td>
<td><img src="atlantabraveslogo.jpg" width="100" height="100"alt="Portfolio Preview" /></td>
<tr>

<tr>
<td>Game Tracker</td>
<td>A web app to track games I have played and want to play</td>
<td><img src="atlantabraveslogo.jpg"width="100" height="100" alt="Portfolio Preview" /></td>
<tr>

</tbody>

<tfoot>

<tr>
<td colspan="3">More Projects Coming Soon!</td>
</tr>

</tfoot>
</table>


</section>

<section id="contact">
<h2>Contact Me</h2>

<form class="form-flex">
<label for="name">Name:</label>
<input type="text" id="name" name="name" required />

<label for="email">Email:</label>
<input type="text" id="email" name="name" required />

<label for="subject">Subject:</label>
<input type="text" id="subject" name="name" />

<label for="message">Message:</label>
<textarea id="message" name="message" rows="5"></textarea>

<input type="submit" value="Send Message" />
</form>


</section>

</main>



<footer>
<p>&copy; &nbsp; 2025 Edward Golden &mdash; All rights reserved</p>
</footer>


</body>
</html>
