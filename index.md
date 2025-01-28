<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="home" class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>Web Developer & Designer</p>
    </section>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I'm a passionate developer focused on creating beautiful and functional web experiences. I specialize in front-end development and user interface design.</p>
        </section>

        <section id="projects">
            <h2>My Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Project 1</h3>
                    <p>A brief description of your first project goes here.</p>
                </div>
                <div class="project-card">
                    <h3>Project 2</h3>
                    <p>A brief description of your second project goes here.</p>
                </div>
                <div class="project-card">
                    <h3>Project 3</h3>
                    <p>A brief description of your third project goes here.</p>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <form class="contact-form">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="message">Message:</label>
                    <textarea id="message" name="message" rows="5" required></textarea>
                </div>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>