<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kennedy Maina - Data Analyst Portfolio</title>
  <!-- Bootstrap CSS for responsive design -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />
  <!-- AOS CSS for animations -->
  <link
    href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css"
    rel="stylesheet"
  />
  <style>
    /* General Styles */
    body {
      font-family: 'Arial', sans-serif;
      background: #f4f7fb;
      color: #333;
      margin: 0;
      padding: 0;
    }
    /* Header with stats-themed background */
    header {
      background: url('data-statistics-background.jpg') no-repeat center center/cover;
      color: white;
      padding: 100px 0;
      text-align: center;
      position: relative;
    }
    header h1 {
      font-size: 4rem;
      margin-bottom: 0.5rem;
    }
    header p {
      font-size: 1.5rem;
    }
    header .profile-img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #fff;
      margin-top: 20px;
    }
    /* Main Section Styling */
    section {
      padding: 60px 0;
      position: relative;
      z-index: 10;
    }
    .card-img-top {
      height: 200px;
      object-fit: cover;
    }
    .section-title {
      font-size: 2.5rem;
      margin-bottom: 30px;
    }
    .project-card {
      border: none;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      margin-bottom: 30px;
    }
    .project-card:hover {
      box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
    }
    .project-card .btn {
      background-color: #4CAF50;
      color: white;
    }
    .skills-icons img {
      max-width: 50px;
      margin: 10px;
      opacity: 0.8;
      transition: opacity 0.3s;
    }
    .skills-icons img:hover {
      opacity: 1;
    }
    /* Footer */
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 20px 0;
    }
    footer p {
      margin: 0;
    }
  </style>
</head>
<body>
  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top" data-aos="fade-down">
    <div class="container">
      <a class="navbar-brand" href="#">Kennedy Maina</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Header Section with Data-Driven Background -->
  <header data-aos="fade-up">
    <div class="container">
      <img src="kennedy-profile-pic.jpg" alt="Kennedy Maina" class="profile-img" />
      <h1>Kennedy Maina</h1>
      <p>Data Analyst | Problem Solver | Machine Learning Enthusiast</p>
    </div>
  </header>

  <!-- About Section -->
  <section id="about" data-aos="fade-up">
    <div class="container">
      <h2 class="section-title">About Me</h2>
      <p>
        Hello, I'm Kennedy Maina—a data analyst passionate about using statistical tools and data science techniques to derive insights and solve complex problems. 
        I have hands-on experience with tools like R, Python, SQL, and advanced Excel. I enjoy tackling challenges, turning raw data into meaningful predictions, and improving decision-making processes.
      </p>
    </div>
  </section>

  <!-- Skills Section with Icons -->
  <section id="skills" class="bg-light" data-aos="fade-up">
    <div class="container">
      <h2 class="section-title">Skills</h2>
      <div class="skills-icons">
        <img src="python-icon.png" alt="Python" title="Python"/>
        <img src="sql-icon.png" alt="SQL" title="SQL"/>
        <img src="r-icon.png" alt="R" title="R"/>
        <img src="tableau-icon.png" alt="Tableau" title="Tableau"/>
        <img src="excel-icon.png" alt="Excel" title="Excel"/>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" data-aos="fade-up">
    <div class="container">
      <h2 class="section-title">Projects</h2>
      <div class="row">
        <!-- Project 1 -->
        <div class="col-md-4">
          <div class="card project-card">
            <img src="project1-thumbnail.jpg" class="card-img-top" alt="Project One">
            <div class="card-body">
              <h5 class="card-title">Project One: Sales Forecasting</h5>
              <p class="card-text">
                Using Python and machine learning techniques to predict sales trends and optimize stock management.
              </p>
              <a href="https://github.com/kennedy/project-one" class="btn btn-primary" target="_blank">View Project</a>
            </div>
          </div>
        </div>
        <!-- Project 2 -->
        <div class="col-md-4">
          <div class="card project-card">
            <img src="project2-thumbnail.jpg" class="card-img-top" alt="Project Two">
            <div class="card-body">
              <h5 class="card-title">Project Two: Customer Segmentation</h5>
              <p class="card-text">
                Conducted clustering analysis to segment customers based on purchasing behavior.
              </p>
              <a href="https://github.com/kennedy/project-two" class="btn btn-primary" target="_blank">View Project</a>
            </div>
          </div>
        </div>
        <!-- Project 3 -->
        <div class="col-md-4">
          <div class="card project-card">
            <img src="project3-thumbnail.jpg" class="card-img-top" alt="Project Three">
            <div class="card-body">
              <h5 class="card-title">Project Three: Financial Data Analysis</h5>
              <p class="card-text">
                Used R to analyze financial data, model price predictions, and visualize trends for decision-making.
              </p>
              <a href="https://github.com/kennedy/project-three" class="btn btn-primary" target="_blank">View Project</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="bg-light" data-aos="fade-up">
    <div class="container">
      <h2 class="section-title">Contact Me</h2>
      <p>Email: <a href="mailto:kennedymaina573@gmail.com">datawing4@gmail.com</a></p>
      <p>Phone: +1 (123) 456-7890</p>
    </div>
  </section>

  <!-- Footer -->
  <footer data-aos="fade-up">
    <p>&copy; 2025 Kennedy Maina. All Rights Reserved.</p>
  </footer>

  <!-- JavaScript Libraries -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
  
  <script>
    // Initialize AOS animations
    AOS.init({
      duration: 1000,
      once: true,
    });
  </script>
</body>
</html>
