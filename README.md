# Project Responsive Web Design using Bootstrap
## Date:13-11-2024

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
    <title>NVIDIA</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <style>
        /* Adding some basic styling for the hero section */
        .hero {
        background-image: radial-gradient(circle at center, #4a4a4a, #333);
        background-size: cover;
        background-position: center;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        text-align: center;
        padding: 20px;
    }
        
        /* Custom footer styling */
        .footer {
            background-image: radial-gradient( #575656, #ffffff);
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .hover-pop {
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .hover-pop:hover {
        transform: scale(1.05); /* Slightly enlarges the card */
        box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15); /* Adds a subtle shadow */
    }
    </style>
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#"><strong><pre style="color: rgb(16, 173, 18);">DRIBBLE</pre></strong></a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
                <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Features</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">About</a>
            </li>
        </ul>
    </div>
</nav>

<!-- Hero Section -->
<section class="hero">
    <div class="container">
        <h1 class="display-3">Welcome to DRIBBLE</h1>
        <p class="lead">This is a revolutionary Institute created in collaboration with <strong style="color: rgb(60, 193, 19);">LONDON COLLEGE OF FASHION</strong></p>
        <hr class="my-4" style="border-color: rgba(255, 255, 255, 0.6);">
        <p>We believe in using the subject of fashion, together with its industrial importance, to shape lives and drive economic and social transformation.</p>
        <a class="btn btn-primary btn-lg" href="#" role="button" style="background-color: rgb(60, 193, 19); border: none;">Learn More</a>
    </div>
</section>

<!-- Features Section -->
<section class="py-5">
    <div class="container">
        <h2 class="mb-4">University of Arts London</h2>
        <div class="row">
            <!-- Each card will take full width on small screens, half width on medium screens, and one-third on large screens -->
            <div class="col-12 col-md-6 col-lg-4 mb-4">
                <div class="card h-100 hover-pop">
                    <div class="card-body">
                        <h5 class="card-title">Research at LCF</h5>
                        <p class="card-text">"Politan" represents concepts of city, citizenship, or a collective body of people—terms that resonate with many, particularly those who identify with more than one place, culture, or orientation. It also conveys the idea of being 'at home' anywhere in the world, an ideology that celebrates the mixed heritage and diverse experiences familiar to many within the Black diaspora.</p>
                        <img src="https://ual-media-res.cloudinary.com/image/fetch/c_fill,f_auto,g_auto,q_auto/https://portfolio-tools.s3.eu-west-2.amazonaws.com/wp-content/uploads/2024/06/02224201/showcase-7.jpg" alt="PAGE" style="height: auto; width: 100%;" class="mb-3">
                        <a href="#" class="btn btn-outline-primary">Go There</a>
                    </div>
                </div>
            </div>
            
            <div class="col-12 col-md-6 col-lg-4 mb-4">
                <div class="card h-100 hover-pop">
                    <div class="card-body">
                        <h5 class="card-title">Business and Innovation</h5>
                        <p class="card-text">The selected collections embody an innovative perspective, offering insights into the places, cultures, and experiences that have shaped individual upbringings and influenced their creative expression. Some reflect on the past, while others present forward-looking ideas, all highly relevant and forward-thinking within a global, inclusive context.</p>
                        <img src="https://ual-media-res.cloudinary.com/image/fetch/c_fill,f_auto,fl_lossy,g_auto,q_auto/https://portfolio-tools.s3.eu-west-2.amazonaws.com/wp-content/uploads/2024/04/20120910/Bildschirmfoto-2024-04-20-um-1.08.16-PM.png" alt="PAGE" style="height: auto; width: 100%;" class="mb-3">
                        <a href="#" class="btn btn-outline-primary" role="button">Go There</a>
                    </div>
                </div>
            </div>
            
            <div class="col-12 col-md-6 col-lg-4 mb-4">
                <div class="card h-100 hover-pop">
                    <div class="card-body">
                        <h5 class="card-title">LCF Global</h5>
                        <p class="card-text">Consequently, these visionary works transform how we see the world, offering a diverse and thought-provoking lens on the future—a future that embraces the 'Politan' mindset of openness and global understanding.</p>
                        <img src="https://ual-media-res.cloudinary.com/image/fetch/c_fill,f_auto,fl_lossy,g_auto,q_auto/https://portfolio-tools.s3.eu-west-2.amazonaws.com/wp-content/uploads/2024/02/13203335/D5D2EB0B-9DEE-4C27-9BC7-17ABC25C982C.jpeg" alt="PAGE" style="height: auto; width: 100%;" class="mb-3">
                        <a href="#" class="btn btn-outline-primary">Go There</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
```

## OUTPUT:
<img width="1680" alt="Dribble_1" src="https://github.com/user-attachments/assets/fc2fa9e4-2ce0-4f9e-8a3d-d6024768655f">

<img width="1680" alt="Dribble_2" src="https://github.com/user-attachments/assets/6c43db61-f60c-40f3-9d1d-cd5ca0582252">

<img width="1680" alt="Dribble_3" src="https://github.com/user-attachments/assets/13fce5cc-4b09-4718-a9df-bdc9e985538a">


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
