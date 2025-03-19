<!DOCTYPE html>
<html>
<head>
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #84a6e9;
        }
        header {
            background-color: #941919;
            color: #fff;
            text-align: center;
            padding: 2rem 0;
            position: relative;
        }
        .header-content h1 {
            font-size: 2.5rem;
        }
        .profile-picture {
            width: 100px;
            height: 100px;
            border-radius: 75%;
            object-fit: cover;
            position: absolute;
            top: 75px;
            left: 75px;
        }
        nav {
            background-color: #333;
            color: #fff;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: #fff;
        }
        .section-content {
            background-color: #fff;
            padding: 2rem;
            margin: 1rem;
            border-radius: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: justify;
        }
        .download-button {
            background-color: #333;
            color: #fff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 20px;
            display: inline-block;
            margin-top: 10px;
            align-self: center;
        }
        .download-button:hover {
            background-color: #555;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>

    <header>
        <div class="header-content">
            <img src="your-image-path.jpg" class="profile-picture">
            <h1>DIVYAKRISHNAN M</h1>
            <p>COLLEGE STUDENT</p>
            <p>AGURCHAND MANMULL JAIN COLLEGE, MEENAMBAKKAM, CHENNAI</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#resume">Resume</a></li>
            <li><a href="#github">GitHub</a></li> <!-- Added GitHub Link -->
        </ul>
    </nav>

    <section id="about">
        <div class="section-content">
            <h2>About Me</h2>
            <p>I'm studying BCA at AM Jain College. I have expertise in CorelDRAW designing.</p>
        </div>
    </section>

    <section id="education">
        <div class="section-content">
            <h2>Education</h2>
            <p>12th Completed</p>
            <p>BCA IN PROGRESS</p>
            <p>Expected Completion: 2026</p>
        </div>
    </section>

    <section id="skills">
        <div class="section-content">
            <h2>Skills</h2>
            <ul>
                <li>Microsoft Excel</li>
                <li>Microsoft Word</li>
                <li>CorelDRAW</li>
            </ul>
        </div>
    </section>

    <section id="resume">
        <div class="section-content">
            <center>
                <h2>Resume</h2>
                <a href="your-resume-link.pdf" target="_blank" class="download-button">Download CV</a>
            </center>
        </div>
    </section>

    <section id="github">
        <div class="section-content">
            <h2>GitHub</h2>
            <p>Check out my projects on GitHub:</p>
            <a href="https://github.com/yourgithubusername" target="_blank" class="download-button">Visit GitHub</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 DIVYAKRISHNAN M | <a href="https://github.com/yourgithubusername" target="_blank" style="color: #fff;">GitHub</a></p>
    </footer>

    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>

</body>
</html>
