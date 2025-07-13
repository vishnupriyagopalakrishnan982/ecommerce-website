# ecommerce-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PetShop E-Commerce</title>
  <link rel="stylesheet" href="style.css"/>
  <script defer src="script.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"/>
</head>
<body>
    <style>
        body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
header {
  display: flex;
  justify-content: space-between;
  padding: 1rem 2rem;
  background-color: #ff6f00;
  color: white;
}
nav a {
  margin: 0 10px;
  color: white;
  text-decoration: none;
}
.hero {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: linear-gradient(to right, #ff9a00, #ffd000);
  padding: 2rem;
}
.hero-text h1 span {
  color: #d60000;
}
.hero img {
  max-width: 300px;
}
.categories, .products {
  padding: 2rem;
  text-align: center;
}
.category-grid, .product-grid {
  display: flex;
  justify-content: center;
  gap: 2rem;
  flex-wrap: wrap;
}
.catogeries img,produt img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
footer {
  background-color: #222;
  color: white;
  padding: 1rem;
  text-align: center;
}
.footer-icons i {
  margin: 0 10px;
}
    </style>
  <header>
    <div class="logo">PetShop</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Shop</a>
      <a href="#">Categories</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-text">
      <h1>High Quality <span>Pet Food</span></h1>
      <p>Up to 40% off today!</p>
      <button>Shop Now</button>
    </div>
    <img src="WhatsApp Image 2025-06-21 at 08.14.21_60d67031.jpg" alt="Pet Food">
  </section>

  <section class="categories">
    <h2>Top Categories</h2>
    <div class="category-grid">
      <div class="category"><img src="WhatsApp Image 2025-06-21 at 08.10.13_16e842f9.jpg"><p>Cat Food</p></div>
      <div class="category"><img src="WhatsApp Image 2025-06-21 at 08.14.20_71f8861c.jpg"><p>Cat Toys</p></div>
      <div class="category"><img src="WhatsApp Image 2025-06-21 at 08.14.21_e3faf373.jpg"><p>Dog Toys</p></div>
      <div class="category"><img src="WhatsApp Image 2025-06-21 at 08.18.58_7dba8906.jpg"><p>Supplements</p></div>
    </div>
  </section>

  <section class="products">
    <h2>Best Sellers</h2>
    <div class="product-grid">
      <div class="product">
        <img src="WhatsApp Image 2025-06-21 at 08.22.40_59a31c90.jpg" />
        <h3>Pedigree Dog Food</h3>
        <p>$500</p>
        <button>Add to Cart</button>
      </div>
      <!-- More products... -->
    </div>
  </section>
  <script>
    document.querySelectorAll("button").forEach(btn => {
  btn.addEventListener("click", () => {
    alert("Item added to cart!");
  });
});

  </script>

  <footer>
    <div class="footer-icons">
      <i class="fas fa-shipping-fast"></i> Free Delivery
      <i class="fas fa-shield-alt"></i> Secure Payment
      <i class="fas fa-phone"></i> 24/7 Support
    </div>
    <p>&copy; 2025 PetShop. All rights reserved.</p>
  </footer>
</body>
</html>





