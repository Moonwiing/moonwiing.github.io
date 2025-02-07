<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kennedy Maina's Portfolio</title>
  <style>
    /* General Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background: #333;
      color: #fff;
      padding: 1rem 0;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }

    .logo {
      font-size: 1.5rem;
      font-weight: bold;
    }

    .nav-links {
      list-style: none;
      display: flex;
    }

    .nav-links li {
      margin-left: 20px;
    }

    .nav-links a {
      text-decoration: none;
      color: #fff;
      transition: color 0.3s;
    }

    .nav-links a:hover {
      color: #ff6347;
    }

    /* Hero Section */
    #hero {
      background: url('https://via.placeholder.com/1920x1080') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: #fff;
    }

    .hero-content h1 {
      font-size: 3rem;
    }

    .hero-content p {
      font-size: 1.5rem;
      margin-bottom: 20px;
    }

    .btn {
      background: #ff6347;
      color: #fff;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s;
    }

    .btn:hover {
      background: #e95a43;
    }

    /* Sections */
    .section {
      padding: 50px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }

    .skills-grid, .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .skill-card, .project-card {
      background: #fff;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      text-align: center;
    }

    .project-card img {
      max-width: 100%;
      height: auto;
      margin-bottom: 10px;
    }

    /* Contact Form */
    #contact-form input, #contact-form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    #contact-form button {
      background: #ff6347;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    #contact-form button:hover {
      background: #e95a43;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background: #333;
      color: #fff;
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <header>
    <nav>
      <div class="logo">Kennedy Maina</div>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="hero">
    <div class="hero-content">
      <h1>Hello, I'm Kennedy Maina</h1>
      <p>A Data Analyst with expertise in data visualization, statistical analysis, and machine learning.</p>
      <a href="#about" class="btn">Learn More</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="section">
    <h2>About Me</h2>
    <p>
      I am a passionate Data Analyst with experience in extracting insights from complex datasets.
      My work focuses on transforming raw data into actionable insights using tools like Python, SQL, and Tableau.
      I enjoy working on projects that involve predictive modeling, data cleaning, and visualization.
    </p>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="section">
    <h2>My Skills</h2>
    <div class="skills-grid">
      <div class="skill-card">
        <h3>Data Cleaning & Preparation</h3>
        <p>Pandas, NumPy, Excel</p>
      </div>
      <div class="skill-card">
        <h3>Data Visualization</h3>
        <p>Tableau, Matplotlib, Seaborn, Plotly</p>
      </div>
      <div class="skill-card">
        <h3>Statistical Analysis</h3>
        <p>R, Python (SciPy, StatsModels)</p>
      </div>
      <div class="skill-card">
        <h3>Database Management</h3>
        <p>SQL, PostgreSQL, MongoDB</p>
      </div>
      <div class="skill-card">
        <h3>Machine Learning</h3>
        <p>Scikit-learn, TensorFlow, Keras</p>
      </div>
      <div class="skill-card">
        <h3>Big Data Tools</h3>
        <p>Apache Spark, Hadoop</p>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="section">
    <h2>My Projects</h2>
    <div class="project-grid">
      <div class="project-card">
        <h3>Sales Forecasting</h3>
        <img src="https://via.placeholder.com/400x300" alt="Sales Forecasting">
        <p>
          Built a time-series forecasting model using ARIMA and Prophet to predict monthly sales for an e-commerce company.
        </p>
        <a href="#" target="_blank">View Project</a>
      </div>
      <div class="project-card">
        <h3>Customer Segmentation</h3>
        <img src="https://via.placeholder.com/400x300" alt="Customer Segmentation">
        <p>
          Performed customer segmentation using K-Means clustering to identify distinct groups of customers based on purchasing behavior.
        </p>
        <a href="#" target="_blank">View Project</a>
      </div>
      <div class="project-card">
        <h3>Churn Prediction</h3>
        <img src="https://via.placeholder.com/400x300" alt="Churn Prediction">
        <p>
          Developed a churn prediction model using logistic regression and random forests to identify customers likely to leave.
        </p>
        <a href="#" target="_blank">View Project</a>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section">
    <h2>Contact Me</h2>
    <form id="contact-form">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2023 Kennedy Maina. All rights reserved.</p>
  </footer>

  <script>
    // Example: Handle form submission
    document.getElementById('contact-form').addEventListener('submit', function (event) {
      event.preventDefault();
      alert('Thank you for your message! I will get back to you soon.');
    });
  </script>
</body>
</html>
