<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Kennedy Maina's Data Analyst Portfolio">
    <title>Kennedy Maina | Data Analyst</title>
    <style>
        /* Global Styles */
        :root {
            --primary-color: #007BFF;
            --secondary-color: #ffffff; /* Default background (light) */
            --accent-color: #d1e0f7; /* Light accent */
            --text-color: #333; /* Dark text for light theme */
            --border-color: #ddd;
            --hover-color: #0056b3;
            --background-color: var(--secondary-color);
        }

        body.dark-theme {
            --primary-color: #007BFF;
            --secondary-color: #282C35; /* Dark background */
            --accent-color: #6495ED; /* Dark accent */
            --text-color: #eaeaea; /* Light text for dark theme */
            --border-color: #444;
            --background-color: #282C35;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, var(--primary-color), var(--accent-color));
            color: var(--text-color);
            text-align: center;
            padding: 2rem 1rem;
        }

        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            border: 4px solid var(--text-color);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            margin-bottom: 1rem;
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 1rem;
            padding: 1rem 0;
        }

        nav a {
            color: var(--text-color);
            text-decoration: none;
            padding: 0.5rem 1rem;
            border: 1px solid var(--text-color);
            border-radius: 5px;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        nav a:hover {
            background-color: var(--text-color);
            color: var(--primary-color);
        }

        section {
            padding: 2rem 1rem;
            max-width: 1200px;
            margin: 0 auto;
            background: var(--secondary-color);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
            border-radius: 8px;
            margin-bottom: 1.5rem;
        }

        h2 {
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }

        article {
            background: var(--secondary-color);
            padding: 1rem;
            border-radius: 8px;
            margin-bottom: 1rem;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        article:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.2);
        }

        a.button {
            display: inline-block;
            background: var(--primary-color);
            color: var(--secondary-color);
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        a.button:hover {
            background: var(--hover-color);
        }

        footer {
            text-align: center;
            padding: 1rem;
            background: var(--secondary-color);
            color: var(--text-color);
            margin-top: 2rem;
        }

        footer a {
            color: var(--primary-color);
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Theme Toggle Button */
        .theme-toggle {
            position: fixed;
            top: 1rem;
            right: 1rem;
            background: var(--secondary-color);
            color: var(--text-color);
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        .theme-toggle:hover {
            background: var(--primary-color);
            color: var(--secondary-color);
        }

        /* Modal Styles */
        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0, 0, 0, 0.8);
        }

        .modal-content {
            background: var(--secondary-color);
            margin: 10% auto;
            padding: 20px;
            border: 1px solid var(--border-color);
            width: 80%;
            max-width: 800px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }

        .close {
            color: var(--text-color);
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
        }

        .close:hover {
            color: var(--primary-color);
        }

        iframe {
            width: 100%;
            height: 600px;
            border: none;
        }
    </style>
</head>
<body>

    <!-- Theme Toggle Button -->
    <button class="theme-toggle" onclick="toggleTheme()">Toggle Theme</button>

    <!-- Header -->
    <header class="fade-in">
        <img src="https://via.placeholder.com/150" alt="Kennedy Maina Profile Picture">
        <h1>Kennedy Maina</h1>
        <p>Data Analyst | SQL | Python | R | Power BI</p>
        <nav>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Skills Section -->
    <section id="skills" class="fade-in">
        <h2>Skills</h2>

        <!-- Data Visualization -->
        <div class="skill-category">
            <h3>Data Visualization</h3>
            <div class="skills-box">
                <span class="skill-item">R Shiny</span>
                <span class="skill-item">ggplot2</span>
                <span class="skill-item">Power BI</span>
                <span class="skill-item">Tableau</span>
            </div>
        </div>

        <!-- Database Management -->
        <div class="skill-category">
            <h3>Database Management</h3>
            <div class="skills-box">
                <span class="skill-item">SQL</span>
                <span class="skill-item">PostgreSQL</span>
                <span class="skill-item">BigQuery</span>
            </div>
        </div>

        <!-- Tools -->
        <div class="skill-category">
            <h3>Tools</h3>
            <div class="skills-box">
                <span class="skill-item">Python</span>
                <span class="skill-item">R</span>
                <span class="skill-item">Pandas</span>
                <span class="skill-item">NumPy</span>
            </div>
        </div>
    </section>

    <!-- Featured Projects Section -->
    <section id="projects" class="fade-in">
        <h2>Featured Projects</h2>

        <article>
            <h3>Sales Trend Analysis</h3>
            <p>Analyzed sales data using R and Python to identify trends and create interactive dashboards.</p>
            <button onclick="openModal('sales-trend')">View Project</button>
        </article>

        <article>
            <h3>Customer Segmentation</h3>
            <p>Used R for clustering algorithms to segment customers for targeted marketing.</p>
            <button onclick="openModal('customer-segmentation')">View Project</button>
        </article>

        <article>
            <h3>Financial Forecasting</h3>
            <p>Built time-series models in R to predict revenue and expenses.</p>
            <a href="#" class="button">Coming Soon</a>
        </article>

        <article>
            <h3>Website Analytics</h3>
            <p>Analyzed user behavior using R to improve website performance and engagement.</p>
            <a href="#" class="button">Coming Soon</a>
        </article>
    </section>

    <!-- Modals -->
    <div id="sales-trend" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('sales-trend')">&times;</span>
            <h2>Sales Trend Analysis</h2>
            <iframe id="sales-trend-iframe"></iframe>
        </div>
    </div>

    <div id="customer-segmentation" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('customer-segmentation')">&times;</span>
            <h2>Customer Segmentation</h2>
            <iframe id="customer-segmentation-iframe"></iframe>
        </div>
    </div>

    <!-- Contact Section -->
    <section id="contact" class="fade-in">
        <h2>Contact Me</h2>
        <p>Feel free to reach out for collaborations or opportunities!</p>
        <p><a href="mailto:kennedymaina573@gmail.com">kennedymaina573@gmail.com</a></p>
        <p>+254 700 000 000</p>
    </section>

    <!-- Footer -->
    <footer class="fade-in">
        <p>&copy; 2023 Kennedy Maina. All rights reserved.</p>
    </footer>

    <!-- JavaScript for Theme Toggle and Modals -->
    <script>
        // Theme Toggle Functionality
        function toggleTheme() {
            const body = document.body;
            body.classList.toggle('dark-theme');
            const theme = body.classList.contains('dark-theme') ? 'dark' : 'light';
            localStorage.setItem('theme', theme);
        }

        // Load saved theme on page load
        const savedTheme = localStorage.getItem('theme');
        if (savedTheme === 'dark') {
            document.body.classList.add('dark-theme');
        }

        // Modal Functionality
        function openModal(id) {
            const modal = document.getElementById(id);
            modal.style.display = "block";

            // Dynamically load the PDF file
            const iframe = modal.querySelector("iframe");
            if (id === "sales-trend") {
                iframe.src = "https://github.com/Moonwiing/report.1/blob/main/Kennedy%20Ithagu%20Maina_Visual.pdf?raw=true";
            } else if (id === "customer-segmentation") {
                iframe.src = "https://github.com/Moonwiing/report.1/blob/main/Kennedy%20Ithagu%20Maina_report.pdf?raw=true";
            }
        }

        function closeModal(id) {
            const modal = document.getElementById(id);
            modal.style.display = "none";

            // Clear the iframe source when closing the modal
            const iframe = modal.querySelector("iframe");
            iframe.src = "";
        }

        // Close modals when clicking outside
        window.onclick = function (event) {
            if (event.target.classList.contains("modal")) {
                event.target.style.display = "none";
                const iframe = event.target.querySelector("iframe");
                iframe.src = "";
            }
        };
    </script>
</body>
</html>
