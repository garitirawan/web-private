document.getElementById('contactForm').onsubmit = function(e) {
    e.preventDefault();
    document.getElementById('formMessage').innerText = "Thank you for reaching out! (Form not actually connected.)";
    this.reset();
};
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f5f5f5;
    color: #222;
}
header {
    background: #333;
    color: white;
    padding: 0.5em 0;
}
nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 2em;
    margin: 0;
    padding: 0;
}
nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}
.section {
    padding: 3em 0;
    background: white;
    margin-bottom: 1em;
}
.container {
    width: 90%;
    max-width: 900px;
    margin: 0 auto;
}
.projects-list {
    display: flex;
    flex-wrap: wrap;
    gap: 1em;
}
.project-card {
    background: #eee;
    padding: 1em;
    border-radius: 8px;
    flex: 1 1 250px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.07);
}
footer {
    text-align: center;
    padding: 1.5em 0;
    background: #333;
    color: white;
    margin-top: 2em;
}
form {
    display: flex;
    flex-direction: column;
    gap: 1em;
    max-width: 400px;
}
input, textarea {
    padding: 0.5em;
    border: 1px solid #ccc;
    border-radius: 6px;
}
button {
    background: #333;
    color: white;
    border: none;
    border-radius: 6px;
    padding: 0.7em;
    font-size: 1em;
    cursor: pointer;
    transition: background 0.2s;
}
button:hover {
    background: #555;
}
#formMessage {
    margin-top: 1em;
    color: green;
}
@media (max-width: 700px) {
    .projects-list {
        flex-direction: column;
    }
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Your Name - Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="home" class="section">
        <div class="container">
            <h1>Your Name</h1>
            <p>Welcome to my portfolio website!</p>
        </div>
    </section>
    <section id="about" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>This is where you write a short introduction about yourself, your skills, background, and interests.</p>
        </div>
    </section>
    <section id="projects" class="section">
        <div class="container">
            <h2>Projects</h2>
            <div class="projects-list">
                <div class="project-card">
                    <h3>Project Title</h3>
                    <p>Short description of the project.</p>
                    <a href="#" target="_blank">View Project</a>
                </div>
                <!-- Add more project cards as needed -->
            </div>
        </div>
    </section>
    <section id="contact" class="section">
        <div class="container">
            <h2>Contact</h2>
            <form id="contactForm">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit">Send</button>
            </form>
            <div id="formMessage"></div>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
