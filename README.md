The structure of a web page refers to how the content and elements are arranged and organized using HTML (HyperText Markup Language).

It's the foundation of every website — like the skeleton of a house.

🔧 Basic Structure of a Web Page
Here’s a simple example of a basic HTML page structure:

html
Copy
Edit
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My First Web Page</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>This is my first web page.</p>
  </body>
</html>
🧱 Breakdown of the Structure
Part	Purpose
<!DOCTYPE html>	Declares the document as an HTML5 page
<html>	The root element of the web page
<head>	Contains meta information (not visible on the page)
<title>	Title shown in the browser tab
<meta>	Provides metadata like character set and responsive layout info
<body>	Contains all visible content (text, images, buttons, etc.)

🧩 Inside the <body>, you can use:
<h1> to <h6> – Headings

<p> – Paragraph

<img> – Images

<a> – Links

<ul>, <ol>, <li> – Lists

<div> and <section> – Containers for layout

<header>, <nav>, <footer> – Semantic layout elements

🖼️ Visual Hierarchy
Most modern web pages follow this general structure:

css
Copy
Edit
<html>
  ├── <head>
  └── <body>
        ├── <header> – Logo, Navigation
        ├── <main>   – Page content
        │     ├── <section> – Articles, Services, etc.
        │     └── <aside> – Sidebar or Ads
        └── <footer> – Copyright, Contact info
📌 Why It's Important
It helps browsers render content correctly

Helps search engines understand the content (SEO)

Enables screen readers and accessibility tools

Organizes your page for easier styling with CSS and scripting with JavaScript

Practice Assignment: Create a Simple Web Page
 Objective:
Build a simple web page using HTML to demonstrate understanding of basic page structure and semantic elements.

 Instructions:
Create an HTML file named index.html and build a personal introduction page that includes:

Requirements:
HTML Boilerplate

Use <!DOCTYPE html>, <html>, <head>, and <body>.

Set the title to: "My First Web Page"

Inside the <body>, include:

A <header> containing:

Your name in an <h1> tag

A short welcome message in a <p> tag

A <nav> section with at least 3 navigation links (use # as href values for now)

A <main> section with:

An <h2> heading: “About Me”

A <p> paragraph introducing yourself (can be made-up)

An <img> tag displaying a picture (use any image link from the web or placeholder like https://via.placeholder.com/150)

A <footer> section with:

A copyright line (e.g. &copy; 2025 Your Name)

A contact email link using <a href="mailto:you@example.com">

(Optional):
Use <section> to group “About Me” content

Add a list (<ul>) of your 3 favorite hobbies

Add an <hr> (horizontal line) between sections

 Example Output (Visually):
markdown
Copy
Edit
-----------------------------------
|     [Your Name - h1]           |
| Welcome to my first website!  |
-----------------------------------
| Home | About | Contact         |
-----------------------------------
About Me
I'm an aspiring web developer... [image here]

Hobbies:
- Coding
- Football
- Reading
-----------------------------------
© 2025 Your Name | you@example.com
Submission:
Save the file as task1.html

Open it in the browser to check

Send a screenshot and push the file for review

