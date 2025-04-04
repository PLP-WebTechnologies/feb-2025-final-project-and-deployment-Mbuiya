# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

HTML5 Document Structure

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Section -->
    <main>
        <!-- Blog or Ecommerce Content Goes Here -->
        <section id="home">
            <h1>Welcome to My Website</h1>
            <p>Here's some introductory content.</p>
        </section>

        <!-- A Blog Post or Product Section -->
        <section id="posts">
            <article>
                <h2>Blog Post Title or Product Name</h2>
                <p>Content for blog post or product description.</p>
            </article>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>

Responsive Design

/* styles.css */

/* Basic Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

a {
    color: white;
    text-decoration: none;
}

/* Main Content */
main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

/* Footer */
footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 1rem;
    position: absolute;
    bottom: 0;
    width: 100%;
}

/* Responsive Design */
@media (max-width: 768px) {
    nav ul {
        text-align: center;
    }

    nav ul li {
        display: block;
        margin-bottom: 10px;
    }

    main {
        padding: 10px;
    }
}

JavaScript Interactivity

// script.js

// Example: Toggle Dark Mode
document.addEventListener("DOMContentLoaded", () => {
    const toggleButton = document.createElement('button');
    toggleButton.textContent = 'Toggle Dark Mode';
    document.body.appendChild(toggleButton);

    toggleButton.addEventListener('click', () => {
        document.body.classList.toggle('dark-mode');
    });
});

// Example: Alert on Page Load
window.onload = function() {
    alert("Welcome to the website!");
};

Deployment

Once your website is ready, you can deploy it using one of the following platforms:

GitHub Pages: Push your project to a GitHub repository, then enable GitHub Pages from the repository settings. It will generate a URL like https://username.github.io/repository-name.

Netlify: Drag and drop your website folder (containing index.html, styles.css, and script.js) to the Netlify dashboard, and it will provide a URL.

Vercel: Similar to Netlify, push your code to GitHub and connect the repository to Vercel for automatic deployment.



Good luck and happy coding! 🚀💻
