<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Narendaran - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #c8ff33;
            text-align: center;
            padding: 20px;
            color: #000;
            font-size: 24px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #d92b2b;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            font-weight: bold;
        }
        nav a:hover {
            background-color: black;
            border-radius: 5px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .section {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #d92b2b;
        }
        ul {
            list-style-type: square;
        }
        .resume {
            text-align: center;
        }
        .resume a {
            display: inline-block;
            background-color: black;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .footer {
            text-align: center;
            background-color: black;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Narendaran D</h1>
        <p>A Student</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
    </nav>

    <div class="container">
        
        <div id="about" class="section">
            <h2>About Me</h2>
            <p>I'm a <strong>Data Science</strong> undergraduate graduate and technology enthusiast, passionate about leveraging data to drive insights and solutions. Currently, I am continuing my studies to deepen my knowledge and expertise in the field. With a strong interest in data analytics, machine learning, and cybersecurity, I stay updated with the latest trends and advancements in technology.</p>
        </div>

        <div id="education" class="section">
            <h2>Education</h2>
            <p><strong>Madras University</strong> - Data Science UG Graduate</p>
        </div>

        <div id="skills" class="section">
            <h2>Skills</h2>
            <ul>
                <li>Python</li>
                <li>Java</li>
            </ul>
        </div>

        <div id="projects" class="section">
            <h2>Projects</h2>
            <ul>
                <li><a href="#">Portfolio</a></li>
            </ul>
        </div>

        <div id="resume" class="section resume">
            <h2>Resume</h2>
            <a href="#">Download CV</a>
        </div>

    </div>

    <div class="footer">
        &copy; Narendaran D
    </div>

</body>
</html>
