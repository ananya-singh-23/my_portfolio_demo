# my_portfolio_demo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- NAVBAR -->
    <nav class="navbar">
        <div class="nav-container">
            <h1 class="logo">My Portfolio</h1>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- MAIN -->
    <main class="container">

        <!-- HERO -->
        <section id="home" class="hero">
            <h1>Hello! Welcome to My Creative Space</h1>
            <p>
                I'm a budding web developer passionate about building
                clean, modern, and user-friendly websites.
               
            </p>
        </section>

        <!-- ABOUT -->
        <section id="about" class="section">
            <div class="card about-card">
                <img class="profile-img" src="me.jpeg" alt="Ananya Singh">
                <h2>About Me</h2>
                <p>
                    Hello! I am a self-taught developer who loves turning complex
                    problems into simple, beautiful interfaces. I enjoy learning
                    new technologies and writing clean, efficient code.
                    <ul type="none"> <!--unordered list-->

        <li>Name: Ananya Singh</li>
        <li>From rourkela</li>
        <li>Email: ananyasingh8763@gmail.com</li>
        <li>Currently studying  B.Tech in Computer Science at Veer Surendra Sai University of Technology</li>
    </ul>
                </p>
            </div>
        </section>

        <!-- SKILLS -->
        <section id="skills" class="section">
            <h2 class="section-title">My Skills</h2>
            <div class="grid">
                <div class="skill-card">HTML</div>
                <div class="skill-card">C language</div>
                <div class="skill-card">C++</div>
                <div class="skill-card">Python</div>
                <div class="skill-card">MYSQL</div>

            </div>
        </section>

   

        <!-- CONTACT -->
        <section id="contact" class="section">
            <div class="card contact-card">
                <h2>Get In Touch</h2>
<br>
                    <ul type="disc">
                        <li><a href="mailto:ananyasingh8763@gmail.com">My Email</a>
                        </li>
                        <li>  <a href="https://www.linkedin.com/in/ananya-singh-a7b598379?utm_source=share_via&utm_content=profile&utm_medium=member_android" target="_blank">LinkedIn</a></li>
                        <li><a href="https://github.com/ananyasingh8763" target="_blank">GitHub</a></li>
                    </ul>
                  

            </div>
        </section>

    </main>

    <!-- FOOTER -->
    <footer>
        <p>© 2026 My Portfolio. All rights reserved.</p>
    </footer>

</body>
</html>
