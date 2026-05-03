# Nayak.github.io
(My first HTML project created for learning purposes.)
myshop.html
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shankar's Deal Store</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; background-color: #f0f2f5; margin: 0; padding: 0; }
        header { background: #232f3e; color: white; padding: 20px; text-align: center; }
        .nav-menu { background: #37475a; padding: 10px; text-align: center; }
        .nav-menu a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        .container { padding: 20px; max-width: 1000px; margin: auto; }
        .section-title { border-left: 5px solid #ff9900; padding-left: 10px; margin: 20px 0; color: #333; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .card { background: white; padding: 15px; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }
        .card h3 { font-size: 18px; margin: 10px 0; }
        .price { color: #B12704; font-size: 20px; font-weight: bold; }
        .buy-btn { display: block; background: #ffd814; color: #0f1111; padding: 10px; margin-top: 10px; text-decoration: none; border-radius: 20px; font-size: 14px; }
    </style>
</head>
<body>
<header>
    <h1>Super Deals Store 🛍️</h1>
    <p>Gadgets | Fashion | Home Appliances</p>
</header>
<div class="nav-menu">
    <a href="#gadgets">Gadgets</a>
    <a href="#fashion">Fashion</a>
    <a href="#home">Home</a>
</div>
<div class="container">
    
    <h2 id="gadgets" class="section-title">Latest Gadgets & Tech</h2>
    <div class="grid">
        <div class="card">
            <h3>Best Wireless Earbuds</h3>
            <p class="price">₹1,499</p>
            <a href="https://fktr.in/Pby9czj" class="buy-btn">View on Amazon</a>
        </div>
        <div class="card">
            <h3>Fast Charging Powerbank</h3>
            <p class="price">₹999</p>
            <a href="https://fktr.in/nLHSPeX" class="buy-btn">View Deal</a>
        </div>
    </div>
    <h2 id="fashion" class="section-title">Trending Fashion</h2>
    <div class="grid">
        <div class="card">
            <h3>Stylish Sneakers</h3>
            <p class="price">70% OFF</p>
            <a href="https://myntr.it/CIA0NF2" class="buy-btn">Get Discount</a>
        </div>
    </div>
    <h2 id="home" class="section-title">Home & Kitchen</h2>
    <div class="grid">
        <div class="card">
            <h3>Smart BLDC Fan</h3>
            <p class="price">Save ₹500</p>
            <a href="Crompton EN Hyperjet 48 5Z BLDC Technology Remote Control with 2 Year Warranty Energy Saving 1200 mm Ceiling Fan Price in India - Buy Crompton EN Hyperjet 48 5Z BLDC Technology Remote Control with 2 Year Warranty Energy Saving 1200 mm Ceiling Fan online at Flipkart.com https://share.google/7cwyHbX1UHo7DjiRi" class="buy-btn">Buy Now</a>
        </div>
    </div>
</div>
</body>
</html>
