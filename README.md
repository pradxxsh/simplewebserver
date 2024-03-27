
# EX01 Developing a Simple Webserver
## Date:
27.03.2024
## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:



```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SEC PORTAL</title>
    <style>
        a{
            padding: 15px;
            text-decoration: none;
            color: rgb(238, 11, 11);
            font-family: Arial;
            font-size: 15px;
        }
        a:hover{
            color: gray;
        }
    </style>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
<div style="display: flex;">
    <div style="width: 25%;">
      <img style="width: 100%;" src="img/logo_1.png" alt="">
    </div>
    <div style="width: 55%; padding-top:13px">
<a href="">Home</a>
<a href="">About</a>
<a href="">Departments</a>
<a href="">Life at SEC</a>
<a href="">Admissions</a>
<a href="">Placements</a>
</div>

<div style="width: 20%; padding-top:8px">

<input style="padding-left: 20px;width: 80%;height: 30px;background-image: url('img/search.png"type="text" placeholder="Search" />

</div>
</div>
<center><div style="width: 60%;"  id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators" >
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner" >
      <div class="carousel-item active">
        <img src="img/1.jpeg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="img/2.jpg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="img/44.jpg" class="d-block w-100" alt="...">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div></center>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
    crossorigin="anonymous"></script>
</body>
</html>
```

## OUTPUT:
![ex01 output](https://github.com/pradxxsh/simplewebserver/assets/131758539/4da8d526-8c01-42e7-b8b5-10b55e637cfa)


## RESULT:
The program for implementing simple webserver is executed successfully.

