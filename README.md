<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #eef2f3;
            color: #2c3e50;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(45deg, #6a11cb, #2575fc);
            color: white;
            text-align: center;
            padding: 50px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin: 0;
        }

        header p {
            font-size: 1.2rem;
            margin: 10px 0 0;
        }

        nav {
            display: flex;
            justify-content: center;
            margin: 20px 0;
        }

        nav a {
            text-decoration: none;
            color: #2c3e50;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #6a11cb;
        }

        section {
            max-width: 900px;
            margin: 30px auto;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            color: #6a11cb;
            margin-bottom: 20px;
        }

        section p,
        section ul {
            margin: 0 0 15px;
        }

        ul {
            list-style-type: square;
            padding-left: 20px;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 30px;
        }

        footer p {
            margin: 0;
        }

        .button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background: #6a11cb;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .button:hover {
            background: #2575fc;
        }
    </style>
</head>

<body>
    <header>
        <h1>Hello, I&#39;m Aman Thakur</h1>
        <p>Aspiring Developer | Learner | Innovator</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Welcome to my portfolio! I&#39;m a passionate developer eager to learn and grow in the tech world. I enjoy solving problems, building creative projects, and collaborating with others to bring ideas to life.</p>
    </section>

    <section id="skills">
        <h2>My Skills</h2>
        <ul>
            <li>HTML, CSS, and JavaScript</li>
            <li>Responsive Web Design</li>
            <li>Basic Python Programming</li>
            <li>Version Control with Git</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <p>Here are some of the projects I&#39;ve worked on:</p>
        <ul>
            <li><strong>Portfolio Starter:</strong> A simple personal website to showcase my journey (this website!).</li>
            <li><strong>Coming Soon:</strong> Stay tuned for more exciting projects as I continue learning.</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>If you&#39;d like to connect, feel free to reach out:</p>
        <p>Email: <a href="mailto:yourname@example.com">newsaajabholi@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/">https://www.linkedin.com/in/aman-thakur-329963248/?originalSubdomain=it</a></p>
        <a class="button" href="mailto:newsaajabholi@gmail.com">Get in Touch</a>
    </section>

    <footer>
        <p>&copy; 2024 Aman Thakur. Crafted with ❤️ and passion.</p>
    </footer>
</body>

</html>
