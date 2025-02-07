<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kennedy Maina | Data Analyst</title>
    <meta name="description" content="Data Analyst specializing in SQL, Python, R, and Data Visualization with expertise in transforming raw data into actionable insights">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <style>
        :root {
            --primary: #2A5C82;
            --secondary: #34ADAD;
            --accent: #FF6B6B;
            --background: #f0f4f8;
            --text: #333;
            --card-bg: white;
        }

        [data-theme="dark"] {
            --primary: #34ADAD;
            --secondary: #2A5C82;
            --accent: #FF6B6B;
            --background: #1a1a1a;
            --text: #f0f4f8;
            --card-bg: #2a2a2a;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
            transition: background 0.3s, color 0.3s;
        }

        body {
            line-height: 1.6;
            background: var(--background);
            color: var(--text);
        }

        .hero {
            text-align: center;
            padding: 6rem 2rem;
            background: var(--primary);
            color: white;
            clip-path: polygon(0 0, 100% 0, 100% 90%, 0 100%);
        }

        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            border: 5px solid white;
            margin: 1rem auto;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, border-color 0.3s ease;
        }

        .profile-img:hover {
            transform: scale(1.1);
            border-color: var(--accent);
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            padding: 4rem 2rem;
        }

        .skill-card {
            background: var(--card-bg);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .skill-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }

        .project-card {
            background: var(--card-bg);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            position: relative;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
        }

        .project-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .project-info {
            padding: 1.5rem;
        }

        .project-plot {
            width: 100%;
            height: 150px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            position: relative;
            overflow: hidden;
        }

        .project-plot::before {
            content: '';
            position: absolute;
            width: 100%;
            height: 100%;
            background: repeating-linear-gradient(
                90deg,
                transparent,
                transparent 20px,
                rgba(255, 255, 255, 0.1) 20px,
                rgba(255, 255, 255, 0.1) 40px
            );
            animation: moveLines 5s linear infinite;
        }

        @keyframes moveLines {
            0% {
                transform: translateX(0);
            }
            100% {
                transform: translateX(-40px);
            }
        }

        .contact {
            padding: 4rem 2rem;
            background: var(--primary);
            color: white;
            text-align: center;
        }

        .contact a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.2rem;
        }

        .contact a:hover {
            color: var(--accent);
        }

        .theme-toggle {
            position: fixed;
            top: 20px;
            right: 20px;
            background: var(--primary);
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 50%;
            cursor: pointer;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            z-index: 1000;
        }

        .theme-toggle:hover {
            background: var(--accent);
        }

        .message-button {
            background: var(--accent);
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: background 0.3s, transform 0.3s;
            margin: 1rem 0;
        }

        .message-button:hover {
            background: #ff5252;
            transform: scale(1.05);
        }

        @media (max-width: 768px) {
            .hero {
                padding: 4rem 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Dark Mode Toggle -->
    <button class="theme-toggle" onclick="toggleTheme()">
        <i class="fas fa-moon"></i>
    </button>

    <header class="hero">
        <img src="assets/your-photo.jpg" alt="Kennedy Maina" class="profile-img">
        <h1>Kennedy Maina</h1>
        <p>Data Analyst | SQL | Python | R | Power BI</p>
        <div style="margin: 1.5rem 0;">
            <a href="https://linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin fa-2x"></i></a>
            <a href="https://github.com/yourprofile" target="_blank"><i class="fab fa-github fa-2x"></i></a>
            <a href="resume.pdf" download class="resume-button"><i class="fas fa-file-pdf fa-2x"></i> Download Resume</a>
        </div>
        <!-- Message Me Button -->
        <a href="mailto:kennedymaina573@gmail.com" class="message-button">
            <i class="fas fa-envelope"></i> Message Me
        </a>
    </header>

    <section class="skills-grid">
        <div class="skill-card" data-aos="fade-up">
            <i class="fas fa-database fa-3x" style="color: var(--primary);"></i>
            <h3>Data Analysis</h3>
            <p>Python, R, Pandas, NumPy</p>
        </div>
        <div class="skill-card" data-aos="fade-up" data-aos-delay="100">
            <i class="fas fa-chart-line fa-3x" style="color: var(--secondary);"></i>
            <h3>Data Visualization</h3>
            <p>Power BI, Tableau, ggplot2</p>
        </div>
        <div class="skill-card" data-aos="fade-up" data-aos-delay="200">
            <i class="fas fa-server fa-3x" style="color: var(--accent);"></i>
            <h3>Databases</h3>
            <p>SQL, PostgreSQL, BigQuery</p>
        </div>
    </section>

    <section style="padding: 4rem 2rem;">
        <h2 style="text-align: center; margin-bottom: 3rem;">Featured Projects</h2>
        <div class="projects-grid">
            <!-- Project 1 -->
            <div class="project-card" data-aos="zoom-in">
                <div class="project-plot"></div>
                <div class="project-info">
                    <h3>Sales Trend Analysis</h3>
                    <p>Analyzed sales data using R and Python to identify trends and create interactive dashboards.</p>
                    <button style="margin-top: 1rem;">View Project</button>
                </div>
            </div>

            <!-- Project 2 -->
            <div class="project-card" data-aos="zoom-in" data-aos-delay="100">
                <div class="project-plot"></div>
                <div class="project-info">
                    <h3>Customer Segmentation</h3>
                    <p>Used R for clustering algorithms to segment customers for targeted marketing.</p>
                    <button style="margin-top: 1rem;">View Project</button>
                </div>
            </div>

            <!-- Project 3 -->
            <div class="project-card" data-aos="zoom-in" data-aos-delay="200">
                <div class="project-plot"></div>
                <div class="project-info">
                    <h3>Financial Forecasting</h3>
                    <p>Built time-series models in R to predict revenue and expenses.</p>
                    <button style="margin-top: 1rem;">View Project</button>
                </div>
            </div>

            <!-- Project 4 -->
            <div class="project-card" data-aos="zoom-in" data-aos-delay="300">
                <div class="project-plot"></div>
                <div class="project-info">
                    <h3>Website Analytics</h3>
                    <p>Analyzed user behavior using R to improve website performance and engagement.</p>
                    <button style="margin-top: 1rem;">View Project</button>
                </div>
            </div>
        </div>
    </section>

    <section class="contact">
        <h2>Contact Me</h2>
        <p>Feel free to reach out for collaborations or opportunities!</p>
        <div style="margin: 1.5rem 0;">
            <a href="mailto:kennedymaina573@gmail.com"><i class="fas fa-envelope"></i> kennedymaina573@gmail.com</a>
            <a href="tel:+254700000000"><i class="fas fa-phone"></i> +254 700 000 000</a>
        </div>
    </section>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        // Initialize animations
        AOS.init({
            duration: 1000,
            once: true
        });

        // Dark Mode Toggle
        function toggleTheme() {
            const body = document.body;
            const themeToggle = document.querySelector('.theme-toggle');
            body.setAttribute('data-theme', body.getAttribute('data-theme') === 'dark' ? 'light' : 'dark');
            themeToggle.innerHTML = body.getAttribute('data-theme') === 'dark' ? '<i class="fas fa-sun"></i>' : '<i class="fas fa-moon"></i>';
        }

        // Set initial theme
        document.body.setAttribute('data-theme', 'light');
    </script>
</body>
</html>
