<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ShopNow - Online Store</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- Navigation -->
  <nav>
    <div class="logo">🛍️ Shopping Webpage</div>
    <ul>
      <li>Home</li>
      <li>Products</li>
      <li>About</li>
      <li>Contact</li>
    </ul>
  </nav>
  <!-- Hero Section -->
  <section class="hero">
    <h1>Welcome to ShopNow</h1>
    <p>Your one-stop online shopping destination</p>
  </section>
  <!--product Section -->
  <section class="products">
    <div class="product">
      <img src="s.webp" alt="Product 1">
      <h3>Bluetooth Speaker</h3>
      <p class="price">Rs.1,499</p>
      <button>Add to Cart</button>
    </div>
<div class="product">
      <img src="watch.webp" alt="Product 2">
      <h3>Smart Watch</h3>
      <p class="price">Rs.2,999</p>
      <button>Add to Cart</button>
    </div>
 <div class="product">
      <img src="backpack.webp" alt="Product 3">
      <h3>Backpack</h3>
      <p class="price">Rs.899</p>
      <button>Add to Cart</button>
    </div>
 <div class="product">
      <img src="earphone.jpg" alt="Product 4">
      <h3>Wireless Earbuds</h3>
      <p class="price">Rs.1,199</p>
      <button>Add to Cart</button>
    </div>
  </section>
 <!-- Footer -->
  <footer>
    &copy; 2025 ShopNow. All rights reserved.
  </footer>
</body>
</html>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
/* Body */
body {
  font-family: Arial, sans-serif;
  background-color: #f2f2f2;
  color: #333;
}
/* Navigation */
nav {
  background-color: #3CACAE;
  color: white;
  padding: 15px 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.logo {
  font-size: 1.8rem;
  font-weight: bold;
}
nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}
nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: 500;
}
/* Hero Section */
.hero {
  background-color:#C8F4F9;
  text-align: center;
  padding: 40px 20px;
}
.hero h1 {
  font-size: 2rem;
  margin-bottom: 10px;
}
.hero p {
  font-size: 1.1rem;
}
/* Product Grid */
.products {
  background-color:#E5DDC8;
  display: flex;
  justify-content: center;
  padding: 40px 20px;
  gap: 30px;
}
.product {
  background-color: #EEEDE7;
  border-radius: 10px;
  width: 250px;
  padding: 15px;
  text-align: center;
}
.product img {
  width: 100%;
  border-radius: 8px;
}
.product h3 {
  margin: 10px 0 5px;
}
.price {
  color: green;
  font-weight: bold;
  margin-bottom: 10px;
}
button {
  padding: 10px 15px;
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 5px;
}
/* Footer */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
}

