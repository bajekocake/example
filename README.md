<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bajeko Cake</title>
  <style>
    body { font-family: 'Poppins', sans-serif; margin: 0; padding: 0; background: #fff7f2; }
    header { background: linear-gradient(135deg, #f7b16a, #e98e3a); padding: 30px; text-align: center; color: white; }
    header h1 { margin: 0; font-size: 3rem; }
    nav { background: #f2dcc0; padding: 15px; text-align: center; position: sticky; top: 0; }
    nav a { margin: 0 18px; text-decoration: none; color: #5a3e1b; font-weight: bold; }

    .slider { position: relative; width: 100%; max-height: 400px; overflow: hidden; }
    .slides { display: flex; width: 300%; animation: slide 12s infinite; }
    .slides img { width: 100%; height: 400px; object-fit: cover; }
    .auth { display: flex; justify-content: center; gap: 20px; padding: 20px; }
    .auth button { padding: 10px 20px; background: #ff7eb9; border: none; color: white; cursor: pointer; border-radius: 5px; }
    .modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.6); justify-content: center; align-items: center; }
    .modal-content { background: white; padding: 20px; border-radius: 8px; width: 300px; }
    .modal-content input { width: 100%; padding: 8px; margin: 10px 0; }
    @keyframes slide {
      0% { transform: translateX(0); }
      33% { transform: translateX(-100%); }
      66% { transform: translateX(-200%); }
      100% { transform: translateX(0); }
    }
    
    

    .section { padding: 5px; text-align: center; }
    h2 { font-size: 2.2rem; margin-bottom: 20px; }
    <div class="slider">
    <div class="slides">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/IMG_20250526_101643373.jpg" alt="Cake 1">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/IMG_20250726_114354841.jpg" alt="Cake 2">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/images%20(7).jpg" 
      alt="Cake 3">
    </div>
  </div>
  .auth { display: flex; justify-content: center; gap: 20px; padding: 20px; }
    .auth button { padding: 10px 20px; background: #ff7eb9; border: none; color: white; cursor: pointer; border-radius: 5px; }
    .modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: #e98e3a; justify-content: center; align-items: center; }
    .modal-content { background: white; padding: 20px; border-radius: 8px; width: 300px; }
    .modal-content input { width: 100%; padding: 8px; margin: 10px 0; }
    
    .category-buttons { display: flex; justify-content: center; gap: 15px; flex-wrap: wrap; margin-bottom: 50px; }
    .category-buttons button {
      padding: 19px 16px;
      border: none;
      background: #e98e3a;
      color: white;
      font-size: 10pxpx;
      border-radius: 35px;
      cursor: pointer;
    }

    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 25px; margin-top: 20px; }
    .product-card { background: white; padding: 20px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.15); }
    .product-card img { width: 80%; border-radius: 0px; height: 400px; object-fit: contain; }
    .product-card h3 { margin: 15px 0 5px; }
    .btn-row { display: flex; justify-content: space-between; margin-top: 10px; }
    .btn {
      padding: 10px 15px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-weight: bold;
    }
    .cart-btn { background: #f4a259; color: white; }
    .wish-btn { background: #ffe3c2; color: #5a3e1b; }

    footer { background: #5a3e1b; color: white; text-align: center; padding: 25px; margin-top: 50px; }
  </style>
</head>
<body>
  <header>
    <h1>Bajeko Cake</h1>
    <div class="slider">
    <div class="slides">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/IMG_20250526_101643373.jpg" alt="Cake 1">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/IMG_20250726_114354841.jpg" alt="Cake 2">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/images%20(7).jpg" alt="Cake 3">
    </div>
  </div>
  <div class="auth">
    <button onclick="openModal('loginModal')">Login</button>
    <button onclick="openModal('signupModal')">Sign Up</button>
  </div>
    
  </header>

  <nav>
    <a href="#home"> Home</a>
    <a href="#products"> Products</a>
    <a href="#contact"> Contact</a>
    <a href="#cart"> Cart 🛒</a>
    <a href="#wishlist"> Wishlist ❤️</a>
    <a href="carrer"> Carrer</a>
  </nav>

  <div class="hero" id="home">Premium Cakes for Every Occasion</div>

  <section class="section" id="products">
    <h2>Shop by Category</h2>

    <div class="category-buttons">
      <button onclick="filterCategory('quick')">Quick Cake</button>
      <button onclick="filterCategory('eggless')">Eggless Cake</button>
      <button onclick="filterCategory('wedding')">Wedding Cake</button>
      <button onclick="filterCategory('cheese')">Cheese Cake</button>
    </div>

    <div class="products" id="product-list">

      <!-- Quick Cake -->
      <div class="product-card" data-category="quick">
        <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/95a33ceb554a695b8f016d2a73526fc3.jpg?auto=format&fit=crop&w=800&q=80" />
        <h3>Quick Chocolate Cake</h3>
        <p>Fast-picked, rich & moist.</p>
        <div class="btn-row">
          <button class="btn cart-btn">Add to Cart</button>
          <button class="btn wish-btn">Wishlist</button>
        </div>
      </div>

      <!-- Eggless Cake -->
      <div class="product-card" data-category="eggless">
        <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/Red-Velvet-Birthday-Cake-scaled.jpeg?auto=format&fit=crop&w=800&q=80" />"
        <h3>Eggless Red Velvet</h3>
        <p>Soft, smooth & completely egg-free.</p>
        <div class="btn-row">
          <button class="btn cart-btn">Add to Cart</button>
          <button class="btn wish-btn">Wishlist</button>
        </div>
      </div>

      <!-- Wedding Cake -->
      <div class="product-card" data-category="wedding">
        <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/royal%20cake.jpg?auto=format&fit=crop&w=800&q=80" />
        <h3>Royal Wedding Cake</h3>
        <p>Elegant multi-tier handcrafted design.</p>
        <div class="btn-row">
          <button class="btn cart-btn">Add to Cart</button>
          <button class="btn wish-btn">Wishlist</button>
        </div>
      </div>

      <!-- Cheese Cake -->
      <div class="product-card" data-category="cheese">
        <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/1200x1200px_Blueberry_Cheesecake.png?auto=format&fit=crop&w=800&q=80" />
        <h3>Classic Cheesecake</h3>
        <p>Creamy, smooth & premium cheese blend.</p>
        <div class="btn-row">
          <button class="btn cart-btn">Add to Cart</button>
          <button class="btn wish-btn">Wishlist</button>
        </div>
      </div>

    </div>
  </section>
   <!-- Login Modal -->
  <div id="loginModal" class="modal">
    <div class="modal-content">
      <h3>Login</h3>
      <input type="text" placeholder="Email" />
      <input type="password" placeholder="Password" />
      <button onclick="closeModal('loginModal')">Login</button>
    </div>
  </div>

  <!-- Signup Modal -->
  <div id="signupModal" class="modal">
    <div class="modal-content">
      <h3>Sign Up</h3>
      <input type="text" placeholder="Full Name" />
      <input type="email" placeholder="Email" />
      <input type="password" placeholder="Password" />
      <button onclick="closeModal('signupModal')">Sign Up</button>
    </div>
  </div>

  <script>
    function openModal(id) {
      document.getElementById(id).style.display = 'flex';
    }
    function closeModal(id) {
      document.getElementById(id).style.display = 'none';
    }
    </script>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>Email: bajekocake@gmail.com</p>
    <p>Phone: +977-9867221301</p>
  </section>

  <footer>
    <head>
<meta charset="UTF-8">
<title>Social Media Buttons</title>

<!-- Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
    .social-buttons {
        display: flex;
        gap: 15px;
    }

    .social-buttons a {
        text-decoration: none;
        font-size: 28px;
        color: white;
        padding: 12px;
        border-radius: 50%;
        display: inline-flex;
        justify-content: center;
        align-items: center;
    }

    .facebook { background: #1877f2; }
    .instagram { background: #e1306c; }
    .twitter { background: #1da1f2; }
    .youtube { background: #ff0000; }
</style>
</head>

<body>

<div class="social-buttons">
    <a href="https://facebook.com/BAJEKOCAKE" class="facebook" target="_blank"><i class="fab fa-facebook-f"></i></a>
    <a href="https://www.instagram.com/baje_ko_cake?igsh=MWJqMmVkdnI5dzl1dQ==" class="instagram" target="_blank"><i class="fab fa-instagram"></i></a>
    </div>

</body>
</html>

    <p>&copy; 2021 Bajeko cake. Crafted with Love.</p>
  </footer>

  <script>
    function filterCategory(category) {
      const cards = document.querySelectorAll('.product-card');
      cards.forEach(card => {
        card.style.display = card.getAttribute('data-category') === category ? 'block' : 'none';
      });
    }
   
  </script>
</body>
</html>







