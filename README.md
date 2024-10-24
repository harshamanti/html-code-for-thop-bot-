<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FreshGrain & Veggies Delivery</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header class="navbar">
        <h1>FreshGrain & Veggies</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#locations">Stores</a>
            <a href="#contact">Contact Us</a>
        </nav>
    </header>

    <section id="home" class="hero">
        <h2>Your Grains & Veggies, Delivered Fast</h2>
        <p>Order fresh grains, vegetables, and groceries. Fast delivery from your nearest store!</p>
        <button onclick="scrollToOrderForm()">Place Your Order</button>
    </section>

    <section id="products" class="products">
        <h2>Our Products</h2>
        <div class="product-list">
            <div class="product">
                <h3>Rice</h3>
                <p>Fresh from the fields.</p>
            </div>
            <div class="product">
                <h3>Wheat</h3>
                <p>Whole grains and flour options.</p>
            </div>
            <div class="product">
                <h3>Maize</h3>
                <p>High-quality maize for every use.</p>
            </div>
            <div class="product">
                <h3>Vegetables</h3>
                <p>Locally sourced, fresh vegetables.</p>
            </div>
        </div>
    </section>

    <section id="locations" class="locations">
        <h2>Our Stores</h2>
        <div class="store-list">
            <div class="store">
                <h3>Store 1</h3>
                <p>Location: City Center</p>
            </div>
            <div class="store">
                <h3>Store 2</h3>
                <p>Location: Green Park</p>
            </div>
            <div class="store">
                <h3>Store 3</h3>
                <p>Location: Riverside Plaza</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form id="orderForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="product">Select Product:</label>
            <select id="product" name="product">
                <option value="rice">Rice</option>
                <option value="wheat">Wheat</option>
                <option value="maize">Maize</option>
                <option value="veggies">Vegetables</option>
            </select>

            <label for="quantity">Quantity (kg):</label>
            <input type="number" id="quantity" name="quantity" required>

            <label for="address">Delivery Address:</label>
            <textarea id="address" name="address" required></textarea>

            <button type="submit">Place Order</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 FreshGrain & Veggies. All rights reserved.</p>
    </footer>
</body>
</html>