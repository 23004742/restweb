# Ex.07 Restaurant Website
## Date:15-5-2025

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
admin.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Administration</title>
    <style>
        /* Basic Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff0000;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: rgb(255, 174, 0);
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        h2 {
            text-align: center;
            color: #333;
        }

        .admin-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .admin-item {
            background-color: #fff;
            border: 1px solid #000000;
            border-radius: 8px;
            padding: 15px;
            width: 200px;
            text-align: center;
            margin: 10px;
        }

        .admin-item img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        .admin-item h3 {
            margin: 0;
            color: #333;
        }

        .admin-item p {
            color: #777;
            margin: 5px 0;
        }

        footer {
            background-color: #ff0000;
            color: rgb(255, 0, 0);
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Restaurant Administration</h1>
    </header>

    <section>
        <h2>Meet Our Team</h2>

        <div class="admin-list">
            <!-- Admin 1 -->
            <div class="admin-item">
                <img src="download (1).jpg" alt="parthiban">
                <h3>PARTHIBAN</h3>
                <p>Founder</p>
            </div>

            <!-- Admin 2 -->
            <div class="admin-item">
                <img src="AK.jpg" alt="AK">
                <h3>AK</h3>
                <p>Head Chef</p>
            </div>

            <!-- Admin 3 -->
            <div class="admin-item">
                <img src="ME.jpg" alt="Akash">
                <h3>AKASH</h3>
                <p> Manager</p>
            </div>

            <!-- Admin 4 -->
            <div class="admin-item">
                <img src="JEEVAN.jpg" alt="JEEVAN">
                <h3>JEEVAN</h3>
                <p>Customer Service Lead</p>
            </div>

            <!-- Admin 5 -->
            <div class="admin-item">
                <img src="ROLEX.jpg" alt="ROLEX">
                <h3>ROLEX</h3>
                <p> Chef</p>
            </div>

           
        </div>

    </section>

    

</body>
</html>
```
contact.html
```
  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff0000;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 30px;
            margin: 20px;
            background-color: rgb(255, 187, 0);
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #333;
        }

        p {
            font-size: 1.1em;
        }

        .contact-info {
            margin-top: 20px;
        }

        .contact-info p {
            margin: 10px 0;
        }

        footer {
            background-color: #8b2121;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact-info h3 {
            margin-bottom: 15px;
            color: #ff0000;
        }

        a {
            text-decoration: none;
            color: #002fff;
        }
    </style>
</head>
<body>
     <header>
        <h1>HOTEL AK- Contact Us</h1>
    </header>

    <section>
        <h2>Get in Touch with Us</h2>
        <p>If you have any questions or feedback, we would love to hear from you! Please find our contact details below.</p>

        <div class="contact-info">
            <h3>Restaurant Details:</h3>
            <p><strong>Address:</strong> NO.34/2  OPPOSITE  TO  NOYYAL  HOSTEL , SAVEETHA  UNIVERSITY , CHENNAI</p>
            <p><strong>Phone:</strong> 9876543210,7890654321</p>
            <p><strong>Email:</strong> <a href="mailto:contact@restaurant.com">akrestaurant@gmail.com</a></p>
        </div>

        <h3>TIMING</h3>
         10.00 am - 12.00 am
```
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Home</title>
    <style>
        /* Basic Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffd900;
        }

        header {
            background-color: #ff0000;
            color: rgb(255, 255, 255);
            text-align: center;
            padding: 20px;
        }

        h1 {
            margin: 0;
        }

        .intro {
            text-align: center;
            margin-top: 20px;
        }

        .intro p {
            font-size: 1.2em;
            color: #555;
        }

        .gallery {
            display: flex;
            justify-content: space-around;
            margin: 20px;
            flex-wrap: wrap;
        }

        .gallery img {
            width: 250px;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
            margin: 10px;
        }

        footer {
            background-color: #ff0000;
            color: rgb(255, 255, 255);
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>HOTEL AK</h1>
        <p>Delicious Food, Amazing Atmosphere</p>
    </header>

    <div class="intro">
        <h2>Our Best Dishes</h2>
        <p>Take a look at some of our most popular dishes!</p>
    </div>

    <div class="gallery">
        <!-- Image 1 -->
        <img src="briyani.avif" alt="SPECIAL BIRIYANI">
        <!-- Image 2 -->
        <img src="falooda.jpeg" alt="FALOODA">
        <!-- Image 3 -->
        <img src="noobles.jpeg" alt="CHICKEN NOODLES">
        <!-- Image 4 -->
        <img src="sawarma.jpeg" alt="SHAWARMA">
        <!-- Image 5 -->
        <img src="grill.jpeg" alt="GRILLED CHICKEN">
    </div>

    <footer>
        <p>Designed by AKASH</p>
    </footer>

</body>
</html>
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Menu</title>
    <style>
        /* Simple Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #ff0000;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #fc0000;
            color: rgb(0, 0, 0);
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: rgb(251, 205, 3);
            border-radius: 8px;
        }

        h2 {
            color: #000000;
            text-align: center;
        }

        .menu-item {
            display: flex;
            align-items: center;
            margin-bottom:-10px;
            padding: -10px;
            border-bottom: 1px solid #ddd;
        }

        .menu-item:last-child {
            border-bottom: none;
        }

        .menu-item img {
            width: 100px;
            height: 100px;
            margin-right: 20px;
            border-radius: 8px;
        }

        .menu-item h3 {
            margin: 0;
            color: #333;
        }

        .menu-item p {
            margin: 2px;
            color: #777;
        }

        .price {
            font-weight: bold;
            color: #13025e;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Hotel AK</h1>
    </header>

    <section>
        <h2>Our Menu</h2>
        
        <div class="menu-item">
            <img src="noobles.jpeg" alt="Chicken noodles">
            <div>
                <h3>Chicken noodles</h3>
                <p>Classic chinese chicken noodles with tomato & chilli sauce.</p>
                <span class="price">Rs.120</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="sawarma.jpeg" alt="Shawarma">
            <div>
                <h3>Shawarma</h3>
                <p> Juicy Shawarma.</p>
                <span class="price">Rs.80</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="grill.jpeg" alt="Grilled Chicken ">
            <div>
                <h3>Grilled chicken</h3>
                <p>Spicy grill with mint chuttney and mayonese </p>
                <span class="price">Rs.340 per kg</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="briyani.avif" alt="Special biriyani">
            <div>
                <h3>Special biriyani</h3>
                <p>Spicy and tasty biriyani</p>
                <span class="price">Rs.230</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="falooda.jpeg" alt="Falooda">
            <div>
                <h3>Falooda </h3>
                <p>Chill falooda with fruits.</p>
                <span class="price">Rs.90</span>
            </div>
        </div>

        
    </section>

   

</body>
</html>

```
rest.html
```
<!-- Save this file as index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-color: #ff0000;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #f7d200;
        }
        nav a {
            color: rgb(0, 0, 0);
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #0ceacc;
        }
        .banner {
            background-color:#ff0000;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2em;
            text-shadow: 2px 2px 4px #000;
        }
        .content {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
        }
    </style>
</head>
<body>
    <header>
        <h1>HOTEL AK</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <div class="banner">
        NAMBI VAAINGA HAPPY YA POONGA!
    </div>
    <div class="content">
        <h2>About Us</h2>
        <p>Welcome to our restaurant! We offer variety of delicious food !!</p>
    </div>
    <footer>
        <p>&copy; 2026 restaurant</p>
    </footer>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (13).png>)
![alt text](<Screenshot (14).png>)
![alt text](<Screenshot (15).png>)
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (17).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
