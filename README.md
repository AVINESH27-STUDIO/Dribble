# Project Responsive Web Design using Bootstrap
## Date:26/12/2024

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
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body class="bg-info text-white">

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Dribbble</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Community</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
                <li class="nav-item"><a class="btn btn-primary" href="#">Sign Up</a></li>
            </ul>
        </div>
    </nav>

    <div class="container mt-5">

        <div class="text-center mb-4">
            <h4>FaRz</h4>
            <h3>"Bringing You the Best of Fashion, Tech, and More!"</h3>
            <p class="lead">"Find What You Love!"</p>
        </div>

        <div class="row">
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card">
                    <img src="147.jpeg" class="card-img-top" alt="Aesthetic Hoodies">
                    <div class="card-body text-center">
                        <p class="card-title">AESTHETIC HOODIES</p>
                        <small class="text-muted">H&M</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card">
                    <img src="148.jpeg" class="card-img-top" alt="Combos 4 in 1">
                    <div class="card-body text-center">
                        <p class="card-title">COMBOS</p>
                        <small class="text-muted">4 IN 1</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card">
                    <img src="149.jpeg" class="card-img-top" alt="PUMA Shoes">
                    <div class="card-body text-center">
                        <p class="card-title">SHOES</p>
                        <small class="text-muted">PUMA</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card">
                    <img src="146.jpeg" class="card-img-top" alt="Accessories">
                    <div class="card-body text-center">
                        <p class="card-title">ACCESSORIES</p>
                        <small class="text-muted">ARMANI</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card">
                    <img src="145.jpeg" class="card-img-top" alt="Hoodies from H&M">
                    <div class="card-body text-center">
                        <p class="card-title">HOODIES</p>
                        <small class="text-muted">H&M</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card">
                    <img src="crocs.jpeg" class="card-img-top" alt="CROCS">
                    <div class="card-body text-center">
                        <p class="card-title">CROCS</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card">
                    <img src="kurti.jpeg" class="card-img-top" alt="Kurti for Boys">
                    <div class="card-body text-center">
                        <p class="card-title">KURTI</p>
                        <small class="text-muted">BOYS</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card">
                    <img src="rolex.jpeg" class="card-img-top" alt="Rolex Watches">
                    <div class="card-body text-center">
                        <p class="card-title">WATCHES</p>
                        <small class="text-muted">ROLEX</small>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <footer class="bg-dark text-white py-3 text-center">
        <p>© Dribbble. All rights reserved.</p>
        <p>Designed by AVINESH . B</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-26 214541.png>)
![alt text](<Screenshot 2024-12-26 214553.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
