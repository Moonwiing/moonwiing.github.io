<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kennedy Maina | Data Analyst</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    /* Global Styles */
    body {
      font-family: 'Open Sans', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f6f8;
      color: #333;
      line-height: 1.6;
    }
    
    /* Header */
    header {
      background: linear-gradient(135deg, #6a11cb, #2575fc);
      color: #fff;
      text-align: center;
      padding: 40px 20px;
    }
    
    header h1 {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      font-size: 2.8rem;
    }
    
    header p {
      margin: 10px 0 0;
      font-size: 1.1rem;
    }
    
    .profile-picture {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin: 20px auto;
      border: 5px solid #fff;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    
    /* Navigation */
    nav {
      background: #fff;
      border-bottom: 1px solid #eaeaea;
      display: flex;
      justify-content: center;
      padding: 15px 0;
    }
    
    nav a {
      color: #333;
      text-decoration: none;
      margin: 0 20px;
      font-weight: 600;
      transition: color 0.3s ease, transform 0.3s ease;
    }
    
    nav a:hover {
      color: #2575fc;
      transform: translateY(-3px);
    }
    
    /* Section */
    section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }
    
    section h2 {
      font-family: 'Montserrat', sans-serif;
      font-size: 2.2rem;
      color: #2575fc;
      margin-bottom: 20px;
      border-bottom: 2px solid #eaeaea;
      display: inline-block;
      padding-bottom: 5px;
    }
    
    /* Content Elements */
    ul {
      list-style: none;
      padding: 0;
    }
    
    li {
      margin-bottom: 15px;
    }
    
    a {
      color: #2575fc;
      text-decoration: none;
      transition: color 0.3s ease;
    }
    
    a:hover {
      color: #6a11cb;
    }
    
    /* Boxes for Projects & General Content */
    .box, .project-box {
      background: #fff;
      border: 1px solid #eaeaea;
      border-radius: 8px;
      padding: 25px;
      margin-bottom: 30px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    
    .box:hover, .project-box:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
    }
    
    .project-box h3 {
      margin-top: 0;
      color: #2575fc;
      font-family: 'Montserrat', sans-serif;
    }
    
    .project-box p {
      color: #555;
    }
    
    /* Skill Boxes */
    .skill-category {
      margin-bottom: 30px;
    }
    
    .skill-category h3 {
      font-family: 'Montserrat', sans-serif;
      font-size: 1.8rem;
      color: #333;
      margin-bottom: 15px;
    }
    
    .skill-box {
      display: inline-block;
      background: #fff;
      border: 1px solid #eaeaea;
      border-radius: 5px;
      padding: 10px 20px;
      margin: 5px;
      font-size: 0.95rem;
      color: #555;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    
    .skill-box:hover {
      transform: translateY(-3px);
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    
    /* Footer */
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 30px 20px;
      margin-top: 40px;
    }
    
    footer p {
      margin: 0;
      font-size: 0.9rem;
    }
    
    /* Responsive Styles */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }
      
      .profile-picture {
        width: 120px;
        height: 120px;
      }
      
      section {
        padding: 40px 15px;
      }
      
      nav a {
        margin: 0 10px;
      }
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

    <!-- Data Visualization -->
    <div class="skill-category">
      <h3>Data Visualization</h3>
      <div>
        <span class="skill-box">R Shiny</span>
        <span class="skill-box">ggplot2</span>
        <span class="skill-box">Power BI</span>
        <span class="skill-box">Tableau</span>
      </div>
    </div>

    <!-- Database Management -->
    <div class="skill-category">
      <h3>Database Management</h3>
      <div>
        <span class="skill-box">SQL</span>
        <span class="skill-box">PostgreSQL</span>
        <span class="skill-box">BigQuery</span>
      </div>
    </div>

    <!-- Programming Tools -->
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
</body>
</html>
