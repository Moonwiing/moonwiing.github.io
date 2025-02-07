<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kennedy Maina | Data Analyst</title>
    <meta name="description" content="Data Analyst specializing in SQL, Python, and Data Visualization with expertise in transforming raw data into actionable insights">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <style>
        :root {
            --primary: #2A5C82;
            --secondary: #34ADAD;
            --accent: #FF6B6B;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            line-height: 1.6;
            background: #f9f9f9;
        }

        .hero {
            text-align: center;
            padding: 6rem 2rem;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            color: white;
            clip-path: polygon(0 0, 100% 0, 100% 90%, 0 100%);
        }

        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            border: 5px solid white;
            margin: 1rem auto;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            padding: 4rem 2rem;
        }

        .skill-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
            text-align: center;
        }

        .skill-card:hover {
            transform: translateY(-10px);
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }

        .project-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            position: relative;
        }

        .project-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .project-info {
            padding: 1.5rem;
        }

        .contact {
            padding: 4rem 2rem;
            background: var(--primary);
            color: white;
            text-align: center;
        }

        form {
            max-width: 600px;
            margin: 2rem auto;
        }

        input, textarea {
            width: 100%;
            padding: 1rem;
            margin: 0.5rem 0;
            border: none;
            border-radius: 5px;
        }

        button {
            background: var(--accent);
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }

        button:hover {
            background: #ff5252;
        }

        @media (max-width: 768px) {
            .hero {
                padding: 4rem 1rem;
            }
        }
    </style>
</head>
<body>
    <header class="hero">
        <img src="assets/your-photo.jpg" alt="Kennedy Maina" class="profile-img">
        <h1>Kennedy Maina</h1>
        <p>Data Analyst | SQL | Python | Power BI</p>
        <div style="margin: 1.5rem 0;">
            <a href="https://linkedin.com/in/yourprofile" target="_blank" style="color: white; margin: 0 1rem;"><i class="fab fa-linkedin fa-2x"></i></a>
            <a href="https://github.com/yourprofile" target="_blank" style="color: white; margin: 0 1rem;"><i class="fab fa-github fa-2x"></i></a>
            <a href="resume.pdf" download style="color: white; margin: 0 1rem;"><i class="fas fa-file-pdf fa-2x"></i></a>
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
                <img src="project1.jpg" alt="Sales Analysis">
                <div class="project-info">
                    <h3>Sales Trend Analysis</h3>
                    <p>Created interactive dashboards showing regional sales performance</p>
                    <button style="margin-top: 1rem;">View Project</button>
                </div>
            </div>
            <!-- Add more project cards -->
        </div>
    </section>

    <section class="contact">
        <h2>Let's Connect</h2>
        <form onsubmit="handleSubmit(event)">
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Send Message <i class="fas fa-paper-plane"></i></button>
        </form>
    </section>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        // Initialize animations
        AOS.init({
            duration: 1000,
            once: true
        });

        // Form handling
        function handleSubmit(e) {
            e.preventDefault();
            alert('Message sent successfully!');
            e.target.reset();
        }

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
