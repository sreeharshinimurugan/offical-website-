
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Sreeharshini's portfolio - Computer Science student and aspiring software developer.">
    <title>Sreeharshini | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        :root {
            --background: #0b1120;
            --card: #151f33;
            --accent: #64d8cb;
            --text: #f1f5f9;
            --muted: #a7b3c7;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: var(--background);
            color: var(--text);
            line-height: 1.7;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        .container {
            width: 90%;
            max-width: 1100px;
            margin: auto;
        }

        header {
            position: sticky;
            top: 0;
            z-index: 10;
            background: #0b1120;
            border-bottom: 1px solid #243047;
        }

        nav {
            min-height: 72px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 20px;
        }

        .logo {
            font-size: 1.4rem;
            font-weight: bold;
            color: var(--accent);
        }

        .nav-links {
            display: flex;
            gap: 24px;
            flex-wrap: wrap;
        }

        .nav-links a {
            color: var(--muted);
            font-size: 0.95rem;
        }

        .nav-links a:hover {
            color: var(--accent);
        }

        section {
            padding: 80px 0;
            scroll-margin-top: 70px;
        }

        .hero {
            min-height: 78vh;
            display: flex;
            align-items: center;
        }

        .hero-content {
            max-width: 760px;
        }

        .eyebrow {
            color: var(--accent);
            font-weight: bold;
            letter-spacing: 2px;
            text-transform: uppercase;
            font-size: 0.85rem;
        }

        h1 {
            font-size: clamp(2.5rem, 7vw, 4.5rem);
            line-height: 1.15;
            margin: 18px 0;
        }

        h1 span {
            color: var(--accent);
        }

        .hero p,
        .section-text {
            color: var(--muted);
            max-width: 700px;
        }

        .buttons {
            display: flex;
            flex-wrap: wrap;
            gap: 14px;
            margin-top: 28px;
        }

        .button {
            display: inline-block;
            padding: 11px 22px;
            border-radius: 8px;
            border: 1px solid var(--accent);
            font-weight: bold;
        }

        .button.primary {
            background: var(--accent);
            color: #0b1120;
        }

        .button:hover {
            opacity: 0.85;
        }

        .section-title {
            font-size: 2rem;
            margin-bottom: 12px;
        }

        .section-title span {
            color: var(--accent);
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(
                auto-fit, minmax(220px, 1fr)
            );
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: var(--card);
            border: 1px solid #27344c;
            border-radius: 14px;
            padding: 25px;
            transition: transform 0.2s;
        }

        .card:hover {
            transform: translateY(-4px);
        }

        .card h3 {
            margin-bottom: 10px;
            color: var(--accent);
        }

        .card p {
            color: var(--muted);
        }

        .tag {
            display: inline-block;
            margin: 12px 5px 0 0;
            padding: 5px 12px;
            border: 1px solid #35445d;
            border-radius: 20px;
            color: var(--muted);
            font-size: 0.85rem;
        }

        .contact-card {
            background: var(--card);
            border: 1px solid #27344c;
            border-radius: 14px;
            padding: 30px;
            margin-top: 25px;
        }

        .contact-card p {
            margin: 10px 0;
            color: var(--muted);
            overflow-wrap: anywhere;
        }

        .contact-card a {
            color: var(--accent);
        }

        footer {
            text-align: center;
            padding: 25px 10px;
            border-top: 1px solid #243047;
            color: var(--muted);
            font-size: 0.9rem;
        }

        @media (max-width: 600px) {
            nav {
                padding: 15px 0;
                align-items: flex-start;
                flex-direction: column;
            }

            .nav-links {
                gap: 14px;
            }

            section {
                padding: 60px 0;
            }

            .hero {
                min-height: 65vh;
            }
        }
    </style>
</head>

<body>

    <header>
        <nav class="container">
            <a class="logo" href="#home">Sreeharshini.</a>

            <div class="nav-links">
                <a href="#home">Home</a>
                <a href="#about">About</a>
                <a href="#education">Education</a>
                <a href="#skills">Skills</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <main>
        <!-- HOME -->
        <section class="hero" id="home">
            <div class="container hero-content">
                <p class="eyebrow">Welcome to my portfolio</p>

                <h1>
                    Hi, I'm <span>Sreeharshini</span>
                </h1>

                <h2>Computer Science Student</h2>

                <p>
                    An aspiring software developer passionate about
                    programming, problem-solving, and technology.
                    I am building my technical knowledge through
                    continuous learning and practical projects.
                </p>

                <div class="buttons">
                    <a class="button primary" href="#projects">
                        Explore My Work
                    </a>

                    <a class="button" href="#contact">
                        Contact Me
                    </a>
                </div>
            </div>
        </section>

        <!-- ABOUT -->
        <section id="about">
            <div class="container">
                <p class="eyebrow">Get to know me</p>
                <h2 class="section-title">
                    About <span>Me</span>
                </h2>

                <p class="section-text">
                    I am a Bachelor of Science in Computer Science
                    student at Bishop Heber College. I am interested
                    in learning programming concepts, developing
                    logical thinking, and exploring how technology
                    can solve real-world problems.
                    <br><br>
                    I aim to strengthen my technical abilities,
                    gain practical experience, and build a strong
                    foundation for a career in software development.
                </p>
            </div>
        </section>

        <!-- EDUCATION -->
        <section id="education">
            <div class="container">
                <p class="eyebrow">My academic journey</p>
                <h2 class="section-title">
                    <span>Education</span>
                </h2>

                <div class="cards">
                    <article class="card">
                        <h3>B.Sc. Computer Science (Aided)</h3>
                        <p>Bishop Heber College</p>
                        <p>Academic period: 2026–2029</p>
                    </article>
                </div>
            </div>
        </section>

        <!-- SKILLS -->
        <section id="skills">
            <div class="container">
                <p class="eyebrow">What I am learning</p>
                <h2 class="section-title">
                    Technical <span>Skills</span>
                </h2>

                <p class="section-text">
                    My current technical skills and areas of learning.
                </p>

                <div class="cards">
                    <article class="card">
                        <h3>HTML</h3>
                        <p>
                            Creating structured and accessible
                            web pages.
                        </p>
                    </article>

                    <article class="card">
                        <h3>CSS</h3>
                        <p>
                            Styling web pages with layouts,
                            responsive design, and visual elements.
                        </p>
                    </article>

                    <article class="card">
                        <h3>Python</h3>
                        <p>
                            Learning programming fundamentals,
                            logical problem-solving, and automation.
                        </p>
                    </article>
                </div>
            </div>
        </section>

        <!-- PROJECTS -->
        <section id="projects">
            <div class="container">
                <p class="eyebrow">My practical work</p>
                <h2 class="section-title">
                    Featured <span>Projects</span>
                </h2>

                <p class="section-text">
                    A collection of academic projects and practical
                    work that demonstrates my learning and growth.
                </p>

                <div class="cards">
                    <article class="card">
                        <h3>Bank Management System</h3>
                        <p>
                            An academic programming project focused
                            on basic banking operations, account
                            management, and transaction handling.
                        </p>
                        <span class="tag">C Programming</span>
                    </article>

                    <article class="card">
                        <h3>Personal Portfolio</h3>
                        <p>
                            A personal website presenting my
                            education, technical skills, projects,
                            and contact information.
                        </p>
                        <span class="tag">HTML</span>
                        <span class="tag">CSS</span>
                    </article>
                </div>
            </div>
        </section>

        <!-- CONTACT -->
        <section id="contact">
            <div class="container">
                <p class="eyebrow">Let's connect</p>
                <h2 class="section-title">
                    Contact <span>Me</span>
                </h2>

                <p class="section-text">
                    I welcome opportunities to learn, collaborate,
                    and develop my skills through meaningful projects.
                </p>

                <div class="contact-card">
                    <p>
                        <strong>Phone:</strong>
                        <a href="tel:7200507767">7200507767</a>
                    </p>

                    <p>
                        <strong>College:</strong>
                        Bishop Heber College
                    </p>

                    <p>
                        <strong>Course:</strong>
                        B.Sc. Computer Science (Aided)
                    </p>

                    <p>
                        <strong>Academic period:</strong>
                        2026–2029
                    </p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>
            &copy; 2026 Sreeharshini. All rights reserved.
        </p>
        <p>Designed with a focus on simplicity and professionalism.</p>
    </footer>

</body>
</html>
