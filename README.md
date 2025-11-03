<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moamen Mahout - Data Analyst</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Global Styles */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        a { color: #3498db; text-decoration: none; }
        header { background-color: #ffffff; padding: 50px 20px; text-align: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        header nav h1 { margin: 0; font-size: 2em; }
        header nav ul { list-style: none; padding: 0; display: flex; justify-content: center; gap: 20px; margin: 10px 0 0 0; }
        header nav ul li { display: inline; }
        .hero { margin-top: 30px; }
        .hero h2 { font-size: 1.5em; margin-bottom: 15px; }
        section { padding: 60px 20px; max-width: 1000px; margin: 0 auto; }
        section h2 { text-align: center; margin-bottom: 40px; font-size: 2em; }
        .project-list { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .project { background-color: #ffffff; padding: 20px; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        footer { text-align: center; padding: 20px; background-color: #ffffff; box-shadow: 0 -2px 5px rgba(0,0,0,0.05); }
        /* Responsive */
        @media (max-width: 600px) { header nav ul { flex-direction: column; } }
    </style>
</head>
<body>
    <header>
        <nav>
            <h1>Moamen Mahout</h1>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="hero">
            <h2>Data Analyst</h2>
            <p>I'm a passionate Data Analyst who loves exploring data, finding insights, and turning numbers into stories that drive better decisions.</p>
        </div>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>I'm a passionate Data Analyst who loves exploring data, finding insights, and turning numbers into stories that drive better decisions.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project-list">
            <div class="project">
                <h3>Project 1</h3>
                <p>Brief description of your project. Include tools or skills used.</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>Brief description of your project. Include tools or skills used.</p>
            </div>
            <div class="project">
                <h3>Project 3</h3>
                <p>Brief description of your project. Include tools or skills used.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
        <p>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></p>
    </section>

    <footer>
        <p>© 2025 Moamen Mahout. All rights reserved.</p>
    </footer>
</body>
</html>
