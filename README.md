# Project Responsive Web Design using Bootstrap
## Date:03-01-2025

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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DRIBBLE</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0482ff;
        }
        .navbar-brand {
            font-weight: bold;
        }
        .portfolio-item {
            overflow: hidden;
            position: relative;
        }
        .portfolio-item img {
            transition: transform 0.3s ease;
        }
        .portfolio-item:hover img {
            transform: scale(1.1);
        }
        .portfolio-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.6);
            display: flex;
            align-items: center;
            justify-content: center;
            color: #f00707;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        .portfolio-item:hover .portfolio-overlay {
            opacity: 1;
        }
    </style>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-light bg-light shadow">
    <div class="container">
        <a class="navbar-brand" href="#">DRIBBLE</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Portfolio</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<header class="py-5 bg-primary text-white text-center">
    <div class="container">
        <h1>Welcome to DRIBBLE</h1>
        <p class="lead">Showcasing creative porfolio</p>
    </div>
</header>

<section class="py-5">
    <div class="container">
        <div class="row">
            <div class="col-lg-4 col-md-6 mb-4">
                <div class="portfolio-item">
                    <img src="c:\Users\admin\Pictures\original-79c28b4f9f64f091b8c5c3fb6e66cb60.png" alt="Portfolio Item" class="img-fluid rounded">
                    <div class="portfolio-overlay">
                        <h4>KIRA PROJECT</h4>
                        <p>CodeAuto is a sleek and innovative dashboard that empowers users to design and implement powerful workflows
                             without writing a single line of code. Tailored for businesses, entrepreneurs, and professionals, CodeAuto 
                             offers an intuitive and efficient platform to streamline operations and boost productivity.</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 col-md-6 mb-4">
                <div class="portfolio-item">
                    <img src="c:\Users\admin\Pictures\original-186207fa92900f336a1fb83f7fac9020.webp" alt="Portfolio Item" class="img-fluid rounded">
                    <div class="portfolio-overlay">
                        <h4>NET PROJECT</h4>
                        <p>MONO sacns-we help you to build a design 
                            for more information contact us
                        </p>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 col-md-6 mb-4">
                <div class="portfolio-item">
                    <img src="c:\Users\admin\Pictures\original-a3170091b4988e9ca7570f0aec5e39d1.webp" alt="Portfolio Item" class="img-fluid rounded">
                    <div class="portfolio-overlay">
                        <h4>CRYPO Mobile APP</h4>
                        <p>This Crypto Mobile App UI/UX is designed to provide a seamless and efficient 
                            platform for managing cryptocurrency portfolios. The dashboard offers an overview of key metrics,
                             including total assets, transaction history, portfolio growth, and market trends, 
                             with real-time updates and insights. It features tools to monitor cryptocurrencies, 
                             execute trades, and track performance across various assets.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<footer class="py-4 bg-dark text-white text-center">
    <div class="container">
        <p class="mb-0">&copy; 2024 divakaran l. All rights reserved.</p>
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


## OUTPUT:
![alt text](<Screenshot 2025-01-06 132603-1.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
