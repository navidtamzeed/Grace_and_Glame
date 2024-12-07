<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Grace & Glame</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header -->
    <header>
        <div class="logo">
            <img src="logo.png" alt="Grace & Glame Logo" />
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-text">
            <h1>Welcome to Grace & Glame</h1>
            <p>Your perfect fashion destination.</p>
        </div>
    </section>

    <!-- Product Section -->
    <section id="shop" class="product-section">
        <h2>Featured Products</h2>
        <div class="product-container">
            <!-- Product 1 -->
            <div class="product-card">
                <img src="product1.jpg" alt="Product 1">
                <h3>Product Name</h3>
                <p>Price: $XX.XX</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>

            <!-- Product 2 -->
            <div class="product-card">
                <img src="product2.jpg" alt="Product 2">
                <h3>Product Name</h3>
                <p>Price: $XX.XX</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>

            <!-- Product 3 -->
            <div class="product-card">
                <img src="product3.jpg" alt="Product 3">
                <h3>Product Name</h3>
                <p>Price: $XX.XX</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about-section">
        <h2>About Us</h2>
        <p>Grace & Glame is your go-to online fashion store offering the best in style and comfort. We curate trendy pieces for your wardrobe.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <p>Have any questions? Get in touch with us!</p>
        <form>
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Your Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <div class="social-links">
            <a href="https://www.facebook.com/graceandglame" target="_blank">Facebook</a>
            <a href="https://www.instagram.com/grace__glame" target="_blank">Instagram</a>
            <a href="tel:+8801724722400">Call: +880 1724-722400</a>
        </div>
        <p>&copy; 2024 Grace & Glame. All rights reserved.</p>
    </footer>

</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    display: flex;
    justify-content: space-between;
    padding: 20px;
    background-color: #333;
    color: white;
}

header .logo img {
    width: 150px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li {
    display: inline;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.hero {
    background: url('hero-image.jpg') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.hero h1 {
    font-size: 3rem;
}

.product-section {
    padding: 50px;
    background-color: #f4f4f4;
    text-align: center;
}

.product-container {
    display: flex;
    justify-content: space-around;
    gap: 20px;
}

.product-card {
    background: white;
    padding: 20px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    width: 30%;
    text-align: center;
}

.product-card img {
    width: 100%;
    height: auto;
}

.product-card .btn {
    display: block;
    margin-top: 10px;
    padding: 10px;
    background-color: #333;
    color: white;
    text-decoration: none;
    text-align: center;
}

.contact-section form {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    background-color: #f4f4f4;
    border-radius: 8px;
}

.contact-section input, .contact-section textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact-section .btn {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

footer {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

footer a {
    color: white;
    text-decoration: none;
    margin: 0 10px;
}
