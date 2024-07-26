<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="container">
                <h1>My Portfolio</h1>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="#skills">Skills</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>HI GUYS...I'm a web developer with a passion for creating stunning websites.</p>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>My Projects</h2>
            <div class="project">
                <h3>Project One</h3>
                <p>Explanation for project 1</p>
                <a href="#Project1"></a>
            </div>
            <div class="project">
                <h3>Project Two</h3>
                <p>Explanation for project 2</p>
                <a href="#Project2"></a>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <form action="submit_form.php" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>contact me for furthur information</p>
        </div>
    </footer>
</body>
</html>
