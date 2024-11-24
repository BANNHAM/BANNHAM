<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BANNHAM - Authentic Khmer Cuisine</title>
    <style>
        /* General Styles */
        body {
            font-family: "Arial", sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
        }
        header {
            text-align: center;
            padding: 2em 0;
            background-color: #fff;
        }
        header img {
            width: 200px;
        }
        nav {
            text-align: center;
            padding: 1em 0;
            background-color: #fff;
            border-bottom: 2px solid #ff7733;
        }
        nav a {
            text-decoration: none;
            color: #ff7733;
            margin: 0 1em;
            font-weight: bold;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: #fff;
            text-align: center;
            padding: 3em 1em;
            border-bottom: 2px solid #ff7733;
        }
        .hero h1 {
            font-size: 3em;
            color: #ff7733;
        }
        .hero p {
            font-size: 1.2em;
            margin-top: 1em;
            color: #555;
        }
        section {
            padding: 2em 1em;
            max-width: 1200px;
            margin: auto;
            text-align: center;
        }
        section h2 {
            font-size: 2.5em;
            color: #ff7733;
        }
        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 1.5em;
            margin-top: 2em;
        }
        .menu-item {
            width: 280px;
            border: 1px solid #ddd;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            background-color: #fff;
        }
        .menu-item img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .menu-item h3 {
            color: #ff7733;
            margin: 0.5em 0;
        }
        .menu-item p {
            margin: 0.5em;
            color: #666;
        }
        footer {
            background-color: #ff7733;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            margin-top: 2em;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

<header>
    <!-- Logo -->
    <img src="logo.jpg" alt="BANNHAM Logo">
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero">
    <h1>Welcome to BANNHAM</h1>
    <p>Experience the rich and authentic flavors of Khmer cuisine.</p>
</div>

<section id="menu">
    <h2>Our Menu</h2>
    <div class="menu">
        <div class="menu-item">
            <img src="https://example.com/amok.jpg" alt="Fish Amok">
            <h3>Fish Amok</h3>
            <p>Aromatic curry with tender fish and coconut milk.</p>
            <p><strong>$12.99</strong></p>
        </div>
        <div class="menu-item">
            <img src="https://example.com/loklak.jpg" alt="Beef Lok Lak">
            <h3>Beef Lok Lak</h3>
            <p>Flavorful stir-fried beef served with lime sauce.</p>
            <p><strong>$10.99</strong></p>
        </div>
        <div class="menu-item">
            <img src="https://example.com/nombanhchok.jpg" alt="Nom Banh Chok">
            <h3>Nom Banh Chok</h3>
            <p>Rice noodles with a fragrant green curry.</p>
            <p><strong>$8.99</strong></p>
        </div>
    </div>
</section>
<section id="about">
    <h2>About Us</h2>
    <p>BANNHAM is dedicated to preserving the rich culinary traditions of Cambodia. We bring authentic Khmer dishes to your table with the freshest ingredients and timeless recipes.</p>
</section>
<section id="contact">
    <h2>Contact Us</h2>
    <p>📍 Address: 123 Khmer St, Phnom Penh</p>
    <p>📞 Phone: (123) 456-7890</p>
    <p>📧 Email: info@bannham.com</p>
</section>

<footer>
    <p>© 2024 BANNHAM. All Rights Reserved.</p>
</footer>

</body>
</html>
