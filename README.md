# Project Responsive Web Design using Bootstrap
## Date:31/05/2026

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
index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">Dribbble</a>

            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link active" href="#">Shots</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Community</a></li>
                </ul>

                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search">
                    <button class="btn btn-outline-light" type="submit">Search</button>
                </form>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="bg-light text-center py-5">
        <div class="container">
            <h1 class="display-5 fw-bold">Discover Creative Designs</h1>
            <p class="lead">
                Dribbble is the leading destination to find and showcase creative work.
            </p>
            <a href="#" class="btn btn-primary">Get Started</a>
        </div>
    </section>

    <!-- Design Cards -->
    <section class="container my-5">
        <div class="row g-4">

            <div class="col-md-4">
                <div class="card">
                    <img src="https://picsum.photos/400/250?1" class="card-img-top" alt="">
                    <div class="card-body">
                        <h5 class="card-title">UI Design</h5>
                        <p class="card-text">Modern dashboard and mobile interface design.</p>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="https://picsum.photos/400/250?2" class="card-img-top" alt="">
                    <div class="card-body">
                        <h5 class="card-title">Web Design</h5>
                        <p class="card-text">Responsive and attractive website layouts.</p>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="https://picsum.photos/400/250?3" class="card-img-top" alt="">
                    <div class="card-body">
                        <h5 class="card-title">Creative Art</h5>
                        <p class="card-text">Inspiring illustrations and visual concepts.</p>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- About Section -->
    <section class="container my-5">
        <div class="row">
            <div class="col-md-6">
                <h2>About Dribbble</h2>
                <p>
                    Explore thousands of creative projects from talented designers around
                    the world. Share your work and get inspired.
                </p>
            </div>

            <div class="col-md-6">
                <div class="alert alert-info">
                    Join our creative community and showcase your designs.
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center p-3">
        <p class="mb-0">© 2026 Dribbble Clone | Created by Gokul B</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
```

## OUTPUT:
<img width="1920" height="1078" alt="Screenshot 2026-05-31 141214" src="https://github.com/user-attachments/assets/027ef4e9-2f6a-4258-97c7-5b66b1dfdea3" />


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
