# Ex.07 Restaurant Website
## Date:04.10.2025

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Foodie's Delight</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #F5F5DC;
      color: #333;
      margin: 0;
      scroll-behavior: smooth;
    }
    header {
      background-color: #8B0000;
      color: white;
      padding: 10px;
      text-align: center;
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      background-color: #FFD700;
      margin: 0;
      padding: 10px 0;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      text-decoration: none;
      color: #8B0000;
      font-weight: bold;
    }
    .banner {
      width: auto;
      height: auto;
      object-fit: cover;
    }
    section {
      padding: 20px;
    }
    .menu-list li {
      padding: 5px 0;
    }
    .admin-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
    }
    .admin-card {
      text-align: center;
    }
    .admin-card img {
      width: 120px;
      height: 120px;
      object-fit: cover;
      border-radius: 50%;
    }
    footer {
      background-color: #8B0000;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>

  <header>
    <img src="C:\Users\Shakt\EX7\restweb\restaurent\restaurent\static\download.jpeg" width="400px" height="200px">
    <h1>Foodie's Delight</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#admin">Administration</a></li>
        <li><a href="#contact">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h2>Welcome to Foodie's Delight</h2>
    <p>Experience the best flavors from around the world. Our chefs craft each dish with passion and precision.</p>
  </section>

  <section id="menu">
    <h2>Our Menu</h2>
    <ul class="menu-list">
      <li>Margherita Pizza</li>
      <li>Butter Chicken</li>
      <li>Paneer Tikka</li>
      <li>Spaghetti Carbonara</li>
      <li>Caesar Salad</li>
      <li>Grilled Salmon</li>
      <li>Veg Biryani</li>
      <li>Chicken Shawarma</li>
      <li>Tom Yum Soup</li>
      <li>Chocolate Lava Cake</li>
      <li>Mango Lassi</li>
      <li>Garlic Bread</li>
    </ul>
  </section>

  <section id="admin">
    <h2>Meet Our Team</h2>
    <div class="admin-grid">
      <div class="admin-card">
        <img src="person1.jpg" alt="Rajesh Kumar">
        <p>Chef - Rajesh Kumar</p>
      </div>
      <div class="admin-card">
        <img src="person2.jpg" alt="Priya Sharma">
        <p>Manager - Priya Sharma</p>
      </div>
      <div class="admin-card">
        <img src="person3.jpg" alt="Arjun Mehta">
        <p>Head Waiter - Arjun Mehta</p>
      </div>
      <div class="admin-card">
        <img src="person4.jpg" alt="Neha Verma">
        <p>Pastry Chef - Neha Verma</p>
      </div>
      <div class="admin-card">
        <img src="person5.jpg" alt="Anjali Rao">
        <p>Receptionist - Anjali Rao</p>
      </div>
      <div class="admin-card">
        <img src="person6.jpg" alt="Ramesh Singh">
        <p>Cleaner - Ramesh Singh</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>📍 Address: 123 Food Street, Sriperumbudur, TN, India</p>
    <p>📞 Phone: +91-9876543210</p>
    <p>📧 Email: contact@foodiesdelight.com</p>
  </section>

  <footer>
    <p style="font-size: xx-large;">Foodie's Delight</p>
  </footer>

</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (1).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
