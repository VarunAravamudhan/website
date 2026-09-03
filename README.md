# Ex.05 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
## Index
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Restaurent- Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="main-container">
        <div class="brand-header">
            <h1 class="brand-title">Restaurent</h1>
        </div>

        <nav>
            <a href="index.html" class="active">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="contact.html">Contact Us</a>
        </nav>

        <div class="hero-banner">
            <img src="images/banner.jpg" alt="Special Dish">
            <div class="hero-overlay">
                <h2>30% Off This Weekend</h2>
                <p>Enjoy 30% OFF your meal today! Treat yourself to delicious flavors at unbeatable prices — only at our restaurant.</p>
            </div>
        </div>

        <div class="cards-container">
            <div class="card">
                <h3>Our New Menu</h3>
                <img src="images/food1.jpg" alt="Menu Item">
                <p>Check out our exciting new menu items! We've added some delicious options to satisfy your taste buds.</p>
                <a href="menu.html">See our new menu</a>
            </div>

            <div class="card">
                <h3>Book a table</h3>
                <img src="images/food2.jpg" alt="Dining Table">
                <p>Reserve your spot easily and enjoy a wonderful dining experience with us.</p>
                <a href="contact.html">Book your table now</a>
            </div>

            <div class="card">
                <h3>Opening Hours</h3>
                <img src="images/kitchen.jpg" alt="Kitchen">
                <p>We are open from Monday to Sunday, with varying hours for each day.</p>
                <div class="hours-schedule">
                    <p>Mon - Fri: 2pm - 10pm</p>
                    <p>Sat: 2pm - 11pm</p>
                    <p>Sun: 2pm - 9pm</p>
                </div>
            </div>
        </div>

        <div class="bottom-footer-bar">
            
            <div class="footer-line"></div>
        </div>
    </div>

    <div class="signature">
        Designed and Developed by <span>Varun Aravamudhan</span>
    </div>

</body>
</html>
~~~

## Menu
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon - Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="main-container">
        <div class="brand-header">
            <h1 class="brand-title">Restaurent</h1>
        </div>

        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html" class="active">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="contact.html">Contact Us</a>
        </nav>

        <div class="grid-section">
            <div class="grid-card"><img src="images/m1.jpg" alt="Food"><h4>Greek Salad</h4><p>Crispy lettuce, peppers, olives, feta cheese.</p><div class="price">₹280</div></div>
            <div class="grid-card"><img src="images/m2.jpg" alt="Food"><h4>Bruschetta</h4><p>Grilled bread with garlic, salt, and olive oil.</p><div class="price">₹220</div></div>
            <div class="grid-card"><img src="images/m3.jpg" alt="Food"><h4>Lemon Dessert</h4><p>Traditional layered citrus cake.</p><div class="price">₹190</div></div>
            <div class="grid-card"><img src="images/m4.jpg" alt="Food"><h4>Grilled Fish</h4><p>Catch of the day with herb butter seasoning.</p><div class="price">₹450</div></div>
            <div class="grid-card"><img src="images/m5.jpg" alt="Food"><h4>Pasta Alfredo</h4><p>Creamy fettuccine with parmesan cheese.</p><div class="price">₹320</div></div>
            <div class="grid-card"><img src="images/m6.jpg" alt="Food"><h4>Margherita Pizza</h4><p>Fresh tomatoes, basil, and mozzarella.</p><div class="price">₹380</div></div>
            <div class="grid-card"><img src="images/m7.jpg" alt="Food"><h4>Paneer Tikka</h4><p>Spiced cottage cheese cooked in clay oven.</p><div class="price">₹290</div></div>
            <div class="grid-card"><img src="images/m8.jpg" alt="Food"><h4>Chicken Biryani</h4><p>Aromatic basmati rice with spiced chicken.</p><div class="price">₹360</div></div>
            <div class="grid-card"><img src="images/m9.jpg" alt="Food"><h4>Crispy Calamari</h4><p>Fried squid rings with tartare dip.</p><div class="price">₹410</div></div>
            <div class="grid-card"><img src="images/m10.jpg" alt="Food"><h4>Garlic Bread</h4><p>Toasted baguette slices with herbs and garlic.</p><div class="price">₹160</div></div>
            <div class="grid-card"><img src="images/m11.jpg" alt="Food"><h4>Tiramisu</h4><p>Classic espresso-infused mascarpone delight.</p><div class="price">₹240</div></div>
            <div class="grid-card"><img src="images/m12.jpg" alt="Food"><h4>Iced Lemon Tea</h4><p>Fresh brewed black tea with lemon zest.</p><div class="price">₹120</div></div>
        </div>

        <div class="bottom-footer-bar">
           
            <div class="footer-line"></div>
        </div>
    </div>

    <div class="signature">
        Designed and Developed by <span>Varun Aravamudhan</span>
    </div>

</body>
</html>
~~~

## Admin
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurent - Administration</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="main-container">
        <div class="brand-header">
            <h1 class="brand-title">Restaurent</h1>
        </div>

        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html" class="active">Administration</a>
            <a href="contact.html">Contact Us</a>
        </nav>

        <div class="grid-section">
            <div class="grid-card"><img src="images/staff1.png" alt="Staff"><h4>Varun</h4><p><strong>Executive Head Chef</strong></p><p>Co-founder & Master Chef.</p></div>
            <div class="grid-card"><img src="images/staff2.png" alt="Staff"><h4>Abi</h4><p><strong>General Manager</strong></p><p>Operations & Management.</p></div>
            <div class="grid-card"><img src="images/staff3.png" alt="Staff"><h4>Maha</h4><p><strong>Head of Hospitality</strong></p><p>Guest Experience Lead.</p></div>
            <div class="grid-card"><img src="images/staff4.png" alt="Staff"><h4>Aravamudhan</h4><p><strong>Sous Chef</strong></p><p>Pastas & Italian Delicacies.</p></div>
            <div class="grid-card"><img src="images/staff5.png" alt="Staff"><h4>Diya</h4><p><strong>Pastry Specialist</strong></p><p>Artisanal Breads & Desserts.</p></div>
            <div class="grid-card"><img src="images/staff6.png" alt="Staff"><h4>Thirumudikari</h4><p><strong>Inventory Supervisor</strong></p><p>Supply Chain & Compliance.</p></div>
        </div>

        <div class="bottom-footer-bar">

            <div class="footer-line"></div>
        </div>
    </div>

    <div class="signature">
        Designed and Developed by <span>Varun Aravamudhan</span>
    </div>

</body>
</html>
~~~

## Contact
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon - Contact Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="main-container">
        <div class="brand-header">
            <h1 class="brand-title">Restaurent</h1>
        </div>

        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="contact.html" class="active">Contact Us</a>
        </nav>

        <div class="contact-card-box">
            <p><strong>📍 Address:</strong> No. 45, Mediterranean Avenue, Central Plaza, Chennai - 600056</p>
            <p><strong>📞 Phone:</strong> +91 98450 12345 / 044-24567890</p>
            <p><strong>✉️ Email:</strong> contact@restaurent.com</p>
            <p><strong>🕒 Table Reservation:</strong> Available daily from 10:00 AM - 9:00 PM</p>
        </div>

        <div class="bottom-footer-bar">
            
            <div class="footer-line"></div>
        </div>
    </div>

    <div class="signature">
        Designed and Developed by <span>Varun Aravamudhan</span>
    </div>

</body>
</html>
~~~
# OUTPUT:
## Home

![alt text](image.png)

## Menu

![alt text](image-1.png)

## Admin

![alt text](image-2.png)

## Contact

![alt text](image-3.png)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
