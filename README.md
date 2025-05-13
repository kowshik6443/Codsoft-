# Codsoft-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Job Board</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f9;
      color: #333;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav ul {
      list-style-type: none;
      padding: 0;
    }
    nav ul li {
      display: inline;
      margin: 0 15px;
    }
    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-size: 18px;
    }
    .container {
      padding: 20px;
    }
    .job-listing {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      margin-bottom: 20px;
      padding: 20px;
      display: flex;
      justify-content: space-between;
    }
    .job-listing h3 {
      margin-bottom: 10px;
    }
    .job-listing p {
      color: #777;
      font-size: 14px;
    }
    .job-listing .apply-btn {
      background-color: #28a745;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      text-decoration: none;
    }
    .job-listing .apply-btn:hover {
      background-color: #218838;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Welcome to the Job Board</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Job Listings</a></li>
      <li><a href="#">Post a Job</a></li>
      <li><a href="#">Login</a></li>
      <li><a href="#">Sign Up</a></li>
    </ul>
  </nav>
</header>

<div class="container">
  <h2>Featured Job Listings</h2>
  
  <!-- Job Listing 1 -->
  <div class="job-listing">
    <div>
      <h3>Frontend Developer</h3>
      <p>Location: Remote</p>
      <p>Company: TechCorp</p>
      <p>Experience: 2+ years</p>
    </div>
    <a href="#" class="apply-btn">Apply Now</a>
  </div>

  <!-- Job Listing 2 -->
  <div class="job-listing">
    <div>
      <h3>Backend Developer</h3>
      <p>Location: On-site, San Francisco</p>
      <p>Company: CodeWorks</p>
      <p>Experience: 3+ years</p>
    </div>
    <a href="#" class="apply-btn">Apply Now</a>
  </div>

  <!-- Job Listing 3 -->
  <div class="job-listing">
    <div>
      <h3>Product Manager</h3>
      <p>Location: Hybrid, New York</p>
      <p>Company: InnovateX</p>
      <p>Experience: 5+ years</p>
    </div>
    <a href="#" class="apply-btn">Apply Now</a>
  </div>
</div>

<footer>
  <p>&copy; 2025 Job Board | All Rights Reserved</p>
</footer>

</body>
</html>
