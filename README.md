# Project Responsive Web Design using Bootstrap
## Date:

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
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Travel Booking</title>

    
    <link 
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" 
      rel="stylesheet">
</head>

<body>


<nav class="navbar navbar-expand-lg bg-primary navbar-dark">
  <div class="container">
    <a class="navbar-brand fw-bold" href="#">RA HOLIDAYS</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="nav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#">Destinations</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Bookings</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Offers</a></li>
        <li class="nav-item"><a class="btn btn-light ms-3" href="#">Login</a></li>
      </ul>
    </div>
  </div>
</nav>


<section class="text-center text-light d-flex align-items-center" 
         style="background-image:url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e'); 
                background-size:cover; background-position:center; height:60vh;">
  <div class="container">
    <h1 class="fw-bold">Explore The World With TravelGo</h1>
    <p class="lead mt-3">Book flights, hotels and tours at unbeatable prices.</p>
    <a class="btn btn-warning btn-lg mt-3">Book Now</a>
  </div>
</section>


<section class="py-5">
  <div class="container">
    <h2 class="fw-bold text-center mb-4">Popular Destinations</h2>

    <div class="row g-4">
      
      <div class="col-md-4">
        <div class="card shadow-sm">
          <img src="https://images.unsplash.com/photo-1505761671935-60b3a7427bad" 
               class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Paris, France</h5>
            <p class="card-text">The city of love and lights. Perfect for holidays.</p>
            <a href="#" class="btn btn-primary">Book Trip</a>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card shadow-sm">
          <img src="https://images.unsplash.com/photo-1505765050514-f253f14a1fc8" 
               class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Bali, Indonesia</h5>
            <p class="card-text">Relax on beautiful beaches surrounded by nature.</p>
            <a href="#" class="btn btn-primary">Book Trip</a>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card shadow-sm">
          <img src="https://images.unsplash.com/photo-1473959383417-1f72cb0b0d48" 
               class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Dubai, UAE</h5>
            <p class="card-text">Experience luxury, skyscrapers and desert adventures.</p>
            <a href="#" class="btn btn-primary">Book Trip</a>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>


<section class="bg-light py-5">
  <div class="container">
    <h2 class="fw-bold text-center mb-4">Why Choose RA HOLIDAYS?</h2>

    <div class="row text-center">

      <div class="col-md-4">
        <h4>✔ Best Prices</h4>
        <p>We offer cheap and competitive travel packages worldwide.</p>
      </div>

      <div class="col-md-4">
        <h4>✔ Easy Booking</h4>
        <p>Fast and secure booking process with instant confirmations.</p>
      </div>

      <div class="col-md-4">
        <h4>✔ 24/7 Support</h4>
        <p>We are here anytime to help you with your travel needs.</p>
      </div>

    </div>
  </div>
</section>


<footer class="bg-dark text-light py-4 text-center">
  <p class="mb-1">TravelGo © 2025</p>
  <p class="mb-1">CEO: <strong>Ranjith</strong></p>
  <p class="mb-0">GM: <strong>Abirami</strong></p>
</footer>


<script 
  src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js">
</script>

</body>
</html>
```


## OUTPUT:
<img width="1919" height="1030" alt="Screenshot 2025-11-21 092912" src="https://github.com/user-attachments/assets/54f00577-8ec4-448c-ba0f-d7fc7cd1197a" />
<img width="1918" height="1036" alt="Screenshot 2025-11-21 092938" src="https://github.com/user-attachments/assets/f427f424-5d84-4dea-a968-28117b9b85c4" />


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
