# 🎨 Assignment: CSS Basics & The Box Model

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title> & CSS Box model and HTML Demo</title>
	<link rel="stylesheet" href="styles.css">
</head>
<body>
	<header>
		<h1> CSS Box Model and HTML Demo</h1>
	</header>
	<nav>
		<a href="#home">Home</a>
		<a href="#about">About</a>
		<a href="#contact">Contact Us</a>
	</nav>
	<div class="container">
		<h2>Love</h2>
		<p>Love is an unconditional feeling or action towards a person. It can be Philo, Eros or Agape.</p>
		<div class="card">
			<h3>Philo</h3>
			<p>This is a brotherly love.</p>
			<button class="button">Click Me</button>
		</div>
		<div class="card">
			<h3>Eros and Agape</h3>
			<p>Eros love is between husband and wife. It is not sustaninable because it does not exist all the time. But agape which is the love of God towards one another is sustainable because is unconditional love.</p>
			<button class="button">Learn More</button>
		</div>
	</div>
</body>
</html>

/*css codes*/

body {
    font-family: Arial, sans-serif;
    background-color: #a397c2;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4a90e2;
    color: #721717;
    padding: 24px 0;
    text-align: center;
    margin-bottom: 24px;
    border-bottom: 4px solid #357abd;
}

nav {
    background-color: #fff;
    border: 2px solid #4a90e2;
    margin: 0 auto 24px auto;
    padding: 12px 0;
    width: 80%;
    border-radius: 8px;
    text-align: center;
}

nav a {
    color: #4a90e2;
    text-decoration: none;
    margin: 0 16px;
    font-weight: bold;
    padding: 8px 16px;
    border-radius: 4px;
    transition: background 0.2s;
}

nav a:hover {
    background-color: #e3f0fc;
}

.container {
    background-color: #fff;
    border: 2px solid #e2e2e2;
    margin: 0 auto 32px auto;
    padding: 32px;
    width: 80%;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}

h1, h2, h3 {
    margin-top: 0;
    margin-bottom: 16px;
    padding: 8px 0;
    border-bottom: 2px solid #e2e2e2;
    background-color: #e3f0fc;
}

p {
    margin: 16px 0;
    padding: 12px;
    background-color: #f9f9f9;
    border: 1px dashed #bdbdbd;
    border-radius: 6px;
}

.card {
    background-color: #f0f8ff;
    border: 2px solid #4a90e2;
    border-radius: 10px;
    padding: 24px;
    margin: 24px 0;
    box-shadow: 0 2px 6px rgba(74,144,226,0.08);
}

.button {
    display: inline-block;
    background-color: #4a90e2;
    color: #fff;
    border: none;
    border-radius: 6px;
    padding: 12px 24px;
    margin: 12px 0;
    cursor: pointer;
    font-size: 1rem;
    font-weight: bold;
    box-shadow: 0 1px 4px rgba(74,144,226,0.15);
    transition: background 0.2s;
}

.button:hover {
    background-color: #357abd;
}

























## Overview

This assignment introduces you to the foundational principles of CSS—how to style web content, apply essential styling properties, and understand the powerful concept of the CSS Box Model. You’ll practice writing clean, organized CSS that brings structure and visual appeal to an HTML page.

## Objective

Your goal is to create a visually styled web page using only CSS. You will apply basic styling rules to text, backgrounds, and layout elements, and demonstrate an understanding of how the CSS Box Model affects spacing and sizing on the page.

## What You'll Practice

* Connecting CSS to your HTML (external stylesheet)
* Using basic CSS properties such as `color`, `font-size`, `margin`, `padding`, `border`, and `background`
* Structuring your layout with awareness of how the Box Model influences spacing and dimensions
* Writing clean and maintainable CSS selectors and rules

## Instructions

Start with a basic HTML structure and create a separate CSS file named `styles.css`. Link it to your HTML file. Apply various styles to headings, paragraphs, and container sections.

Use the Box Model deliberately—experiment with margin, padding, and borders to see how they affect the layout. Apply background colors to visualize box boundaries. You may also style buttons, navigation, and card-like sections to demonstrate your grasp of spacing and alignment.

No JavaScript or external CSS libraries (like Bootstrap) should be used.

## Deliverables

Submit the following files:

* `index.html`: A basic HTML page with structured content.
* `styles.css`: Your external stylesheet containing all your CSS rules.

Both files should work together to showcase:

* Proper use of selectors and basic styling properties
* Clear implementation of the CSS Box Model
* Consistent spacing, sizing, and layout styling

## Tips

* Correct linkage of HTML and CSS files
* Use of appropriate CSS selectors and properties
* Demonstration of the Box Model through visual layout (clear use of margin, padding, and borders)
* Readability and organization of CSS code (indentation, comments, spacing)
* Overall appearance and clarity of styled content
