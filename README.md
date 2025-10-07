# Ex.07 Restaurant Website
# Date:07/10/2025
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
```
index

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Spice Haven | Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <h1>Spice Haven</h1>
      <ul>
        <li><a href="index.html" class="active">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to Spice Haven</h2>
    <p>Where traditional Indian flavors meet modern dining.</p>
    <a href="menu.html" class="btn">Explore Menu</a>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>📍 123 Main Street, Chennai, India</p>
    <p>📞 +91 98765 43210</p>
    <p>📧 info@spicehaven.com</p>
  </section>

  <footer>
    <p>© 2025 Spice Haven. All rights reserved.</p>
  </footer>
</body>
</html>

menu

!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Spice Haven | Menu</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <h1>Spice Haven</h1>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html" class="active">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
      </ul>
    </nav>
  </header>

  <section class="menu">
    <h2>Our Menu</h2>
    <div class="menu-grid">
      <div class="menu-item"><img src="parotta.png"><h3>parotta</h3><span>₹320</span></div>
      <div class="menu-item"><img src="prawn.png"><h3>Prawn</h3><span>₹280</span></div>
      <div class="menu-item"><img src="rasamula.png"><h3>rasamula</h3><span>₹350</span></div>
      <div class="menu-item"><img src="shwarama.png"><h3>shwarama</h3><span>₹180</span></div>
      <div class="menu-item"><img src="pannir masala.png"><h3>pannir</h3><span>₹200</span></div>
      <div class="menu-item"><img src="soup.png"><h3>soup</h3><span>₹160</span></div>
      <div class="menu-item"><img src="briyani.png"><h3>briyani</h3><span>₹300</span></div>
      <div class="menu-item"><img src="chappathi.png"><h3>chappathi</h3><span>₹220</span></div>
      <div class="menu-item"><img src="friedrice.png"><h3>friedrice</h3><span>₹60</span></div>
      <div class="menu-item"><img src="bread.png"><h3>bread</h3><span>₹100</span></div>
      <div class="menu-item"><img src="tandoori.png"><h3>tandoori</h3><span>₹90</span></div>
      <div class="menu-item"><img src="chicken.png"><h3>chicken</h3><span>₹50</span></div>
    </div>
  </section>

  <footer>
    <p>© 2025 Spice Haven. All rights reserved.</p>
  </footer>
</body>
</html>

admin

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Spice Haven | Administration</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <h1>Spice Haven</h1>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html" class="active">Administration</a></li>
      </ul>
    </nav>
  </header>

  <section class="admin">
    <h2>Our Administration Team</h2>
    <div class="admin-grid">

      <div class="admin-card">
        <img src="image1.png" alt="Manager">
        <h3>rajesh</h3>
        <p>General Manager</p>
      </div>

      <div class="admin-card">
        <img src="image2.png" alt="Chef">
        <h3> tony</h3>
        <p>Head Chef</p>
      </div>

      <div class="admin-card">
        <img src="image3.png" alt="Sous Chef">
        <h3>bruss</h3>
        <p>Sous Chef</p>
      </div>

      <div class="admin-card">
        <img src="image5.png" alt="Waiter">
        <h3>emilye</h3>
        <p>Senior Waitress</p>
      </div>

      <div class="admin-card">
        <img src="image4.png" alt="Cashier">
        <h3>steve rogerr</h3>
        <p>Cashier</p>
      </div>

      <div class="admin-card">
        <img src="image6.png" alt="Cleaner">
        <h3>ravi</h3>
        <p>Housekeeping Staff</p>
      </div>

    </div>
  </section>

  <footer>
    <p>© 2025 Spice Haven. All rights reserved.</p>
  </footer>
</body>
</html>

css

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}

body {
  background-color: #fffaf5;
  color: #333;
}

/* NAVIGATION */
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #ff7b00;
  padding: 1rem 2rem;
}

nav h1 {
  color: white;
  font-size: 1.5rem;
}

nav ul {
  display: flex;
  list-style: none;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: 600;
}

nav ul li a.active,
nav ul li a:hover {
  border-bottom: 2px solid white;
}

/* HERO SECTION */
.hero {
  background: url('images/restaurant.jpg') center/cover no-repeat;
  height: 80vh;
  color: white;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.hero h2 {
  font-size: 3rem;
  margin-bottom: 10px;
}

.btn {
  background: white;
  color: #ff7b00;
  padding: 10px 25px;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
}

.btn:hover {
  background: #ff7b00;
  color: white;
}

/* MENU PAGE */
.menu {
  padding: 50px 20px;
  text-align: center;
}

.menu h2 {
  color: #ff7b00;
  margin-bottom: 40px;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
}

.menu-item {
  background: white;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  padding: 10px;
  transition: 0.3s;
}

.menu-item:hover {
  transform: scale(1.05);
}

.menu-item img {
  width: 100%;
  height: 180px;
  border-radius: 10px;
  object-fit: cover;
}

.menu-item h3 {
  color: #ff7b00;
  margin-top: 10px;
}

/* ADMINISTRATION PAGE */
.admin {
  padding: 60px 20px;
  text-align: center;
  background: #fff3e0;
}

.admin h2 {
  color: #ff7b00;
  margin-bottom: 30px;
}

.admin-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 25px;
}

.admin-card {
  background: white;
  padding: 15px;
  border-radius: 15px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.admin-card img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 10px;
}

.admin-card h3 {
  margin: 10px 0 5px;
  color: #ff7b00;
}

.admin-card p {
  color: #555;
  font-weight: 500;
}

/* CONTACT + FOOTER */
.contact {
  text-align: center;
  padding: 40px 20px;
}

footer {
  background: #ff7b00;
  color: white;
  text-align: center;
  padding: 15px 0;
  margin-top: 30px;
}

```
# OUTPUT:
![alt text](<Screenshot 2025-10-07 235627.png>)
![alt text](<Screenshot 2025-10-07 235650.png>)
![alt text](<Screenshot 2025-10-07 235845.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
