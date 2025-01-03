# Ex.08 Design of Interactive Image Gallery
## Date:

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Homepage</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-warning">

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">SUDARSAN</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Designs</a></li>
          <li class="nav-item"><a class="nav-link" href="#">animes</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Team up!</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Collaboration</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="text-center py-5 bg-primary text-white">
    <h1>Welcome to Our site</h1>
    <p>Explore designs, anime recommendations, and more!</p>
    <a href="#" class="btn btn-warning">Get Started</a>
  </header>

  <!-- Main Content -->
  <div class="container py-5">
    <div class="row text-center">
      <div class="col-12">
        <h2>Featured Anime</h2>
      </div>
      <div class="col-md-4">
        <img src="images (4).jpeg" class="img-fluid" alt="Designer 1">
        <p>TALA</p>
      </div>
      <div class="col-md-4">
        <img src="16aeec16629cabe6728a06b84a523a32.jpg" class="img-fluid" alt="Designer 2">
        <p>KAI</p>
      </div>
      <div class="col-md-4">
        <img src="1062251-y1pynu_1dao16kntyrepx_s_tedturp38wk.jpg" class="img-fluid" alt="Designer 3">
        <p>TYSON</p>
      </div>
      <div class="col-md-4">
        <img src="images (1).jpeg" class="img-fluid" alt="Designer 4">
        <p>RAY</p>
      </div>
      <div class="col-md-4">
        <img src="images (2).jpeg" class="img-fluid" alt="Designer 4">
        <p>MAX</p>
      </div>
      <div class="col-md-4">
        <img src="images (3).jpeg" class="img-fluid" alt="Designer 4">
        <p>BROOKLYN</p>
      </div> 
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4">
    <p>&copy; DESIGNED AND DEVELOPED BY SUDARSAN.A All rights reserved.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2024-12-25 110447.png>)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
