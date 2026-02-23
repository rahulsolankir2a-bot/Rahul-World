# Rahul-World
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon Clone | Shop Online</title>
    <style>
        /* CSS Styles */
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
        body { background-color: #eaeded; }

        /* Navbar */
        header { background-color: #131921; color: white; padding: 10px 20px; display: flex; align-items: center; }
        .logo { font-size: 24px; font-weight: bold; color: #ff9900; margin-right: 20px; text-decoration: none; }
        .search-container { flex-grow: 1; display: flex; height: 40px; }
        .search-input { width: 100%; border: none; padding: 10px; border-radius: 4px 0 0 4px; outline: none; }
        .search-btn { background-color: #febd69; border: none; width: 45px; border-radius: 0 4px 4px 0; cursor: pointer; font-weight: bold; }
        .nav-links { display: flex; gap: 20px; margin-left: 20px; font-size: 14px; }

        /* Hero Section */
        .hero { 
            height: 300px; 
            background: linear-gradient(to bottom, rgba(0,0,0,0), #eaeded), url('https://images.unsplash.com/photo-1607082348824-0a96f2a4b9da?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
        }

        /* Product Grid */
        .container { max-width: 1200px; margin: -100px auto 20px auto; display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; padding: 0 20px; }
        .card { background: white; padding: 20px; border-radius: 4px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); display: flex; flex-direction: column; }
        .card h3 { font-size: 18px; margin-bottom: 10px; color: #0f1111; }
        .product-img { width: 100%; height: 200px; object-fit: contain; margin-bottom: 15px; }
        .price { font-size: 20px; font-weight: bold; margin-bottom: 10px; }
        .buy-btn { background-color: #ffd814; border: 1px solid #fcd200; border-radius: 20px; padding: 8px; cursor: pointer; font-size: 13px; }
        .buy-btn:hover { background-color: #f7ca00; }
    </style>
</head>
<body>

    <header>
        <a href="#" class="logo">amazon.clone</a>
        <div class="search-container">
            <input type="text" class="search-input" placeholder="Search Amazon">
            <button class="search-btn">🔍</button>
        </div>
        <div class="nav-links">
            <div>Hello, Sign in<br><b>Account & Lists</b></div>
            <div>Returns<br><b>& Orders</b></div>
            <div><b>🛒 Cart</b></div>
        </div>
    </header>

    <div class="hero"></div>

    <div class="container">
        <div class="card">
            <h3>Wireless Headphones</h3>
            <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?w=400" class="product-img" alt="Headphones">
            <p class="price">$199.99</p>
            <button class="buy-btn">Add to Cart</button>
        </div>

        <div class="card">
            <h3>Smart Watch Series 9</h3>
            <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?w=400" class="product-img" alt="Watch">
            <p class="price">$349.00</p>
            <button class="buy-btn">Add to Cart</button>
        </div>

        <div class="card">
            <h3>Leather Sneakers</h3>
            <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=400" class="product-img" alt="Shoes">
            <p class="price">$85.50</p>
            <button class="buy-btn">Add to Cart</button>
        </div>

        <div class="card">
            <h3>Gaming Laptop</h3>
            <img src="https://images.unsplash.com/photo-1603302576837-37561b2e2302?w=400" class="product-img" alt="Laptop">
            <p class="price">$1,299.00</p>
            <button class="buy-btn">Add to Cart</button>
        </div>
    </div>

</body>
</html>
