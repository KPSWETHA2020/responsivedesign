# Design of Responsive Website
## AIM:
To design a responsive website with two break points.

## DESIGN STEPS:
### Step 1: 
Requirement collection.
### Step 2:
Creating the layout using HTML and CSS.
### Step 3:
Updating the sample content.
### Step 4:
Choose the appropriate style and color scheme.
### Step 5:
Validate the layout in various browsers.
### Step 6:
Validate the HTML code.
### Step 7:
Create a database model and migrate the database.
### Step 8:
Retrieve data from database and display it in a dynamic webpage.
### Step 9:
Publish the website in the given URL.

## PROGRAM:
### home.html
```
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <title>Responsive Aboutus Design</title>
</head>

<body>
    <div class="jumbotron">
        <div class="container text-center">
            <h1 class="display-3">Silicon Private Limited</h1>
            <h5 class="display-6">About Silicon Pvt Ltd</h5>
        </div>
    </div>
    <div class="homecontent">    
    <h1>About Us</h1>
    <img src="/static/img/building.jpg" alt="Building">
    <div class="contenttext">
    Silicon Pvt Ltd, provides a broad range of semiconductor and infrastructure software applications that serve the data center, networking, software, broadband, wireless, and storage and industrial markets. Common applications for its products include: data center networking, home connectivity, broadband access, telecommunications equipment, smartphones, base stations, data center servers and storage, factory automation, power generation and alternative energy systems, displays, and mainframe operations and management, and application software development. Some of Silicon's core technologies and products include:
    <ul>
        <li>Memory Chips</li>
        <li>SATA HDD</li>
        <li>SATA SSD </li>
        <li>Broadband Modems</li>
        <li>Wifi Devices</li>
        <li>Switching Devices</li>
        <li>Optical Sensors</li>
    </ul> 
    </div>
    </div>
    <div class="row">
        <div class="col-12">
            <p>Copyright © 2021 Silicon Private Limited, Developed by swetha.</p>
        </div>
    </div>
   


    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
        integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
        integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
        crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
        integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
        crossorigin="anonymous"></script>

</body>

</html>
```
### productsresponsive.html
```
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>Responsive Product Design</title>
</head>

<body>
    <div class="jumbotron">
        <div class="container text-center">
            <h1 class="display-3">Silicon Private Limited</h1>
            <h5 class="display-6">We Manufacture high quality electronic products</h5>
        </div>
    </div>
    <div class="container">
        <div class="row text-center">
            <div class="col-12 col-md-3 "><a href="/home">home</a></div>
            <div class="col-12 col-md-3 "><a href="/productsresponsive">productsresponsive</a></div>
            <div class="col-12 col-md-3 "><a href="/peopleresponsive">peopleresponsive</a></div>
            <div class="col-12 col-md-3 "><a href="/contactus">contactus</a></div>
        </div>
        <div class="row text-center">
            <div class="col-12">
                <h5 class="display-6">Our Premium Products</h5>
            </div>
        </div>
        <div class="row text-center">
            <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/v1.jpg" alt="card image cap">
                <div class="card-body">
                    <h5 class="card-title">Crucial P1 1TB 3D </h5>
                    <p class="card-text">price: Rs.10000.00</p>
                    <a href="#" class="btn btn-primary">More Details</a>
                </div>
            </div>
            <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/v2.jpg" alt="card image cap">
                <div class="card-body">
                    <h5 class="card-title">Adata SX6000 Lite 1TB</h5>
                    <p class="card-text">price: Rs.2000.00</p>
                    <a href="#" class="btn btn-primary">More Details</a>
                </div>
            </div>
            <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/v3.jpg" alt="card image cap">
                <div class="card-body">
                    <h5 class="card-title">Adata SU800 1TB M.2 2280 3D </h5>
                    <p class="card-text">price: Rs.4000.00</p>
                    <a href="#" class="btn btn-primary">More Details</a>
                </div>
            </div>
            <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/v4.jpg" alt="card image cap">
                <div class="card-body">
                    <h5 class="card-title">Samsung 970 Evo 1TB - NVMe PCIe</h5>
                    <p class="card-text">price: Rs.6000.00</p>
                    <a href="#" class="btn btn-primary">More Details</a>
                </div>
            </div>
            <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/v5.jpg" alt="card image cap">
                <div class="card-body">
                    <h5 class="card-title">4GB DDRA4 laptop memory</h5>
                    <p class="card-text">price: Rs.77000.00</p>
                    <a href="#" class="btn btn-primary">More Details</a>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <p>Copyright © 2021 Silicon Private Limited, Developed by swetha.</p>
            </div>
        </div>
    </div>


    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
        integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
        integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
        crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
        integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
        crossorigin="anonymous"></script>

</body>

</html>
```
### peopleresponsive.html
```
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>Responsive People Design</title>
</head>

<body>
    <div class="jumbotron">
        <div class="container text-center">
            <h1 class="display-3">Silicon Private Limited</h1>
            <h5 class="display-6">crew people</h5>
        </div>
    </div>
    <div class="row text-center">
        <div class="col-12">
            <h5 class="display-6">Our Crew People</h5>
        </div>
    </div>
    <div class="row text-center">
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/d1.jpg" alt="card image cap">
            <div class="card-body">
                <h5 class="card-title">Nihan Mohan</h5>
                <p class="card-text">CEO of Silicon labs</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/d2.jpg" alt="card image cap">
            <div class="card-body">
                <h5 class="card-title">sri harish</h5>
                <p class="card-text">Senior Manager Officer </p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/d3.jpg" alt="card image cap">
            <div class="card-body">
                <h5 class="card-title">laya</h5>
                <p class="card-text">Chairman of the Silicon labs</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/d4.jpg" alt="card image cap">
            <div class="card-body">
                <h5 class="card-title">Sri Ram</h5>
                <p class="card-text">Accountant Officer</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/d5.jpg" alt="card image cap">
            <div class="card-body">
                <h5 class="card-title">swetha</h5>
                <p class="card-text"> Chief Financial Officer</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col-12">
            <p>Copyright © 2021 Silicon Private Limited, Developed by swetha.</p>
        </div>
    </div>
   


    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
        integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
        integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
        crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
        integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
        crossorigin="anonymous"></script>
</body>

</html>
```
### contactus.html
```
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <title>Responsive Contactus Design</title>   
</head>

<body>
    <div class="jumbotron">
        <div class="container text-center">
            <h1 class="display-3">Silicon Private Limited</h1>
            <h5 class="display-6">Contact Details of Silicon Private Limited</h5>
        </div>
    </div>

    <div class="contactuscontent">
    <h1>CONTACT US</h1>
    <div class="contactustext">
        <h1> PRASAD (General Contact Manager),</h1>
        <h2> M. K. Silicon Products Private Limited,</h2>
        <h2> ilabs India Private Limited 9th Floor, Maximus Towers 2B, Raheja Mindspace IT Park, APIIC Software Layout,
            Madhapur, Hyderabad,</h2>
        <h2> Telangana, India - 500081,</h2>
        <h2> contact number-91-40-39351000</h2>
        <h3> Email address-Silicon@gmail.com</h3>

    </div>
    <div class="row">
        <div class="col-12">
            <p>Copyright © 2021 Silicon Private Limited, Developed by swetha.</p>
        </div>
    </div>
</div>


    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
        integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
        integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
        crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
        integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
        crossorigin="anonymous"></script>

</body>

</html>
```
## code validation report
![output](./static/img/r1.jpg)
![output](./static/img/r2.jpg)
![output](./static/img/r3.jpg)
![output](./static/img/r4.jpg)

## OUTPUT:
![output](./static/img/o1.jpg)

![output](./static/img/o2.jpg)

![output](./static/img/o3.jpg)

![output](./static/img/o3.jpg)

![output](./static/img/o4.jpg)

![output](./static/img/o5.jpg)

![output](./static/img/o6.jpg)

![output](./static/img/o7.jpg)

![output](./static/img/o8.jpg)

## RESULT:
Thus a website is designed for the responsivedesign with two break points and is hosted in the URL http://swetha.student.saveetha.in:8000/productsresponsive HTML code is validated.