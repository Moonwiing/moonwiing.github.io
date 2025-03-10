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
            overflow: hidden; /* Ensure media doesn’t spill out */
        }

        .project-card:hover {
            transform: scale(1.05);
        }

        .project-card img,
        .project-card video {
            width: 100%;
            height: 150px; /* Match image height */
            object-fit: cover; /* Crop to fit */
            display: block;
        }

        /* Responsive Video Container */
        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 aspect ratio */
            height: 0;
            overflow: hidden;
            max-width: 100%;
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        .project-info {
            padding: 1.5rem;
            color: var(--text-color); 
        }

        .project-button {
            display: inline-block;
            padding: 0.75rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            border: none;
            transition: all 0.3s ease;
            cursor: pointer;
            font-size: 1rem;
            margin: 0 0.5rem; /* Space between buttons */
            position: relative;
            overflow: hidden;
        }

        .view-btn {
            background: var(--secondary);
            color: var(--button-text);
        }

        .view-btn:hover {
            background: #1e8c8c; /* Darker shade of secondary */
        }

        .download-btn {
            background: var(--accent);
            color: var(--button-text);
        }

        .download-btn:hover {
            background: #ff5252;
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
            <p>Data Analyst R | SQL | Python | Power BI</p>
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
            <p>R, Excel, SPSS, Python, Pandas, NumPy</p>
        </div>
        <div class="skill-card" data-aos="fade-up" data-aos-delay="100">
            <i class="fas fa-chart-line fa-3x" style="color: var(--secondary);"></i>
            <h3>Visualization</h3>
            <p>R-shiny, Ggplot, Spatial, Power BI, Tableau, Matplotlib</p>
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
            <!-- Updated First Project with New Image -->
            <div class="project-card" data-aos="zoom-in">
                <img src="https://github.com/Moonwiing/report.1/raw/main/Portfolio%20Development%20Project%20Continuation%20-%20Grok%20-%20Google%20Chrome%202_20_2025%208_47_57%20PM.png" alt="Data Analysis Report Preview">
                <div class="project-info">
                    <h3>Data Analysis Report</h3>
                    <p>In-depth analysis of data trends and insights.</p>
                    <div style="margin-top: 1rem;">
                        <a href="https://github.com/Moonwiing/report.1/blob/main/Kennedy%20Ithagu%20Maina_demo%20report.pdf" target="_blank" class="project-button view-btn">View</a>
                        <a href="https://github.com/Moonwiing/report.1/raw/main/Kennedy%20Ithagu%20Maina_demo%20report.pdf" download="Kennedy_Ithagu_Maina_demo_report.pdf" class="project-button download-btn">Download</a>
                    </div>
                </div>
            </div>
            <!-- Existing Second Project -->
            <div class="project-card" data-aos="zoom-in">
                <img src="https://github.com/Moonwiing/report.1/raw/main/proj%201.png" alt="Visual Data Representation Preview">
                <div class="project-info">
                    <h3>Visual Data Representation</h3>
                    <p>Visual storytelling through data visualization.</p>
                    <div style="margin-top: 1rem;">
                        <a href="https://github.com/Moonwiing/report.1/blob/main/Kennedy%20Ithagu%20Maina_Visual.pdf" target="_blank" class="project-button view-btn">View</a>
                        <a href="https://github.com/Moonwiing/report.1/raw/main/Kennedy%20Ithagu%20Maina_Visual.pdf" download="Kennedy_Ithagu_Maina_Visual.pdf" class="project-button download-btn">Download</a>
                    </div>
                </div>
            </div>
            <!-- Updated YouTube Project 1 (Power BI Dashboard) -->
            <div class="project-card" data-aos="zoom-in">
                <div class="video-container">
                    <iframe src="https://www.youtube.com/embed/ZPM3umY2XiA" title="Superstore Sales: Power BI dashboard" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                </div>
                <div class="project-info">
                    <h3>Superstore Sales: Power BI dashboard.</h3>
                    <p>A straightforward Power BI dashboard showcasing superstore sales data.</p>
                    <div style="margin-top: 1rem;">
                        <a href="https://www.youtube.com/watch?v=ZPM3umY2XiA" target="_blank" class="project-button view-btn">View on YouTube</a>
                    </div>
                </div>
            </div>
            <!-- New YouTube Project 2 (R Shiny Deep Analysis)  -->
            <div class="project-card" data-aos="zoom-in">
                <div class="video-container">
                    <iframe src="https://www.youtube.com/embed/7tUJEf5L4WU" title="Power BI Dashboard" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                </div>
                <div class="project-info">
                    <h3>Superstore Sales: R shiny dashboard.</h3>
                    <p>In-depth analysis featuring spatial analysis, forecasting, and interactive R Shiny visualizations.</p>
                    <div style="margin-top: 1rem;">
                        <a href="https://www.youtube.com/watch?v=7tUJEf5L4WU" target="_blank" class="project-button view-btn">View on YouTube</a>
                    </div>
                </div>
            </div>
            <!-- Remaining Video Projects -->
            <div class="project-card" data-aos="zoom-in">
                <video controls>
                    <source src="https://github.com/Moonwiing/report.1/raw/main/project5.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <div class="project-info">
                    <h3>Project 5: COMMING SOON</h3>
                    <p>REAL TIME EXCEL-SQL-R-POWER BI PIPELINES- for data analysis by just pressing a button in seconds.</p>
                    <div style="margin-top: 1rem;">
                        <a href="https://github.com/Moonwiing/report.1/blob/main/project5.mp4" target="_blank" class="project-button view-btn">View</a>
                        <a href="https://github.com/Moonwiing/report.1/raw/main/project5.mp4" download="project5.mp4" class="project-button download-btn">Download</a>
                    </div>
                </div>
            </div>
            <div class="project-card" data-aos="zoom-in">
                <video controls>
                    <source src="https://github.com/Moonwiing/report.1/raw/main/project6.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <div class="project-info">
                    <h3>Project 6: COMMING SOON</h3>
                    <p>Creating a Data imputation model to determine the impacts by percentage and an automatic data imputation ML.</p>
                    <div style="margin-top: 1rem;">
                        <a href="https://github.com/Moonwiing/report.1/blob/main/project6.mp4" target="_blank" class="project-button view-btn">View</a>
                        <a href="https://github.com/Moonwiing/report.1/raw/main/project6.mp4" download="project6.mp4" class="project-button download-btn">Download</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="footer">
        <p>For collaboration opportunities and inquiries feel free to contact me:</p>
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
