<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kennedy Maina | Data Analyst</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        header {
            background: #007BFF;
            color: white;
            text-align: center;
            padding: 20px 0;
            transition: background 0.3s ease;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        .profile-picture {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin: 20px auto;
            border: 4px solid white;
        }

        nav {
            background: #333;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
            transition: background 0.3s ease;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #007BFF;
        }

        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        h2 {
            font-size: 2rem;
            color: #007BFF;
            margin-bottom: 20px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        li {
            margin-bottom: 15px;
        }

        a {
            color: #007BFF;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        a:hover {
            color: #0056b3;
        }

        .project-box {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: background 0.3s ease, box-shadow 0.3s ease;
        }

        .project-box h3 {
            margin-top: 0;
            color: #007BFF;
        }

        .project-box p {
            color: #555;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
            transition: background 0.3s ease;
        }

        /* Dark Mode Styles */
        body.dark-mode {
            background-color: #121212;
            color: #e0e0e0;
        }

        body.dark-mode header {
            background: #1e1e1e;
        }

        body.dark-mode nav {
            background: #2c2c2c;
        }

        body.dark-mode .project-box {
            background: #1e1e1e;
            border-color: #333;
        }

        body.dark-mode footer {
            background: #2c2c2c;
        }

        /* Theme Toggle Button */
        .theme-toggle {
            position: fixed;
            top: 20px;
            right: 20px;
            background: #007BFF;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .theme-toggle:hover {
            background: #0056b3;
        }

        /* Media Queries for Responsiveness */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            .profile-picture {
                width: 120px;
                height: 120px;
            }

            section {
                padding: 30px 15px;
            }
        }
    </style>
</head>
<body>

    <!-- Theme Toggle Button -->
    <button class="theme-toggle" onclick="toggleTheme()">Switch Theme</button>

    <!-- Header Section -->
    <header>
        <h1>Kennedy Maina</h1>
        <p>Data Analyst | SQL | Python | R | Power BI</p>
        <img src="https://via.placeholder.com/150" alt="Profile Picture" class="profile-picture">
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
            <strong>Data Visualization:</strong><br>
            R Shiny, ggplot2, Power BI, Tableau
        </div>
        <div class="skill-category">
            <strong>Database Management:</strong><br>
            SQL, PostgreSQL, BigQuery
        </div>
        <div class="skill-category">
            <strong>Programming Tools:</strong><br>
            Python, R, Pandas, NumPy
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Featured Projects</h2>

        <!-- Project 1 -->
        <div class="project-box">
            <h3>Sales Trend Analysis</h3>
            <p>Analyzed sales data using R and Python to identify trends and create interactive dashboards.</p>
            <a href="https://github.com/Moonwiing/report.1/blob/main/Kennedy%20Ithagu%20Maina_report.pdf" target="_blank">View Project (PDF)</a>
        </div>

        <!-- Project 2 -->
        <div class="project-box">
            <h3>Customer Segmentation</h3>
            <p>Used R for clustering algorithms to segment customers for targeted marketing.</p>
            <a href="https://github.com/Moonwiing/report.1/blob/main/Kennedy%20Ithagu%20Maina_Visual.pdf" target="_blank">View Project (PDF)</a>
        </div>

        <!-- Project 3 -->
        <div class="project-box">
            <h3>Financial Forecasting</h3>
            <p>Built time-series models in R to predict revenue and expenses.</p>
            <p><em>Coming Soon</em></p>
        </div>

        <!-- Project 4 -->
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
        <p>&copy; 2023 Kennedy Maina. All rights reserved.</p>
    </footer>

    <!-- JavaScript for Theme Toggle -->
    <script>
        function toggleTheme() {
            document.body.classList.toggle("dark-mode");
        }
    </script>

</body>
</html>
