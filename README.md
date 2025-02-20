<!DOCTYPE html>
<html lang="en" data-theme="light">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kennedy Maina | Data Analyst</title>
    <meta name="description" content="Data Analyst specializing in SQL, Python, and Data Visualization with expertise in transforming raw data into actionable insights">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
    <style>
        :root {
            --primary: #2A5C82;
            --secondary: #34ADAD;
            --accent: #FF6B6B;
            --text-color: #1a1a1a; /* Deep black for better visibility */
            --bg-color: #f9f9f9;
            --card-bg: #fff;
            --button-text: #fff;
        }

        [data-theme="dark"] {
            --primary: #34495E;
            --secondary: #27AE60;
            --accent: #F1C40F;
            --text-color: #f9f9f9;
            --bg-color: #2c3e50;
            --card-bg: #34495E;
            --button-text: #000;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
            color: var(--text-color);
        }

        body {
            line-height: 1.6;
            background: var(--bg-color);
            transition: background 0.3s, color 0.3s;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 6rem 2rem;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            color: white;
            clip-path: polygon(0 0, 100% 0, 100% 90%, 0 100%);
            position: relative;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('assets/background-pattern.jpg') repeat;
            opacity: 0.1;
            z-index: 0;
        }

        .hero-content {
            position: relative;
            z-index: 1;
        }

        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            border: 5px solid white;
            margin: 0 auto 1rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            animation: float 5s ease-in-out infinite;
        }

        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0); }
        }

        .hero-description {
            margin: 1rem 0;
            font-style: italic;
        }

        /* Theme Switch Button */
        .theme-switch-wrapper {
            display: flex;
            justify-content: flex-end;
            margin: 20px 20px 0 0;
        }

        .theme-switch {
            display: inline-block;
            height: 34px;
            position: relative;
            width: 60px;
        }

        .theme-switch input {
            display: none;
        }

        .slider {
            background-color: #ccc;
            bottom: 0;
            cursor: pointer;
            left: 0;
            position: absolute;
            right: 0;
            top: 0;
            transition: .4s;
        }

        .slider:before {
            background-color: #fff;
            bottom: 4px;
            content: "";
            height: 26px;
            left: 4px;
            position: absolute;
            transition: .4s;
            width: 26px;
        }

        input:checked + .slider {
            background-color: var(--accent);
        }

        input:checked + .slider:before {
            transform: translateX(26px);
        }

        .slider.round {
            border-radius: 34px;
        }

        .slider.round:before {
            border-radius: 50%;
        }

        /* Skills Grid */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            padding: 4rem 2rem;
            background: var(--bg-color);
        }

        .skill-card {
            background: var(--card-bg);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .skill-card::before {
            content: '';
            position: absolute;
            top: -100%;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(255, 107, 107, 0.1);
            transition: top 0.3s;
        }

        .skill-card:hover::before {
            top: 0;
        }

        .skill-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.15);
        }

        /* Projects Grid */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }

        .project-card {
            background: var(--card-bg);
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            position: relative;
            transition: transform 0.3s;
        }

        .project-card:hover {
            transform: scale(1.05);
        }

        .project-info {
            padding: 1.5rem;
            color: var(--text-color); 
        }

        .project-button {
            display: inline-block;
            background: var(--accent);
            color: var(--button-text);
            padding: 0.75rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            border: none;
            transition: all 0.3s ease;
            cursor: pointer;
            font-size: 1rem;
            margin-top: 1rem;
            position: relative;
            overflow: hidden;
        }

        .project-button::after {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.2);
            transform: skewX(-25deg);
            transition: left 0.3s;
        }

        .project-button:hover {
            background: #ff5252;
        }

        .project-button:hover::after {
            left: 100%;
        }

        /* Footer */
        .footer {
            background: var(--primary);
            color: var(--text-color);
            text-align: center;
            padding: 2rem 0;
            position: relative;
        }

        .footer::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: var(--accent);
        }

        .footer p {
            margin: 0;
            font-size: 0.9em;
        }

        .footer a {
            color: var(--secondary);
            text-decoration: none;
            transition: color 0.3s;
        }

        .footer a:hover {
            color: var(--accent);
        }

        @media (max-width: 768px) {
            .hero {
                padding: 4rem 1rem;
            }
        }
    </style>
