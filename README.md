
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kennedy Maina | Data Analyst</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f1f3f4;
            color: #333;
            line-height: 1.6;
            overflow-x: hidden;
        }

        header {
            background: linear-gradient(45deg, #007BFF, #00aaff);
            color: white;
            text-align: center;
            padding: 60px 0;
            position: relative;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            margin: 0;
            font-size: 3rem;
            font-weight: 600;
        }

        header p {
            font-size: 1.25rem;
            margin-top: 10px;
        }

        .profile-picture {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            object-fit: cover;
            margin: 30px auto;
            border: 6px solid white;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s ease-in-out;
        }

        .profile-picture:hover {
            transform: scale(1.1);
        }

        nav {
            background: #333;
            color: white;
            display: flex;
            justify-content: center;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-weight: 500;
            font-size: 1rem;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #00aaff;
        }

        section {
            padding: 60px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        h2 {
            font-size: 2.5rem;
            color: #007BFF;
            margin-bottom: 30px;
            text-align: center;
            font-weight: 600;
        }

        ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        li {
            margin-bottom: 20px;
            font-size: 1.1rem;
        }

        a {
            color: #007BFF;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        a:hover {
            color: #00aaff;
        }

        .box {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 30px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .box:hover {
            transform: translateY(-10px);
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.2);
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 40px 0;
            margin-top: 40px;
            position: relative;
        }

        /* Skill Boxes */
        .skill-category {
            margin-bottom: 50px;
        }

        .skill-box {
            display: inline-block;
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 12px 20px;
            margin: 8px;
            font-size: 1rem;
            color: #555;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .skill-box:hover {
            transform: scale(1.1);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }

        /* Projects Section */
        .project-box {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 12px;
            padding: 25px;
            margin-bottom: 30px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project-box h3 {
            margin-top: 0;
            color: #007BFF;
            font-size: 1.5rem;
        }

        .project-box p {
            font-size: 1rem;
            color: #555;
        }

        .project-box a {
            font-size: 1.1rem;
            color: #007BFF;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .project-box a:hover {
            color: #00aaff;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            .profile-picture {
                width: 140px;
                height: 140px;
            }

            section {
                padding: 40px 15px;
            }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Kennedy Maina</h1>
        <p>Data Analyst | SQL | Python | R | Power BI</p>
        <img src="https://github.com/Moonwiing/report.1/blob/main/Maina.jpeg?raw=true" alt="Profile Picture" class="profile-picture">
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>
            I am a passionate Data Analyst with expertise in SQL, Python, R, and Power BI. 
            My goal is to transform raw data into actionable insights that drive business growth.
        </p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <div class="skill-category">
            <h3>Data Visualization</h3>
            <div>
                <span class="skill-box">R Shiny</span>
                <span class="skill-box">ggplot2</span>
                <span class="skill-box">Power BI</span>
                <span class="skill-box">Tableau</span>
            </div>
        </div>
        <div class="skill-category">
            <h3>Database Management</h3>
            <div>
                <span class="skill-box">SQL</span>
                <span class="skill-box">PostgreSQL</span>
                <span class="skill-box">BigQuery</span>
            </div>
        </div>
        <div class="skill-category">
            <h3>Programming Tools</h3>
            <div>
                <span class="skill-box">Python</span>
                <span class="skill-box">R</span>
                <span class="skill-box">Pandas</span>
                <span class="skill-box">NumPy</span>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Featured Projects</h2>
        <div class="project-box">
            <h3>Sales Trend Analysis</h3>
            <p>Analyzed sales data using R and Python to identify trends and create interactive dashboards.</p>
            <a href="https://github.com/Moonwiing/report.1/blob/main/Kennedy%20Ithagu%20Maina_report.pdf" target="_blank">View Project (PDF)</a>
        </div>
        <div class="project-box">
            <h3>Customer Segmentation</h3>
            <p>Used R for clustering algorithms to segment customers for targeted marketing.</p>
            <a href="https://github.com/Moonwiing/report.1/blob/main/Kennedy%20Ithagu%20Maina_Visual.pdf" target="_blank">View Project (PDF)</a>
        </div>
        <div class="project-box">
            <h3>Financial Forecasting</h3>
            <p>Built time-series models in R to predict revenue and expenses.</p>
            <p><em>Coming Soon</em></p>
        </div>
        <div class="project-box">
            <h3>Website Analytics</h3>
            <p>Analyzed user behavior using R to improve website performance and engagement.</p>
            <p><em>Coming Soon</em></p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Feel free to reach out for collaborations or opportunities!</p>
        <p>Email: <a href="mailto:kennedymaina573@gmail.com">kennedymaina573@gmail.com</a></p>
        <p>Phone: +254 700 000 000</p>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Kennedy Maina | All Rights Reserved</p>
    </footer>

</body>
</html>
