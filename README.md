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
  <!-- Inline CSS -->
  <style>
    :root {
      --primary-color: #4CAF50;
      --secondary-color: #2196F3;
      --accent-color: #FFC107;
      --warning-color: #FF5722;
      --purple-color: #9C27B0;
    }
    body {
      font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }
    /* Navigation */
    .navbar-brand {
      font-weight: bold;
    }
    /* Header Section */
    header.header-section {
      background: url('header-background.jpg') no-repeat center center/cover;
      padding: 150px 0;
      color: #fff;
      text-align: center;
      position: relative;
    }
    .profile-img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border: 4px solid #fff;
    }
    /* Sections */
    section {
      padding: 60px 0;
    }
    html {
      scroll-behavior: smooth;
    }
    .card-img-top {
      height: 200px;
      object-fit: cover;
    }
    /* Footer */
    footer {
      background-color: #343a40;
      color: #fff;
      padding: 20px 0;
      text-align: center;
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
          <li class="nav-item"><a class="nav-link" href="#about">About Me</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Header Section -->
  <header class="header-section" data-aos="fade-up">
    <div class="container">
      <img src="your-profile-image.jpg" alt="Kennedy Maina" class="profile-img rounded-circle" data-aos="zoom-in" data-aos-delay="200">
      <h1 class="mt-3">Kennedy Maina</h1>
      <p class="lead">Data Analyst | Data Enthusiast | Problem Solver</p>
    </div>
  </header>

  <!-- About Section -->
  <section id="about" data-aos="fade-up">
    <div class="container">
      <h2 class="mb-4">About Me</h2>
      <p>
        Hello, I'm Kennedy Maina—a passionate data analyst dedicated to turning raw data into actionable insights.
        With a strong background in statistical analysis, data visualization, and predictive modeling, I help
        businesses make informed, data-driven decisions.
      </p>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="bg-light" data-aos="fade-up">
    <div class="container">
      <h2 class="mb-4">My Skills</h2>
      <canvas id="skillsChart" width="400" height="200"></canvas>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" data-aos="fade-up">
    <div class="container">
      <h2 class="mb-4">Projects</h2>
      <div class="row">
        <!-- Project 1 -->
        <div class="col-md-4" data-aos="zoom-in" data-aos-delay="100">
          <div class="card mb-4 shadow-sm">
            <img src="project1-thumbnail.jpg" class="card-img-top" alt="Project One">
            <div class="card-body">
              <h5 class="card-title">Project One</h5>
              <p class="card-text">
                A comprehensive analysis exploring trends in the finance industry.
              </p>
              <a href="https://github.com/yourusername/project-one" class="btn btn-primary" target="_blank">View Project</a>
            </div>
          </div>
        </div>
        <!-- Project 2 -->
        <div class="col-md-4" data-aos="zoom-in" data-aos-delay="200">
          <div class="card mb-4 shadow-sm">
            <img src="project2-thumbnail.jpg" class="card-img-top" alt="Project Two">
            <div class="card-body">
              <h5 class="card-title">Project Two</h5>
              <p class="card-text">
                Data exploration and visualization of customer behavior patterns.
              </p>
              <a href="https://github.com/yourusername/project-two" class="btn btn-primary" target="_blank">View Project</a>
            </div>
          </div>
        </div>
        <!-- Project 3 -->
        <div class="col-md-4" data-aos="zoom-in" data-aos-delay="300">
          <div class="card mb-4 shadow-sm">
            <img src="project3-thumbnail.jpg" class="card-img-top" alt="Project Three">
            <div class="card-body">
              <h5 class="card-title">Project Three</h5>
              <p class="card-text">
                A dynamic dashboard for monitoring key performance indicators.
              </p>
              <a href="https://github.com/yourusername/project-three" class="btn btn-primary" target="_blank">View Project</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="bg-light" data-aos="fade-up">
    <div class="container">
      <h2 class="mb-4">Contact Me</h2>
      <p>Email: <a href="mailto:datawing4@gmail.com">datawing4@gmail.com</a></p>
      <p>Phone: +1 (123) 456-7890</p>
      <!-- The "Send Message" contact form has been removed as requested -->
    </div>
  </section>

  <!-- Footer -->
  <footer data-aos="fade-up">
    <div class="container">
      <p class="mb-0">© 2025 Kennedy Maina. All Rights Reserved.</p>
    </div>
  </footer>

  <!-- JavaScript: Bootstrap, AOS, Chart.js -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <!-- Inline JavaScript -->
  <script>
    // Initialize AOS for smooth animations
    AOS.init({
      duration: 1000,
      once: true,
    });

    // Initialize the skills chart when the document is fully loaded
    document.addEventListener("DOMContentLoaded", function () {
      const ctx = document.getElementById("skillsChart").getContext("2d");
      new Chart(ctx, {
        type: "bar",
        data: {
          labels: ["Python", "SQL", "Excel", "Tableau", "R"],
          datasets: [{
            label: "Skill Proficiency (%)",
            data: [90, 85, 80, 75, 70],
            backgroundColor: [
              getComputedStyle(document.documentElement).getPropertyValue('--primary-color'),
              getComputedStyle(document.documentElement).getPropertyValue('--secondary-color'),
              getComputedStyle(document.documentElement).getPropertyValue('--accent-color'),
              getComputedStyle(document.documentElement).getPropertyValue('--warning-color'),
              getComputedStyle(document.documentElement).getPropertyValue('--purple-color')
            ]
          }]
        },
        options: {
          scales: {
            y: {
              beginAtZero: true,
              max: 100
            }
          }
        }
      });
    });
  </script>
</body>
</html>
