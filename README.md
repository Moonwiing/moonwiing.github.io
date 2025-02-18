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
            --secondary-color: #ffffff; /* Light background */
            --accent-color: #d1e0f7; /* Soft blue accent */
            --text-color: #333; /* Dark text */
            --border-color: #ddd;
            --hover-color: #0056b3;
            --background-color: var(--secondary-color);
        }

        body.dark-theme {
            --primary-color: #007BFF;
            --secondary-color: #1E1E1E; /* Darker background */
            --accent-color: #282C35; /* Dark gray accent */
            --text-color: #eaeaea; /* Light text */
            --border-color: #444;
            --hover-color: #0056b3;
            --background-color: #121212; /* Darkest background */
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        header {
            background: linear-gradient(135deg, var(--primary-color), var(--accent-color));
            color: var(--text-color);
            text-align: center;
            padding: 2rem 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            border: 4px solid var(--text-color);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            margin-bottom: 1rem;
            transition: transform 0.3s ease;
        }

        header img:hover {
            transform: scale(1.05);
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
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            margin-bottom: 1.5rem;
            transition: box-shadow 0.3s ease;
        }

        section:hover {
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.2);
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
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .theme-toggle:hover {
            background: var(--primary-color);
            color: var(--secondary-color);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }

        /* Skill Boxes */
        .skill-category {
            display: flex;
            flex-direction: column;
            background: linear-gradient(135deg, var(--accent-color), var(--secondary-color));
            padding: 1rem;
            border-radius: 8px;
            margin-bottom: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: box-shadow 0.3s ease;
        }

        .skill-category:hover {
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.2);
        }

        .skills-box {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 0.5rem;
        }

        .skill-item {
            background: var(--secondary-color);
            color: var(--text-color);
            padding: 0.5rem 1rem;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s ease, transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .skill-item:hover {
            background: var(--primary-color);
            transform: scale(1.05);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
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
            background: linear-gradient(135deg, var(--secondary-color), var(--accent-color));
            margin: 10% auto;
            padding: 20px;
            border: 1px solid var(--border-color);
            width: 80%;
            max-width: 800px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
            transition: box-shadow 0.3s ease;
        }

        .modal-content:hover {
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.3);
        }

        .close {
            color: var(--text-color);
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        .close:hover {
            color: var(--primary-color);
        }

        iframe {
            width: 100%;
            height: 600px;
            border: none;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background: linear-gradient(135deg, var(--secondary-color), var(--accent-color));
            color: var(--text-color);
            margin-top: 2rem;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
        }

        footer a {
            color: var(--primary-color);
            text-decoration: none;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: var(--hover-color);
        }
    </style>
</head>
<body>

    <!-- Theme Toggle Button -->
    <button class="theme-toggle" onclick="toggleTheme()">Toggle Theme</button>

    <!-- Header -->
    <header class="fade-in">
        <img src="https://via.placeholder.com/150" alt="Kennedy Maina Profile Picture">
        <h1>Kennedy Maina - Data Analyst</h1>
        <p>Exploring the world of data through analysis, insights, and actionable solutions.</p>
    </header>

    <!-- Portfolio Section -->
    <section>
        <h2>My Work</h2>
        <article>
            <h3>Project Report PDF</h3>
            <p>Click below to view my detailed report on various data analysis techniques and applications:</p>
            <a href="https://raw.githubusercontent.com/Moonwiing/report.1/main/Kennedy%20Ithagu%20Maina_report.pdf" target="_blank">View Full Report PDF</a>
        </article>

        <article>
            <h3>Visual Analysis PDF</h3>
            <p>Click below to view my data visualizations and insights:</p>
            <a href="https://raw.githubusercontent.com/Moonwiing/report.1/main/Kennedy%20Ithagu%20Maina_Visual.pdf" target="_blank">View Visual Analysis PDF</a>
        </article>
    </section>

    <!-- Footer -->
    <footer>
        <p>Contact me: <a href="mailto:kennedy.maina@example.com">kennedy.maina@example.com</a></p>
    </footer>

</body>
</html>
