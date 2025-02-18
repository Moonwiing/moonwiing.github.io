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
        }

        header {
            background: #007BFF;
            color: white;
            text-align: center;
            padding: 20px 0;
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

        .project-title {
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .project-description {
            color: #555;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }

        footer p {
            margin: 0;
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

        /* Advanced Animations */
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease, transform 0.6s ease;
        }

        .fade-in.active {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>

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
        <div class="skill-category fade-in">
            <strong>Data Visualization:</strong><br>
            R Shiny, ggplot2, Power BI, Tableau
        </div>
        <div class="skill-category fade-in">
            <strong>Database Management:</strong><br>
            SQL, PostgreSQL, BigQuery
        </div>
        <div class="skill-category fade-in">
            <strong>Programming Tools:</strong><br>
            Python, R, Pandas, NumPy
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Featured Projects</h2>

        <!-- Project 1 -->
        <div class="project fade-in">
            <h3 class="project-title">Sales Trend Analysis</h3>
            <p class="project-description">
                Analyzed sales data using R and Python to identify trends and create interactive dashboards.
            </p>
            <a href="https://github.com/Moonwiing/report.1/blob/main/Kennedy%20Ithagu%20Maina_report.pdf" target="_blank">View Project (PDF)</a>
        </div>

        <!-- Project 2 -->
        <div class="project fade-in">
            <h3 class="project-title">Customer Segmentation</h3>
            <p class="project-description">
                Used R for clustering algorithms to segment customers for targeted marketing.
            </p>
            <a href="https://github.com/Moonwiing/report.1/blob/main/Kennedy%20Ithagu%20Maina_Visual.pdf" target="_blank">View Project (PDF)</a>
        </div>

        <!-- Project 3 -->
        <div class="project fade-in">
            <h3 class="project-title">Financial Forecasting</h3>
            <p class="project-description">
                Built time-series models in R to predict revenue and expenses.
            </p>
            <p><em>Coming Soon</em></p>
        </div>

        <!-- Project 4 -->
        <div class="project fade-in">
            <h3 class="project-title">Website Analytics</h3>
            <p class="project-description">
                Analyzed user behavior using R to improve website performance and engagement.
            </p>
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

    <!-- JavaScript for Animations -->
    <script>
        document.addEventListener("DOMContentLoaded", () => {
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add("active");
                    }
                });
            }, { threshold: 0.1 });

            document.querySelectorAll(".fade-in").forEach(el => {
                observer.observe(el);
            });
        });
    </script>

</body>
</html>
