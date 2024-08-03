git clone https://github.com/dpkpunetha07/dpk.github.io)
cd dpk.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Deepak's Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Deepak's Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I'm Deepak, an IT professional with a passion for technology and problem-solving. Welcome to my portfolio!</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Project 1</h3>
                <p>Description of project 1.</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>Description of project 2.</p>
            </div>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>You can reach me at <a href="mailto:deepak@example.com">deepak@example.com</a>.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Deepak. All rights reserved.</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

.project {
    border: 1px solid #ddd;
    padding: 10px;
    margin-bottom: 10px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
git add .
git commit -m "Initial commit"
git push origin main
