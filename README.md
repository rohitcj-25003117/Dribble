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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Responsive Website using Bootstrap</title>

  <!-- Bootstrap CSS -->
  <link 
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" 
    rel="stylesheet"
  />

  <style>
    .hero {
      background: url("https://images.unsplash.com/photo-1519125323398-675f0ddb6308")
        center/cover no-repeat;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 5px black;
    }
  </style>
</head>
<body>

  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">MyBootstrapSite</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      
      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#features">Features</a></li>
          <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- HERO SECTION -->
  <section class="hero text-center">
    <div>
      <h1 class="display-4 fw-bold">Responsive Web Design</h1>
      <p class="lead">Built Completely Using Bootstrap</p>
      <a href="#features" class="btn btn-primary btn-lg">Explore</a>
    </div>
  </section>

  <!-- FEATURES SECTION -->
  <section id="features" class="py-5">
    <div class="container text-center">
      <h2 class="mb-4 fw-bold">Features</h2>

      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="p-4 shadow rounded">
            <h4>100% Responsive</h4>
            <p>Website adjusts perfectly on mobile, tablet & desktop screens.</p>
          </div>
        </div>

        <div class="col-md-4 mb-4">
          <div class="p-4 shadow rounded">
            <h4>Bootstrap 5</h4>
            <p>Uses the latest version of Bootstrap for layout & design.</p>
          </div>
        </div>

        <div class="col-md-4 mb-4">
          <div class="p-4 shadow rounded">
            <h4>Clean UI</h4>
            <p>Modern and minimal user interface for better experience.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- IMAGE GALLERY -->
  <section id="gallery" class="py-5 bg-light">
    <div class="container text-center">
      <h2 class="fw-bold mb-4">Gallery</h2>

      <div class="row g-3">
        <div class="col-md-4 col-6">
          <img src="https://picsum.photos/400?1" class="img-fluid rounded shadow" />
        </div>
        <div class="col-md-4 col-6">
          <img src="https://picsum.photos/400?2" class="img-fluid rounded shadow" />
        </div>
        <div class="col-md-4 col-6">
          <img src="https://picsum.photos/400?3" class="img-fluid rounded shadow" />
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACT SECTION -->
  <section id="contact" class="py-5">
    <div class="container text-center">
      <h2 class="fw-bold mb-4">Contact Us</h2>

      <form class="mx-auto" style="max-width: 600px;">
        <input class="form-control mb-3" type="text" placeholder="Name" required />
        <input class="form-control mb-3" type="email" placeholder="Email" required />
        <textarea class="form-control mb-3" rows="4" placeholder="Message"></textarea>

        <button class="btn btn-success px-4">Send Message</button>
      </form>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-dark text-light text-center py-3">
    <p class="m-0">&copy; 2025 MyBootstrapSite | All Rights Reserved</p>
  </footer>

  <!-- Bootstrap JS -->
  <script 
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js">
  </script>

</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2025-11-16 222741.png>)
![alt text](<Screenshot 2025-11-16 222810.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
