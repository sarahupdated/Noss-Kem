<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Noss Kem - T-shirts</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #c2050b;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #3a3a3a;
        }
        nav a {
            color: #fff;
            padding: 1em;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 2em 0;
        }
        .grunge {
            font-family: 'Courier New', Courier, monospace;
        }
        h1, h2 {
            font-family: 'Courier New', Courier, monospace;
            text-align: center;
        }
        .products img {
            width: 100%;
            height: auto;
        }
        .contact-form, .Ektirahet-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input, .Ektirahet-form input, .contact-form textarea, .Ektirahet-form textarea {
            margin-bottom: 1em;
            padding: 0.5em;
        }
        footer {
            margin-top: 2em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Noss Kem</h1>
        <p class="grunge">Vintage Vibes - T-shirts</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
        <a href="#Ektirahet">Ektirahet</a>
    </nav>
    <div id="home" class="container">
        <h2>Welcome to Noss Kem</h2>
        <p>Your one-stop shop for grunge and vintage-inspired T-shirts. Explore our unique collection and find the perfect fit for your style.</p>
    </div>
    <div id="about" class="container">
        <h2>About Us</h2>
        <p>Noss Kem is a small business dedicated to bringing you the best in vintage and grunge fashion. Our T-shirts are designed with a love for the oldies and a passion for unique styles.</p>
    </div>
    <div id="products" class="container products">
        <h2>Our Products</h2>
        <div>
            <h3>Product 1</h3>
            <img src="product1.jpg" alt="Product 1">
            <p>Description of Product 1.</p>
        </div>
        <div>
            <h3>Product 2</h3>
            <img src="product2.jpg" alt="Product 2">
            <p>Description of Product 2.</p>
        </div>
        <!-- Add more products as needed -->
    </div>
    <div id="Lel tawassol" class="container">
        <h2>Lel tawassol</h2>
        <form class="contact-form">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>
    <div id="Ektirahet" class="container">
        <h2>Ektirahet</h2>
        <form class="Ektirahet-form">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="suggestion" rows="5" placeholder="Your Suggestion" required></textarea>
            <button type="submit">Send Suggestion</button>
        </form>
    </div>
    <footer>
        <p>&copy; 2024 Noss Kem. Kel el hou2ou2 mahfouza.</p>
    </footer>
</body>
</html>
