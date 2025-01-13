<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Food Products</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Delicious Food Products</h1>
        <nav>
            <a href="#products">Products</a>
            <a href="#contact">Contact Us</a>
        </nav>
    </header>

    <main>
        <section id="products">
            <h2>Our Products</h2>
            <div class="product">
                <img src="product1.jpg" alt="Product 1">
                <p>Fresh Organic Honey - $10</p>
            </div>
            <div class="product">
                <img src="product2.jpg" alt="Product 2">
                <p>Natural Olive Oil - $15</p>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>© 2025 Delicious Food Products. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: #ff6347;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav a {
    margin: 0 10px;
    color: white;
    text-decoration: none;
}

main {
    padding: 2rem;
    text-align: center;
}

.product img {
    width: 200px;
    border-radius: 10px;
}

.product {
    margin: 20px;
}

form input, form textarea {
    display: block;
    width: 100%;
    margin-bottom: 10px;
    padding: 10px;
}

form button {
    padding: 10px 20px;
    background: #ff6347;
    color: white;
    border: none;
    cursor: pointer;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
}
