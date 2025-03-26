<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Balaji S - Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #e63946;
            color: black;
        }
        .header {
            background-color: #a8eb12;
            text-align: center;
            padding: 30px;
            font-size: 28px;
            font-weight: bold;
        }
        .sub-header {
            text-align: center;
            font-size: 18px;
            font-style: italic;
            margin-bottom: 10px;
        }
        .profile-img {
            display: block;
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 10px auto;
            border: 3px solid #000;
        }
        .nav {
            text-align: center;
            padding: 15px;
            background-color: #d90429;
        }
        .nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
        }
        .container {
            width: 80%;
            margin: auto;
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            margin-top: 20px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.2);
        }
        h2 {
            color: #e63946;
        }
        ul {
            padding-left: 20px;
        }
        .resume-btn {
            display: block;
            text-align: center;
            margin-top: 20px;
            padding: 12px;
            background-color: black;
            color: white;
            text-decoration: none;
            font-weight: bold;
            width: 180px;
            margin-left: auto;
            margin-right: auto;
            border-radius: 5px;
            font-size: 16px;
        }
        .footer {
            text-align: center;
            padding: 15px;
            background-color: black;
            color: white;
            margin-top: 30px;
        }
        .contact {
            text-align: center;
            margin-top: 20px;
        }
        .contact a {
            color: #e63946;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="header">Balaji S</div>
    <div class="sub-header">Student | Programme Developer</div>
    
    <img src="profile.jpg" alt="Profile Picture" class="profile-img">

    <div class="nav">
        <a href="#">About</a>
        <a href="#">Education</a>
        <a href="#">Skills</a>
        <a href="#">Projects</a>
        <a href="#">Resume</a>
        <a href="#">Contact</a>
    </div>

    <div class="container">
        <h2>About Me</h2>
        <p>Pursuing II YEAR OF BCA. MUSIC LOVER. PROGRAMME DEVELOPER.</p>
    </div>

    <div class="container">
        <h2>Education</h2>
        <p>II BCA</p>
    </div>

    <div class="container">
        <h2>Skills</h2>
        <ul>
            <li>Web Developing</li>
            <li>Administration</li>
            <li>Teaching</li>
            <li>Handling Heavy Tasks</li>
        </ul>
    </div>

    <div class="container">
        <h2>Projects</h2>
        <ul>
            <li>Data Handler</li>
        </ul>
    </div>

    <div class="container">
        <h2>Resume</h2>
        <a href="resume.pdf" class="resume-btn" download>Download CV</a>
    </div>

    <div class="container contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:balaji@example.com">balaji@example.com</a></p>
        <p>LinkedIn: <a href="#">linkedin.com/in/balaji</a></p>
        <p>GitHub: <a href="#">github.com/balaji</a></p>
    </div>

    <div class="footer">© 2025 Balaji S</div>

</body>
</html>
