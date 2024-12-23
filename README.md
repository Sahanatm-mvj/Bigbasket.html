<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BigBasket - Online Grocery Store</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <img src="logo.png" alt="BigBasket Logo">
        </div>
        <nav>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/shop">Shop</a></li>
                <li><a href="/offers">Offers</a></li>
                <li><a href="/about">About Us</a></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </nav>
        <div class="user-options">
            <a href="/cart"><img src="cart-icon.png" alt="Cart"> Cart</a>
            <a href="/profile">Profile</a>
        </div>
    </header>

    <!-- Main Banner Section -->
    <section class="banner">
        <img src="banner-image.jpg" alt="Banner Image">
        <div class="banner-text">
            <h1>Fresh Groceries Delivered to Your Door</h1>
            <button>Shop Now</button>
        </div>
    </section>

    <!-- Featured Categories Section -->
    <section class="categories">
        <h2>Shop by Category</h2>
        <div class="category-list">
            <div class="category-item">
                <img src="fruits-category.jpg" alt="Fruits">
                <h3>Fruits</h3>
            </div>
            <div class="category-item">
                <img src="vegetables-category.jpg" alt="Vegetables">
                <h3>Vegetables</h3>
            </div>
            <div class="category-item">
                <img src="dairy-category.jpg" alt="Dairy">
                <h3>Dairy</h3>
            </div>
            <div class="category-item">
                <img src="snacks-category.jpg" alt="Snacks">
                <h3>Snacks</h3>
            </div>
        </div>
    </section>

    <!-- Featured Products Section -->
    <section class="products">
        <h2>Featured Products</h2>
        <div class="product-list">
            <div class="product-item">
                <img src="apple.jpg" alt="Apple">
                <h3>Fresh Apples</h3>
                <p>$2.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product-item">
                <img src="milk.jpg" alt="Milk">
                <h3>Organic Milk</h3>
                <p>$1.49</p>
                <button>Add to Cart</button>
            </div>
            <div class="product-item">
                <img src="chips.jpg" alt="Chips">
                <h3>Potato Chips</h3>
                <p>$1.29</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="footer-links">
            <ul>
                <li><a href="/terms">Terms & Conditions</a></li>
                <li><a href="/privacy">Privacy Policy</a></li>
                <li><a href="/faq">FAQ</a></li>
            </ul>
        </div>
        <p>&copy; 2024 BigBasket. All Rights Reserved.</p>
    </footer>
</body>
</html>

