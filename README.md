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
            background-color: #f4f7fb;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: #007BFF;
            color: white;
            text-align: center;
            padding: 20px 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
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

        .box {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: background 0.3s ease, box-shadow 0.3s ease;
        }

        .box:hover {
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
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
            font-size: 0.9rem;
        }

        /* Skill Boxes */
        .skill-category {
            margin-bottom: 30px;
        }

        .skill-box {
            display: inline-block;
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 10px 15px;
            margin: 5px;
            font-size: 0.9rem;
            color: #555;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .skill-box:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }

        /* Grouped Skills Box */
        .skills-box {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 40px;
        }

        .skills-box h3 {
            margin-top: 0;
            color: #007BFF;
        }

        .skills-box .skill-category {
            margin-bottom: 20px;
        }

        .skills-box .skill-category h4 {
            font-size: 1.2rem;
            color: #555;
            margin-bottom: 10px;
        }

        .skills-box .skill-category div {
            margin-left: 15px;
        }

        .skills-box .skill-category .skill-box {
            display: inline-block;
            margin-right: 10px;
        }

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

    <!-- Header Section -->
    <header>
        <h1>Kennedy Maina</h1>
        <p>Data Analyst | SQL | Python | R | Power BI</p>
        <img src="https://github.com/Moonwiing/report.1/blob/main/Maina.jpeg" alt="Profile Picture" class="profile-picture">
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
        <div class="box">
            <p>
                I am a passionate Data Analyst with expertise in SQL, Python, R, and Power BI. 
                My goal is to transform raw data into actionable insights that drive business growth.
            </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        
        <!-- Grouped Skills Box -->
        <div class="skills-box">
            <h3>Technical Skills</h3>

            <!-- Data Visualization -->
            <div class="skill-category">
                <h4>Data Visualization</h4>
                <div>
                    <span class="skill-box">R Shiny</span>
                    <span class="skill-box">ggplot2</span>
                    <span class="skill-box">Power BI</span>
                    <span class="skill-box">Tableau</span>
                </div>
            </div>

            <!-- Database Management -->
            <div class="skill-category">
                <h4>Database Management</h4>
                <div>
                    <span class="skill-box">SQL</span>
                    <span class="skill-box">PostgreSQL</span>
                    <span class="skill-box">BigQuery</span>
                </div>
            </div>

            <!-- Programming Tools -->
            <div class="skill-category">
                <h4>Programming Tools</h4>
                <div>
                    <span class="skill-box">Python</span>
                    <span class="skill-box">R</span>
                    <span class="skill-box">Pandas</span>
                    <span class="skill-box">NumPy</span>
                </div>
            </div>

            <!-- Report Writing -->
            <div class="skill-category">
                <h4>Report Writing</h4>
                <div>
                    <span class="skill-box">Microsoft Word</span>
                    <span class="skill-box">Google Docs</span>
                    <span class="skill-box">LaTeX</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Featured Projects</h2>

        <!-- Project 1 -->
        <div class="project-box">
            <h3>Sales Trend Analysis (Coming Soon)</h3>
            <p>This project focuses on analyzing sales data to uncover trends and predict future sales. I will use tools such as Python and Power BI for analysis and visualization.</p>
        </div>

        <!-- Project 2 -->
        <div class="project-box">
            <h3>Customer Segmentation (Coming Soon)</h3>
            <p>This project aims to segment customers based on purchasing behavior using clustering algorithms in R and Python, helping businesses improve marketing strategies.</p>
        </div>

        <!-- Project 3 -->
        <div class="project-box">
            <h3>Time Series Forecasting (Coming Soon)</h3>
            <p>This project will involve forecasting future sales and demand using time series models in R and Python, leveraging libraries like ARIMA and Prophet.</p>
        </div>

        <!-- Project 4 -->
        <div class="project-box">
            <h3>Market Basket Analysis (Coming Soon)</h3>
            <p>By analyzing transaction data, this project will identify patterns in customer purchases and help businesses improve product recommendations.</p>
        </div>

    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Kennedy Maina | All rights reserved.</p>
    </footer>

</body>
</html>
