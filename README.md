<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <h2 class="logo">YourName</h2>
            <ul class="nav-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Hi, I'm <span class="highlight">Your Name</span></h1>
            <p class="hero-subtitle">I create amazing digital experiences</p>
            <div class="hero-buttons">
                <a href="#projects" class="btn btn-primary">View Work</a>
                <a href="#contact" class="btn btn-secondary">Contact Me</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>I'm a passionate developer/designer with X years of experience. I love creating beautiful, functional websites that solve real problems.</p>
                    <div class="skills">
                        <span>HTML/CSS</span>
                        <span>JavaScript</span>
                        <span>React</span>
                        <span>Node.js</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2>My Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Project 1</h3>
                    <p>A cool project description</p>
                    <a href="#" class="project-link">View Project</a>
                </div>
                <div class="project-card">
                    <h3>Project 2</h3>
                    <p>Another awesome project</p>
                    <a href="#" class="project-link">View Project</a>
                </div>
                <div class="project-card">
                    <h3>Project 3</h3>
                    <p>Third project showcase</p>
                    <a href="#" class="project-link">View Project</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Get In Touch</h2>
            <form class="contact-form">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="5" required></textarea>
                <button type="submit" class="btn btn-primary">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 YourName. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
