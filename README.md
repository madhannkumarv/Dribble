# Project Responsive Web Design using Bootstrap
## Date:
24/12/2024
## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Pacifico&display=swap" rel="stylesheet">
  <title>Homepage</title>
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(to bottom, #ffffff, #f0f8ff);
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #057ff9;
      box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    }
    header a {
      font-weight: 700;
      font-size: 18px;
    }
    .announcement {
      background-color: #6c757d;
      color: white;
      font-weight: 700;
    }
    .announcement button {
      font-weight: bold;
    }
    h5 {
      font-family: 'Pacifico', cursive;
      text-align: center;
      color: #343a40;
    }
    .card img {
      border-radius: 15px;
      transition: transform 0.3s ease;
    }
    .card img:hover {
      transform: scale(1.05);
    }
    .card a {
      color: #343a40;
      font-weight: bold;
      text-decoration: none;
    }
    .card a:hover {
      text-decoration: underline;
    }
    footer {
      background-color: #343a40;
      color: white;
      text-align: center;
      padding: 10px 0;
      font-weight: bold;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <div class="container-fluid py-3">
      <div class="row align-items-center">
        <div class="col-md-6 d-flex">
          <a href="#" class="ms-3 text-white text-decoration-none">Home</a>
          <a href="#" class="ms-3 text-white text-decoration-none">Designers</a>
          <a href="#" class="ms-3 text-white text-decoration-none">Jobs</a>
          <a href="#" class="ms-3 text-white text-decoration-none">Teams</a>
          <a href="#" class="ms-3 text-white text-decoration-none">Collaboration</a>
        </div>
        <div class="col-md-6 d-flex justify-content-end">
          <button class="btn btn-info text-white me-2">Sign up</button>
          <button class="btn btn-info text-white me-2">Sign in</button>
          <input type="search" class="form-control w-50" placeholder="Search">
        </div>
      </div>
    </div>
  </header>

  <!-- Announcement -->
  <div class="text-center announcement py-3">
    <span>To see what's new</span>
    <button class="btn btn-dark ms-2">Learn more</button>
    <button class="btn btn-warning ms-2">Sign up</button>
  </div>

  <!-- Main Content -->
  <main class="container my-4">
    <h5><i>LIONS</i></h5>
    <div class="row g-4 text-center">
      <!-- Image Row 1 -->
      <div class="col-sm-3">
        <div class="card border-0">
          <img src="1.jpg" class="img-fluid" alt="Lion 1">
          <a href="#" class="mt-2 d-block">Barbary lion </a>
        </div>
      </div>
      <div class="col-sm-3">
        <div class="card border-0">
          <img src="2.jpg" class="img-fluid" alt="Lion 2">
          <a href="#" class="mt-2 d-block">Transvaal lion</a>
        </div>
      </div>
      <div class="col-sm-3">
        <div class="card border-0">
          <img src="3.jpg" class="img-fluid" alt="Lion 3">
          <a href="#" class="mt-2 d-block">Cape lion</a>
        </div>
      </div>
      <div class="col-sm-3">
        <div class="card border-0">
          <img src="4.jpg" class="img-fluid" alt="Lion 4">
          <a href="#" class="mt-2 d-block">Congo lion</a>
        </div>
      </div>
    </div>
    <div class="row g-4 text-center mt-4">
      <!-- Image Row 2 -->
      <div class="col-sm-3">
        <div class="card border-0">
          <img src="5.jpg" class="img-fluid" alt="Lion 5">
          <a href="#" class="mt-2 d-block">Asiatic lion</a>
        </div>
      </div>
      <div class="col-sm-3">
        <div class="card border-0">
          <img src="6.jpg" class="img-fluid" alt="Lion 6">
          <a href="#" class="mt-2 d-block">European lion</a>
        </div>
      </div>
      <div class="col-sm-3">
        <div class="card border-0">
          <img src="7.jpg" class="img-fluid" alt="Lion 7">
          <a href="#" class="mt-2 d-block">Southwest African lion</a>
        </div>
      </div>
      <div class="col-sm-3">
        <div class="card border-0">
          <img src="8.jpg" class="img-fluid" alt="Lion 8">
          <a href="#" class="mt-2 d-block">Panthera leo fossilis Animal</a>
        </div>
      </div>
    </div>
  </main>

  <!-- Footer -->
  <footer>
    MADHANN KUMAR (24010027)
  </footer>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (59).png>)
![alt text](<Screenshot (60).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
