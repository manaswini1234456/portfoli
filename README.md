# portfoli
/* Reset some default styles */
body, h1, h2, h3, p {
    margin: 0;
    padding: 0;
}

/* Apply some basic styling */
body {
    font-family: Arial, sans-serif;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    background-color: #333;
}

nav li {
    margin: 10px;
}

nav a {
    text-decoration: none;
    color: #fff;
}

section {
    margin: 20px;
}

.project {
    border: 1px solid #ccc;
    padding: 10px;
    margin: 10px;
    text-align: center;
}

footer {
    text-align: center;
    background-color: #333;
    color: #fff;
    padding: 10px;
}
<!DOCTYPE html>
<html lang="english,hindi,telugu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Web Developer | Designer | Achiever</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>
            Hello, I'm Manaswini. I am a passionate web developer and designer with a strong desire to learn and create amazing things. I have experience in HTML, CSS, JavaScript, and various web development technologies. My goal is to turn your ideas into beautiful and functional websites.
        </p>
    </section>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="project">
            <img src="project1.jpg" alt="Project 1">
            <h3>Project 1</h3>
            <p>Description of your project goes here.</p>
        </div>

        <div class="project">
            <img src="project2.jpg" alt="Project 2">
            <h3>Project 2</h3>
            <p>Description of your project goes here.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>If you'd like to collaborate or have any questions, feel free to get in touch:</p>
        <ul>
            <li>Email: your.email@example.com</li>
            <li>LinkedIn: <a href="https://www.linkedin.com/yourprofile" target="_blank">LinkedIn Profile</a></li>
            <li>GitHub: <a href="https://github.com/yourusername" target="_blank">GitHub Profile</a></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2023 Your Name</p>
    </footer>
</body>
</html>
