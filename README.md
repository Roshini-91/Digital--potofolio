<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roshini S - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        .header {
            background-color: #b8e137;
            padding: 20px;
            text-align: center;
        }
        .header h1 {
            color: #ffffff;
        }
        .header h2 {
            color: #333;
        }
        .nav {
            background-color: #d60036;
            text-align: center;
            padding: 10px;
        }
        .nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            font-size: 18px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .box {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
        .resume-btn {
            display: block;
            width: 200px;
            margin: 20px auto;
            text-align: center;
            background: black;
            color: white;
            padding: 10px;
            text-decoration: none;
            border-radius: 5px;
        }
        .resume-btn:hover {
            background: grey;
        }
        .footer {
            text-align: center;
            background: #333;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Roshini S</h1>
        <h2>Computer Application Student</h2>
    </div>

    <div class="nav">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
    </div>

    <div class="container">
        
        <div class="box" id="about">
            <h2>About Me</h2>
            <p>I am a student of Prince Shri Venkateshwara Arts and Science College, currently in my 2nd year.  
            I am pursuing a degree in Computer Applications at the University of Madras.  
            I am a hardworking person with a passion for technology.</p>
        </div>

        <div class="box" id="education">
            <h2>Education</h2>
            <p><strong>University:</strong> University of Madras</p>
            <p><strong>College:</strong> Prince Shri Venkateshwara Arts and Science College</p>
            <p><strong>Degree:</strong> Bachelor of Computer Applications (BCA) - 2nd Year</p>
        </div>

        <div class="box" id="skills">
            <h2>Skills</h2>
            <ul>
                <li>Communication</li>
                <li>Problem-Solving Skills</li>
                <li>Java Programming</li>
                <li>Creative Thinking</li>
                <li>Dubbing</li>
            </ul>
        </div>

        <div class="box" id="projects">
            <h2>Projects</h2>
            <ul>
                <li>Hangman Game</li>
                <li>Guess a Number</li>
                <li>Digital Portfolio</li>
                <li>Pattern Calculator with AWT</li>
            </ul>
        </div>

        <div class="box" id="resume">
            <h2>Resume</h2>
            <a href="your-resume-link.pdf" class="resume-btn" download>Download CV</a>
        </div>
        
    </div>

    <div class="footer">
        <p>© 2025 Roshini S. All Rights Reserved.</p>
    </div>

</body>
</html>
