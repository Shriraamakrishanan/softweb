# Ex.07 Restuarant Website
## Date:

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
# menu.html
```
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - The Great Indian Kitchen</title>
    <style>
        body {
            background-color: rgb(200, 96, 205);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(92, 225, 156);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(85, 241, 90);
        }
        nav a {
            color: rgb(248, 97, 97);
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(198, 224, 114);
        }
        section {
            padding: 20px;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            text-align: center;
        }
        .menu-item {
            border: 1px solid silver;
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color: rgb(205, 205, 87);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Our Menu</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Explore Our Dishes</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="Hyderabadi Lamb Biryani.jpg" alt="briyani">
                <h3>briyani</h3>
                <p>Hyderabadi Biryani is a world-renowned dish that epitomizes the rich culinary heritage of Hyderabad. This aromatic rice delicacy is made with long-grained basmati rice, tender marinated meat (usually chicken or mutton), and a blend of fragrant spices. Cooked using the traditional dum method, where layers of rice and meat are slow-cooked in a sealed pot, the biryani captures a symphony of flavors. Often garnished with fried onions, fresh mint, and boiled eggs, it is served with raita or mirchi ka salan, making it a feast for the senses and a symbol of regal cuisine.</p>
            </div>
            <div class="menu-item">
                <img src="Crispy Masala Dosa.jpg" alt="Crispy Masala Dosa">
                <h3>Crispy Masala Dosa</h3>
                <p>Crispy Masala Dosa is a popular South Indian delicacy known for its golden, crunchy texture and flavorful filling. Made from a fermented batter of rice and urad dal, the dosa is cooked to perfection on a hot griddle.</p>
            </div>
            <div class="menu-item">
                <img src="grill.jpg" alt="grill">
                <h3>grill</h3>
                <p>grill is an american based dish made of chicken fired to juicy flavour.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; The Great Indian Kitchen. All Rights Reserved.</p>
        <p> designed and developed by: SHRI RAAMA KRISHANAN J</p>
    </footer>
</body>
</html>
```
# about.html
```
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Rio Foods</title>
    <style>
        body {
            background-color: rgb(145, 112, 160);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(34, 87, 88);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(14, 239, 40);
        }
        nav a {
            color: rgb(124, 92, 92);
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(10, 212, 248);
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
            text-align: justify;
        }
        footer {
            background-color: rgb(108, 75, 36);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>About The Great Indian Kitchen</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Our Story</h2>
        <div class="content">
            <p>Welcome to The Great Indian Kitchen, where we bring together a love for fresh, delicious meals and a passion for hospitality. Established with the goal of creating memorable dining experiences, Java Foods is your go-to destination for a delightful culinary journey.</p>
            <p>Our team is committed to using the finest ingredients to prepare dishes that reflect authenticity and innovation. Whether you're here for a hearty meal, a light snack, or a sweet treat, our menu is designed to cater to every craving.</p>
            <p>We take pride in our warm and inviting atmosphere, perfect for family gatherings, friendly get-togethers, or a quiet meal on your own. At Java Foods, we believe food is more than just sustenance—it's an experience, and we are thrilled to share it with you.</p>
        </div>
    </section>
    <footer>
        <p>&copy; The Great Indian Kitchen. All Rights Reserved.</p>
        <p> designed and developed by: SHRI RAAMA KRISHANAN J</p>
    </footer>
</body>
</html>
```
# table.html
```
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Great Indian Kitchen</title>
    <style>
        body {
            background-color: cornsilk;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color:grey;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color:chocolate;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color:grey;
        }
        .hero {
             background-color:navajowhite;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .hero h1 {
            font-size: 3rem;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .menu-item {
            border: 1px solid rgb(51, 170, 103);
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color:rgb(240, 247, 115);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>The Great Indian Kitchen</h1>
    </header>
    <nav>
        <a href="home.html">home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="hero">
        <h1>Welcome to Our Restaurant</h1>
    </div>
    <section id="about">
        <h2>About Us</h2>
        <p>We are passionate about serving delicious food made with fresh ingredients. Join us for an unforgettable dining experience!</p>
    </section>
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="briyani.jpeg">
                <h3>briyani</h3>
                <p>A flavorful and spicy Indian appetizer made with juicy chicken , steamed to have a tasty perfection.</p>
            </div>
            <div class="menu-item">
                <img src="parotta 95.jpeg">
                <h3>parotta 95</h3>
                <p>A rich and creamy North Indian curry with soft parotta in a buttery tomato-based gravy.</p>
            </div>
            <div class="menu-item">
                <img src="grill.jpeg">
                <h3>grill</h3>
                <p>grill is an american based dish made of chicken fired to juicy flavour.</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Phone: 9025934788</p>
        <p>Email:thegreatindiankitchen@gmail.com</p>
        <p>Address:340, 341, 2nd Ave, G Block, Ranganathan Garden, Anna Nagar, Chennai, Tamil Nadu 600040</p>
    </section>
    <footer>
        <p>&copy;The Great Indian Kitchen . All Rights Reserved.</p>
    </footer>
</body>
</html>

```
# contact.html
```
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - The Great Indian Kitchen</title>
    <style>
        body {
            background-color: rgb(118, 54, 161);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(41, 106, 106);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(147, 110, 59);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(61, 230, 97);
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .contact-info {
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.6;
        }
        footer {
            background-color: rgb(162, 240, 89);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>A warm welcome</h2>
        <div class="contact-info">
            <p><strong>Phone:</strong> 9025934788</p>
            <p><strong>Email:</strong> thegreatindiankitchen@gmail.com</p>
            <p><strong>Address:</strong> 340, 341, 2nd Ave, G Block, Ranganathan Garden, Anna Nagar, Chennai, Tamil Nadu 600040</p>
            <p>we value your feedback</p>
    </section>
    <footer>
        <p>&copy; The Great Indian Kitchen. All Rights Reserved.</p>
        <p> designed and developed by: SHRI RAAMA KRISHANAN J</p>
    </footer>
</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot 2025-10-30 184446.png>)
![alt text](<Screenshot 2025-10-30 184459.png>)
![alt text](<Screenshot 2025-10-30 184515.png>)
![alt text](<Screenshot 2025-10-30 184523.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
