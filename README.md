<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Modern Website</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>

    <header class="header">
        <nav class="navbar">
            <div class="logo">MyBrand</div>
            <ul class="nav-links" id="navLinks">
                <li><a href="#home">Home</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="hamburger" id="hamburger">&#9776;</div>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Build Stunning Websites</h1>
            <p>Clean design. Smooth animations. Fully responsive.</p>
            <button class="btn">Get Started</button>
        </div>
    </section>

    <section id="features" class="features">
        <h2>Features</h2>
        <div class="feature-grid">
            <div class="card">
                <h3>Responsive</h3>
                <p>Looks great on mobile, tablet, and desktop.</p>
            </div>
            <div class="card">
                <h3>Modern Design</h3>
                <p>Minimalistic and elegant UI components.</p>
            </div>
            <div class="card">
                <h3>Fast</h3>
                <p>Lightweight code for blazing performance.</p>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>
            We create modern web experiences using clean code and best practices.
            This template is a starting point for any project.
        </p>
    </section>

    <section id="contact" class="contact">
        <h2>Contact</h2>
        <form id="contactForm">
            <input type="text" placeholder="Your Name" required />
            <input type="email" placeholder="Your Email" required />
            <textarea placeholder="Message" required></textarea>
            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <footer class="footer">
        <p>© 2026 MyBrand. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
