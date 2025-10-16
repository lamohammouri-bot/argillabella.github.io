# argillabella.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Argilla Bella - Handmade Jewelry Trays</title>
<style>
  body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: #e0f7fa;
    color: #333;
  }

  /* Header */
  header {
    background: linear-gradient(135deg, #80deea, #4dd0e1);
    color: white;
    text-align: center;
    padding: 70px 20px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }
  header h1 {
    margin: 0;
    font-size: 3.2em;
    letter-spacing: 2px;
  }
  header p {
    margin-top: 10px;
    font-size: 1.3em;
  }

  /* Navigation */
  nav {
    background: #4dd0e1;
    display: flex;
    justify-content: center;
    padding: 15px;
    gap: 30px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }
  nav a {
    text-decoration: none;
    color: white;
    font-weight: bold;
    transition: 0.3s;
  }
  nav a:hover {
    color: #e0f7fa;
  }

  /* Hero Section */
  .hero {
    background: url('https://images.unsplash.com/photo-1618232760751-4a537c9739a5?auto=format&fit=crop&w=1200&q=80') center/cover no-repeat;
    color: white;
    text-align: center;
    padding: 140px 20px;
    font-size: 2em;
    text-shadow: 0 3px 10px rgba(0,0,0,0.4);
    border-radius: 10px;
    margin: 20px;
    transition: transform 0.3s;
  }
  .hero:hover {
    transform: scale(1.02);
  }
  .hero h2 {
    animation: fadeIn 2s ease-in-out;
  }

  /* Products Section */
  .products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    padding: 50px 20px;
  }
  .product {
    background: white;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    overflow: hidden;
    transition: transform 0.3s, box-shadow 0.3s;
    text-align: center;
  }
  .product:hover {
    transform: scale(1.05);
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
  }
  .product img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    transition: transform 0.3s;
  }
  .product img:hover {
    transform: scale(1.05);
  }
  .product h3 {
    margin: 15px 0 5px;
  }
  .product p {
    margin-bottom: 10px;
    color: #00796b;
    font-weight: bold;
  }
  .product button {
    background: linear-gradient(135deg, #00bcd4, #0097a7);
    color: white;
    border: none;
    padding: 12px 25px;
    margin-bottom: 15px;
    border-radius: 8px;
    cursor: pointer;
    font-weight: bold;
    transition: 0.3s;
  }
  .product button:hover {
    background: linear-gradient(135deg, #0097a7, #00796b);
    transform: scale(1.05);
  }

  /* Footer */
  footer {
    background: #4dd0e1;
    color: white;
    text-align: center;
    padding: 25px;
    font-size: 1em;
    margin-top: 30px;
  }

  /* Animations */
  @keyframes fadeIn {
    from {opacity: 0;}
    to {opacity: 1;}
  }
</style>
</head>
<body>

<header>
  <h1>Argilla Bella</h1>
  <p>Handmade Jewelry Trays ✨ Elegant & Unique</p>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#">Shop</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>

<section class="hero">
  <h2>Discover Unique Handmade Trays</h2>
</section>

<section class="products">
  <div class="product">
    <img src="https://i.pinimg.com/564x/0f/39/9b/0f399b5fa6d83e01fa17b7bfb2ff41d6.jpg" alt="Pink Tray">
    <h3>Elegant Pink Tray</h3>
    <p>15 JD</p>
    <button onclick="window.open('https://wa.me/962XXXXXXXXX')">Buy Now</button>
  </div>
  <div class="product">
    <img src="https://i.pinimg.com/564x/3d/9c/9f/3d9c9f0f26d5e5a3c5b1b8b623b1bb11.jpg" alt="Marble Tray">
    <h3>Marble White Tray</h3>
    <p>18 JD</p>
    <button onclick="window.open('https://wa.me/962XXXXXXXXX')">Buy Now</button>
  </div>
  <div class="product">
    <img src="https://i.pinimg.com/564x/5b/7c/4e/5b7c4efb4b65e3a4b3e7f7c5b1b3a1ef.jpg" alt="Minimalist Tray">
    <h3>Minimalist Black Tray</h3>
    <p>17 JD</p>
    <button onclick="window.open('https://wa.me/962XXXXXXXXX')">Buy Now</button>
  </div>
</section>

<footer>
  <p>© 2025 Argilla Bella | Follow us on Instagram @ArgillaBella</p>
</footer>

</body>
</html>
