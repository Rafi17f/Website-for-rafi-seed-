<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rafi Seeds - Premium Seeds for Your diet</title>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    <style>
        /* Enhanced CSS: Responsive, better layout, natural theme */
        body {
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #228B22; /* Darker green for nature */
            color: white;
            padding: 30px 20px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        nav {
            background-color: #333;
            overflow: hidden;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            transition: background 0.3s;
        }
        nav a:hover {
            background-color: #555;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1200x500?text=Vibrant+Garden+Seeds'); /* Replace with real image */
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 120px 20px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.7);
        }
        .section {
            padding: 50px 20px;
            text-align: center;
            max-width: 1200px;
            margin: 0 auto;
        }
        .product-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .product {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            padding: 15px;
            width: 250px;
            text-align: center;
            transition: transform 0.3s;
        }
        .product:hover {
            transform: translateY(-5px);
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        button {
            background-color: #228B22;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 4px;
            transition: background 0.3s;
        }
        button:hover {
            background-color: #1B5E20;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        form {
            max-width: 500px;
            margin: 0 auto;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        #cart-items {
            list-style: none;
            padding: 0;
        }
        #cart-items li {
            display: flex;
            justify-content: space-between;
            margin: 10px 0;
            padding: 10px;
            background: #f4f4f4;
            border-radius: 4px;
        }
        /* Responsive Design */
        @media (max-width: 768px) {
            .product {
                width: 100%;
            }
            .hero {
                padding: 80px 20px;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>GreenThumb Seeds</h1>
        <p>Family-owned seed business providing heirloom varieties since 2010</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#home">Home</a>
        <a href="#shop">Shop</a>
        <a href="#about">About Us</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
        <a href="#cart" style="float:right;">Cart (<span id="cart-count">0</span>)</a>
    </nav>

    <!-- Homepage Section -->
    <section id="home" class="hero">
        <h2>Premium Seeds for Your Garden</h2>
        <p>Discover high-quality, sustainable seeds to grow your own fresh produce.</p>
        <button onclick="location.href='#shop'">Shop Now</button>
    </section>

    <section class="section">
        <h2>Featured Products</h2>
        <div class="product-grid">
            <div class="product" data-name="Heirloom Tomato Seeds" data-price="5.99">
                <img src="https://via.placeholder.com/250?text=Tomato+Seeds" alt="Heirloom Tomato Seeds">
                <h3>Heirloom Tomato Seeds</h3>
                <p>$5.99 - Pack of 50</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
            <div class="product" data-name="Basil Seeds" data-price="4.99">
                <img src="https://via.placeholder.com/250?text=Basil+Seeds" alt="Basil Seeds">
                <h3>Basil Seeds</h3>
                <p>$4.99 - Pack of 100</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
            <div class="product" data-name="Sunflower Seeds" data-price="6.99">
                <img src="https://via.placeholder.com/250?text=Sunflower+Seeds" alt="Sunflower Seeds">
                <h3>Sunflower Seeds</h3>
                <p>$6.99 - Pack of 30</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
            <div class="product" data-name="Carrot Seeds" data-price="3.99">
                <img src="https://via.placeholder.com/250?text=Carrot+Seeds" alt="Carrot Seeds">
                <h3>Carrot Seeds</h3>
                <p>$3.99 - Pack of 200</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
            <div class="product" data-name="Lavender Seeds" data-price="7.49">
                <img src="https://via.placeholder.com/250?text=Lavender+Seeds" alt="Lavender Seeds">
                <h3>Lavender Seeds</h3>
                <p>$7.49 - Pack of 50</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
    </section>

    <section class="section">
        <h2>Subscribe to Our Newsletter</h2>
        <form id="newsletter-form">
            <input type="email" placeholder="Enter your email" required>
            <button type="submit">Subscribe</button>
        </form>
        <p>Get planting tips, promotions, and updates delivered to your inbox.</p>
    </section>

    <!-- Shop Section -->
    <section id="shop" class="section">
        <h2>Our Products</h2>
        <p>Explore our full range of seeds. Filter by category coming soon!</p>
        <div class="product-grid">
            <!-- Products from featured plus more can be added here -->
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="section">
        <h2>About Us</h2>
        <p>We are a family-owned business dedicated to providing sustainable, heirloom seeds for home gardeners. Our mission is to promote eco-friendly gardening practices and help you grow your own food.</p>
        <img src="https://via.placeholder.com/600x300?text=Our+Farm" alt="Our Farm" style="max-width:100%; border-radius:8px;">
    </section>

    <!-- Blog Section -->
    <section id="blog" class="section">
        <h2>Blog</h2>
        <article>
            <h3>How to Start a Vegetable Garden</h3>
            <p>Beginner tips for planting your first seeds, including soil preparation and watering schedules.</p>
        </article>
        <article>
            <h3>Best Seeds for Beginners</h3>
            <p>Easy-to-grow options like radishes and lettuce for new gardeners.</p>
        </article>
        <article>
            <h3>Sustainable Gardening Tips</h3>
            <p>Learn how to reduce waste and use organic methods in your garden.</p>
        </article>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <input type="text" placeholder="Name" required>
            <input type="email" placeholder="Email" required>
            <textarea placeholder="Message" required></textarea>
            <button type="submit">Send</button>
        </form>
        <p>Address: 123 Garden Lane, Green City, USA | Phone: (123) 456-7890 | Email: info@greenthumbseeds.com</p>
    </section>

    <!-- Cart Section -->
    <section id="cart" class="section">
        <h2>Your Cart</h2>
        <ul id="cart-items"></ul>
        <p>Total: $<span id="cart-total">0.00</span></p>
        <!-- Placeholder for PayPal Checkout - Replace with your actual PayPal button code -->
        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
            <input type="hidden" name="cmd" value="_xclick">
            <input type="hidden" name="business" value="your-paypal-email@example.com"> <!-- Replace with your PayPal email -->
            <input type="hidden" name="item_name" value="Seed Order">
            <input type="hidden" name="amount" value="0.00" id="paypal-amount"> <!-- Updated by JS -->
            <input type="hidden" name="currency_code" value="USD">
            <button type="submit">Checkout with PayPal</button>
        </form>
        <p>To enable real payments, sign up at paypal.com, create a 'Buy Now' button, and replace the form above with your generated code. For dynamic amounts, use PayPal's API (requires backend).</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 GreenThumb Seeds. All rights reserved. | <a href="#privacy" style="color:white;">Privacy Policy</a></p>
    </footer>

    <script>
        // Enhanced JS: Cart functionality with localStorage
        let cart = JSON.parse(localStorage.getItem('cart')) || [];

        function updateCart() {
            const cartItems = document.getElementById('cart-items');
            const cartTotal = document.getElementById('cart-total');
            const cartCount = document.getElementById('cart-count');
            const paypalAmount = document.getElementById('paypal-amount');
            cartItems.innerHTML = '';
            let total = 0;
            cart.forEach((item, index) => {
                const li = document.createElement('li');
                li.innerHTML = `${item.name} - $${item.price} <button onclick="removeFromCart(${index})">Remove</button>`;
                cartItems.appendChild(li);
                total += parseFloat(item.price);
            });
            cartTotal.textContent = total.toFixed(2);
            paypalAmount.value = total.toFixed(2);
            cartCount.textContent = cart.length;
            localStorage.setItem('cart', JSON.stringify(cart));
        }

        function addToCart(name, price) {
            cart.push({ name, price });
            updateCart();
            alert(`${name} added to cart!`);
        }

        function removeFromCart(index) {
            cart.splice(index, 1);
            updateCart();
        }

        document.querySelectorAll('.add-to-cart').forEach(button => {
            button.addEventListener('click', (e) => {
                const product = e.target.closest('.product');
                const name = product.dataset.name;
                const price = product.dataset.price;
                addToCart(name, price);
            });
        });

        // Newsletter and Contact Form (placeholders - alerts for demo)
        document.getElementById('newsletter-form').addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Subscribed! (Demo)');
        });

        document.getElementById('contact-form').addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Message sent! (Demo)');
        });

        updateCart(); // Load cart on page load
    </script>

</body>
</html>
