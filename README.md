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
