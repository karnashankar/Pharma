# Project Responsive Web Design using Bootstrap
## Date:10/04/2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
  <title>Pharma</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Therapeia Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">Our Story</a></li>
              <li><a class="dropdown-item" href="#">Our Mission</a></li>
              <li><a class="dropdown-item" href="#">Leadership Team</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">News & Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about us.html
            ">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="hero d-flex align-items-center justify-content-center text-center py-5 mb-5">
    <div class="container">
      <h1>Innovating Healthcare Solutions</h1>
      <p class="lead">We are dedicated to developing and delivering life-changing medications.</p>
      <a href="#" class="btn btn-primary btn-lg">Learn More</a>
    </div>
  </section>

  <section class="container">
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="r&d.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Research & Development</h5>
            <p class="card-text">We invest heavily in R&D to discover new and innovative treatments.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="quality.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Quality & Manufacturing</h5>
            <p class="card-text">Our commitment to quality ensures the safety and efficacy of our medications.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="patient.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Patient Care</h5>
            <p class="card-text">We are dedicated to improving the lives of patients worldwide.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 Therapeia Pharma</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
##Products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Products</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
</head>
<body>


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Therapeia Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">Our Story</a></li>
              <li><a class="dropdown-item" href="#">Our Mission</a></li>
              <li><a class="dropdown-item" href="#">Leadership Team</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">News & Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about us.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-5">
    <h1 class="text-center mb-4">Our Products</h1>
    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
      <div class="col">
        <div class="card">
          <img src="p1.jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Leqembi</h5>
            <p class="card-text">We start our list much as we did last year, namely with an Alzheimer’s disease drug at the top. Eli Lilly’s donanemab was Evaluate Vantage’s No. 1 in 2022, and that honor falls to Eisai and Biogen’s lecanemab this year. .</p>
            <a href="#" class="btn btn-primary">Learn More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="p2.jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title"> SRP-9001</h5>
            <p class="card-text">Duchenne muscular dystrophy (DMD) is a devastating disease that takes hold in childhood, slowly weakening the muscles including the heart. The disease, which only affects males, leaves young boys wheelchair-bound and statistically highly unlikely to see their fourth decade. .</p>
            <a href="#" class="btn btn-primary">Learn More</a>
          </div>
        </div>
      </div>
      </div>
  
  
  </section>

  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 Therapeia Pharma</p>
  </footer>

</body>
</html>
```
##even.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Events</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Therapeia Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">Our Story</a></li>
              <li><a class="dropdown-item" href="#">Our Mission</a></li>
              <li><a class="dropdown-item" href="#">Leadership Team</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">News & Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about us.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <section class="container py-5">
    <h1 class="text-center mb-4">News & Events</h1>
    <div class="row">
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="drug.jpg" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Quadria Capital picks up stake in NephroPlus for $102 mln</h5>
            <p class="card-text">Quadria Capital invests $102 million in NephroPlus, India's largest dialysis chain, acquiring a 
              minority stake. The move supports NephroPlus in meeting the rising demand for dialysis services in India and Asia. Quadria 
              anticipates dialysis demand growth over the next five years in its targeted markets..</p>
            <a href="#" class="btn btn-primary btn-sm">Read More</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="pill.jpg" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">The penicillin war: India's journey from self-sufficiency to dependence on China</h5>
            <p class="card-text">.</p>After India lost its dominance in making penicillin, a drought of three decades is coming to an 
               end. The drug – which forms the base for a raft of extremely potent antibiotics – is part of the govt’s aggressive push 
                for self-sufficiency in critical areas. Will the plan to claw back to the glorious past work?
            <a href="#" class="btn btn-primary btn-sm">Read More</a>
          </div>
        </div>
      </div>
    </div>
   
    
    </section>
  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 Therapeia Pharma</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
##about us.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>contact us</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Therapeia Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">Our Story</a></li>
              <li><a class="dropdown-item" href="#">Our Mission</a></li>
              <li><a class="dropdown-item" href="#">Leadership Team</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">News & Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about us.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="container py-5">
    <h1 class="text-center mb-4">Contact Us</h1>
    <div class="row">
      <div class="col-md-6">
        <h3>Our Information</h3>
        <p>Therapeia Pharma</p>
        <p>Therapeia Pharma
           sun street,
           moon nagar,
           chennai 600028
        </p>
        <p>Phone Number: <a href="tel:+1234567890">123-456-7890</a></p>
        <p>Email: <a href="mailto:info@yourcompany.com">info@Therapeia.com</a></p>
      </div>
      <div class="col-md-6">
        <h3>Get in Touch</h3>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Your Name</label>
            <input type="text" class="form-control" id="name" required>
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email Address</label>
            <input type="email" class="form-control" id="email" required>
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" rows="3" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </div>
  </section>

  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 Therapeia Pharma</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
## OUTPUT:

![image](https://github.com/karnashankar/Pharma/assets/121109150/38073e4f-35c1-4396-aadc-83e0c6ed9a20)
![image](https://github.com/karnashankar/Pharma/assets/121109150/8d86f60c-5ac6-4176-bcd9-0f436a6eb2ec)
![image](https://github.com/karnashankar/Pharma/assets/121109150/2bfd36fa-a9e8-4818-95b2-f651a3205c89)
![image](https://github.com/karnashankar/Pharma/assets/121109150/a65d7844-32d1-4cad-949b-2b8a5c620f36)




## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
