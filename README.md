<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bajeko Cake</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #fff8f0; }
    header { background: #f4c27a; padding: 20px; text-align: center; }
    header h1 { margin: 0; font-size: 2.5rem; }
    nav { background: #f7d9a6; padding: 10px; text-align: center; }
    nav a { margin: 0 15px; text-decoration: none; color: #5a3e1b; font-weight: bold; }
    .hero { background: url('[https://images.unsplash.com/photo-1519861531473-9200262188bf?](https://lh3.googleusercontent.com/a-/ALV-UjVuCJz0DA18xMWEdWwypD2S8gV9R8qObHeQe6hm7Kd2ovyiXv0_=s265-w265-h265)auto=format&fit=crop&w=1500&q=80') center/cover; height: 300px; display: flex; align-items: center; justify-content: center; color: white; font-size: 2rem; text-shadow: 2px 2px 5px #000; }
    .section { padding: 40px; text-align: center; }
    .products { display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; }
    .product-card { background: white; padding: 20px; border-radius: 10px; width: 250px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    .product-card img { width: 100%; border-radius: 10px; }
    footer { background: #5a3e1b; color: white; text-align: center; padding: 20px; margin-top: 40px; }
  </style>
</head>
<body>
  <header>
    <h1>Bajeko Cake</h1>
    <p>Fresh. Delicious. Homemade.</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero" id="home">Sweetness in Every Bite</div>

  <section class="section" id="products">
    <h2>Our Best Sellers</h2>
    <div class="products">
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1608198093002-ad4e005484d7?auto=format&fit=crop&w=800&q=80" alt="Cake" />
        <h3>Chocolate Delight</h3>
        <p>Rich and moist chocolate cake topped with creamy frosting.</p>
      </div>
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1542826438-bd32f43d626f?auto=format&fit=crop&w=800&q=80" alt="Croissant" />
        <h3>Butter Croissant</h3>
        <p>Flaky, buttery, and baked to golden perfection.</p>
      </div>
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1587653915936-9dbabeb8d7d2?auto=format&fit=crop&w=800&q=80" alt="Cupcake" />
        <h3>Vanilla Cupcake</h3>
        <p>Soft vanilla cake topped with silky smooth icing.</p>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>Email: bajekocake@gmail.com</p>
    <p>Phone: +977-9867221301</p>
  </section>

  <footer>
    <p>&copy; 2025 Bajeko Cake. All Rights Reserved.</p>
  </footer>
</body>
</html>
