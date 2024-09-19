# Shopify-website-
Clothing shop 
# Clothing Website

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clothing Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Our Clothing Store</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Latest Trends</h2>
        <p>Discover the latest fashion trends and styles.</p>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product" id="product1">
            <h3>Men's T-Shirt</h3>
            <p>Price: $20</p>
            <button onclick="addToCart('Men\'s T-Shirt')">Add to Cart</button>
        </div>
        <div class="product" id="product2">
            <h3>Women's Dress</h3>
            <p>Price: $35</p>
            <button onclick="addToCart('Women\'s Dress')">Add to Cart</button>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We are dedicated to providing the best clothing options for everyone.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@clothingstore.com</p>
    </section>

    <footer>
        <p>&copy; 2023 Clothing Store. All rights reserved.</p>
    </footer>

    <script>
        function addToCart(item) {
            alert(item + ' has been added to your cart!');
        }
    </script>
</body>
</html>
