<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            text-decoration: none;
            color: #fff;
            margin: 0 10px;
        }
        section {
            padding: 20px;
        }
        .project {
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 10px;
            margin-bottom: 20px;
            background-color: #fff;
        }
        .project h2 {
            margin-top: 0;
        }
        footer {
            background-color: #007bff;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Portfolio</h1>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>Welcome! I'm passionate about creating innovative and user-friendly applications.</p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <p>Here are some of the skills I possess:</p>
    <ul>
        <li>Java</li>
        <li>Kotlin</li>
        <li>Android SDK</li>
        <li>XML</li>
        <li>RESTful APIs</li>
        <!-- Add more skills as needed -->
    </ul>
</section>

<section id="projects">
    <h2>Projects</h2>
    <div class="project">
        <h2>Project 1</h2>
        <p>Description of Project 1</p>
    </div>
    <div class="project">
        <h2>Project 2</h2>
        <p>Description of Project 2</p>
    </div>
    <!-- Add more projects as needed -->
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>If you'd like to get in touch, feel free to email me at <a href="mailto:yourname@example.com">yourname@example.com</a>.</p>
</section>

<footer>
    <p>&copy; 2024</p>
</footer>

</body>
</html>
