# Ex.07 Restaurant Website
## Date:24.12.24

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
Publish the website in the given URL.

## PROGRAM:
```
rest.html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>THE VELVET FLAME</title>
    <style>
         *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: rgb(249, 244, 244);
        }

       
        nav {
            background-color: rgb(131, 34, 34);
            padding: 10px 0;
        }

        .navbar {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }

        .navbar a {
            color: white;
            text-decoration: none;
            font-size: 20px;
            margin: 0 15px;
        }

        .navbar .navbar-brand {
            font-size: 24px;
        }

        .header {
            text-align: center;
            margin: 30px 0;
        }

        .header img {
            width: 700px;
            height: 300px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        h1, h2 {
            text-align: center;
            font-family: 'Liam', sans-serif;
            margin: 20px 0;
        }

   
        .row {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .col-md-4 {
            width: 30%;
            margin-bottom: 20px;
        }

        .card {
            border: 1px solid #ccc;
            border-radius: 8px;
            overflow: hidden;
            background-color: white;
        }

        .card img {
            width: 100%;
            height: auto;
        }

        .card-body {
            padding: 15px;
        }

        .card-title {
            font-size: 18px;
            font-weight: bold;
            text-align: center;
        }

      
        #administration {
            text-align: center;
            margin-top: 50px;
        }

        .admin-grid {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .admin-item {
            margin: 20px;
            text-align: center;
        }

        .admin-item img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

      
        #contact {
            text-align: center;
            margin-top: 50px;
        }

        #contact p {
            margin-bottom: 10px;
        }

        
        footer {
            background-color: #f8f9fa;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <nav>
        <div class="navbar">
            <a class="navbar-brand" href="home.html">THE VELVET FLAME</a> 
            <div>
                <a href="home.html">HOME</a> 
                <a href="about.html">ABOUT</a>
            </div>
        </div>
    </nav>

    <div class="header">
        <img src="Screenshot.png" alt="Restaurant Image">
    </div>

    <div class="container">
        <h1>Experience The Unique Blend Of Taste. Welcome You!</h1>
        <h2>MENU</h2>

        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <img src="noodle.jpg" alt="Noodles">
                    <div class="card-body">
                        <h5 class="card-title">Noodles</h5>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="prawn.jpg" alt="Prawn Gravy">
                    <div class="card-body">
                        <h5 class="card-title">Prawn Gravy</h5>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="fish2.jpg" alt="Fish Fry">
                    <div class="card-body">
                        <h5 class="card-title">Fish Fry</h5>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="chicken gr.jpg" alt="Chicken Gravy">
                    <div class="card-body">
                        <h5 class="card-title">Chicken Gravy</h5>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="fried.jpg" alt="Chicken Fried Rice">
                    <div class="card-body">
                        <h5 class="card-title">Chicken Fried Rice</h5>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="paratha.jpg" alt="Paratha">
                    <div class="card-body">
                        <h5 class="card-title">Paratha</h5>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="egg.jpg" alt="Egg gravy">
                    <div class="card-body">
                        <h5 class="card-title">Egg gravy</h5>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="biryani.jpg" alt="Biriyani">
                    <div class="card-body">
                        <h5 class="card-title">Biryani</h5>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="leg.jpg" alt="Chicken Leg piece">
                    <div class="card-body">
                        <h5 class="card-title">Chicken Leg piece</h5>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="fried rice.jpg" alt="Egg Fried rice">
                    <div class="card-body">
                        <h5 class="card-title">Egg Fried rice</h5>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="chicken 65.jpg" alt="Chicken 65">
                    <div class="card-body">
                        <h5 class="card-title">Chicken 65</h5>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="fish gr.jpg" alt="Chicken Biriyani">
                    <div class="card-body">
                        <h5 class="card-title">Chicken Biriyani</h5>
                    </div>
                </div>
            </div>
        </div>

        <div id="administration">
            <h2>Administration</h2>
            <div class="admin-grid">
                <div class="admin-item">
                    <img src="photo (2).jpeg" alt="SHREYA">
                    <p>V SHREYA</p>
                    <p>CEO</p>
                </div>
                <div class="admin-item">
                    <img src="chef.webp" alt="Sophie">
                    <p>Sophie</p>
                    <p>Head Chef</p>
                </div>
                <div class="admin-item">
                    <img src="manager.png" alt="clara">
                    <p>clara</p>
                    <p>Manager</p>
                </div>
            </div>
        </div>

        <div id="contact">
            <h2>Contact Us</h2>
            <p>Address: 4th road anna nagar, Tamil Nadu, Chennai</p>
            <p>Phone: 0504200059</p>
            <p>Email: velvetflame@gmail.com</p>
        </div>

    </div>

    <footer>
        <p>Designed and Developed by V SHREYA</p>
    </footer>
</body>
</html>


home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - THE VELVET FLAME</title>
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: rgb(249, 244, 244);
        }

        /* Header Section */
        .header {
            text-align: center;
            padding: 50px 0;
        }

        .header h1 {
            font-size: 36px;
        }

        .header p {
            font-size: 18px;
        }

        .btn-home {
            display: inline-block;
            padding: 10px 20px;
            background-color: rgb(131, 34, 34);
            color: white;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
            margin-top: 20px;
        }

        /* Footer */
        footer {
            background-color: #f8f9fa;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Welcome to THE VELVET FLAME</h1>
        <p>Your journey to exquisite flavors begins here.</p>
        <a href="index.html" class="btn-home">Go to Main Page</a>
    </div>

    <footer>
        <p>Designed and Developed by V SHREYA</p>
    </footer>

</body>
</html>


about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - THE VELVET FLAME</title>
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: rgb(249, 244, 244);
            padding: 20px;
        }

        /* Header Section */
        .header {
            text-align: center;
            padding: 50px 0;
            background-color: rgb(131, 34, 34);
            color: white;
        }

        .header h1 {
            font-size: 36px;
        }

        .header p {
            font-size: 18px;
            margin-top: 20px;
        }

        /* Content Section */
        .content {
            margin-top: 40px;
        }

        .content h2 {
            font-size: 28px;
            text-align: center;
            margin-bottom: 30px;
        }

        .content p {
            font-size: 18px;
            line-height: 1.6;
            max-width: 900px;
            margin: 0 auto;
            text-align: justify;
        }

        /* Footer */
        footer {
            background-color: #f8f9fa;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }

        .btn-back {
            display: inline-block;
            padding: 10px 20px;
            background-color: rgb(131, 34, 34);
            color: white;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>About Us</h1>
        <p>Learn more about our journey and passion for great food!</p>
    </div>

    <div class="content">
        <h2>Our Story</h2>
        <p>THE VELVET FLAME was born out of a passion for creating unforgettable dining experiences. Our vision is to offer a unique fusion of traditional flavors with a modern twist, delivering dishes that not only satisfy your taste buds but also leave a lasting impression.</p>

        <p>From humble beginnings, we have grown into a place where food is an art and every meal is crafted with care. We believe in using only the finest ingredients, sourced responsibly, and our chefs are dedicated to perfecting every dish. Whether you're here for a casual meal with family or a special celebration, we promise an unforgettable experience every time.</p>

    </div>

    <footer>
        <p>Designed and Developed by V SHREYA</p>
    </footer>

</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (212).png>)
![alt text](<Screenshot (213).png>)
![alt text](<Screenshot (214).png>)
![alt text](<Screenshot (215).png>)
![alt text](<Screenshot (216).png>)
![alt text](<Screenshot (217).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