</head>

<body>

    <div class="theme-switch-wrapper">
        <label class="theme-switch" for="checkbox">
            <input type="checkbox" id="checkbox" />
            <div class="slider round"></div>
            <span style="color: var(--text-color); margin-left: 10px;">Switch Theme</span>
        </label>
    </div>

    <header class="hero">
        <div class="hero-content">
            <img src="https://github.com/Moonwiing/report.1/raw/main/Maina.jpeg" alt="Kennedy Maina" class="profile-img">
            <h1>Kennedy Maina</h1>
            <p>Data Analyst | SQL | Python | Power BI</p>
            <p class="hero-description">I am passionate about leveraging data to uncover insights that drive strategic decisions in businesses. My love for analytics stems from the thrill of transforming raw data into actionable knowledge.</p>
            <div style="margin: 1.5rem 0;">
                <a href="https://www.linkedin.com/in/kennedy-maina-216822210" target="_blank" style="color: white; margin: 0 1rem;"><i class="fab fa-linkedin fa-2x"></i></a>
                <a href="https://github.com/Moonwiing" target="_blank" style="color: white; margin: 0 1rem;"><i class="fab fa-github fa-2x"></i></a>
                <a href="resume.pdf" download style="color: white; margin: 0 1rem;"><i class="fas fa-file-pdf fa-2x"></i></a>
            </div>
        </div>
    </header>

    <section class="skills-grid">
        <div class="skill-card" data-aos="fade-up">
            <i class="fas fa-database fa-3x" style="color: var(--primary);"></i>
            <h3>Data Analysis</h3>
            <p>Python, Pandas, NumPy</p>
        </div>
        <div class="skill-card" data-aos="fade-up" data-aos-delay="100">
            <i class="fas fa-chart-line fa-3x" style="color: var(--secondary);"></i>
            <h3>Visualization</h3>
            <p>Power BI, Tableau, Matplotlib</p>
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
            <div class="project-card" data-aos="zoom-in">
                <div class="project-info">
                    <h3>Data Analysis Report</h3>
                    <p>In-depth analysis of data trends and insights.</p>
                    <a href="https://github.com/Moonwiing/report.1/raw/main/Kennedy%20Ithagu%20Maina_demo%20report.pdf" class="project-button">View Project</a>
                </div>
            </div>
            <div class="project-card" data-aos="zoom-in">
                <div class="project-info">
                    <h3>Visual Data Representation</h3>
                    <p>Visual storytelling through data visualization.</p>
                    <a href="https://github.com/Moonwiing/report.1/raw/main/Kennedy%20Ithagu%20Maina_Visual.pdf" class="project-button">View Project</a>
                </div>
            </div>
        </div>
    </section>

    <footer class="footer">
        <p>For collaboration opportunities, inquiries, or any other matters, feel free to contact me:</p>
        <p><a href="mailto:kennedymaina573@gmail.com">kennedymaina573@gmail.com</a></p>
        <p>Or call: <a href="tel:0717999296">0717999296</a></p>
        <p>© All Rights Reserved.</p>
    </footer>

    <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
    <script>
        // Initialize animations
        AOS.init({
            duration: 1000,
            once: true
        });

        // Theme switch functionality
        document.getElementById('checkbox').addEventListener('change', function() {
            if(this.checked) {
                document.documentElement.setAttribute('data-theme', 'dark');
            } else {
                document.documentElement.setAttribute('data-theme', 'light');
            }
        });

        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>

</body>
</html>
