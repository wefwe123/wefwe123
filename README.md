<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Eskape - Home</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#shop">Shop</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#checkout">Checkout</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <!-- Main Hero Section -->
    <section class="hero">
      <div class="hero-content">
        <div class="image-section">
          <img id="stander" src="IMG_9790.webp" alt="Stander with Oversized Shirts">
        </div>
        <div class="model-section">
          <img src="https://via.placeholder.com/400x600" alt="Male Model" id="model">
          <h1>ESKAPE</h1>
        </div>
      </div>
    </section>

    <!-- Shop Section -->
    <section id="shop" class="products">
      <h2>Shop by Category</h2>
      <div class="categories">
        <div class="category">
          <h3>Men</h3>
          <a href="#shop-men">Explore</a>
        </div>
        <div class="category">
          <h3>Women</h3>
          <a href="#shop-women">Explore</a>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
      <h2>About Us</h2>
      <p>
        ESKAPE is an oversized clothing brand inspired by freedom, uniqueness, and rave culture. Discover more about our journey.
      </p>
    </section>
  </main>

  <footer>
    <p>&copy; 2024 ESKAPE. All Rights Reserved.</p>
  </footer>
</body>
</html>
/* General Styles */
body {
  margin: 0;
  font-family: 'Playfair Display', serif;
  background-color: #000;
  color: #d35400; /* Dark Orange */
  line-height: 1.6;
}

header {
  background: #000;
  padding: 1rem;
  text-align: center;
}

.nav-links {
  list-style: none;
  padding: 0;
}

.nav-links li {
  display: inline;
  margin: 0 15px;
}

.nav-links a {
  text-decoration: none;
  color: #d35400;
  font-style: italic;
}

.hero {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background: #000;
}

.hero-content {
  display: flex;
  align-items: center;
  justify-content: space-around;
  max-width: 90%;
  margin: auto;
}

.image-section img,
.model-section img {
  width: 40%;
  border-radius: 10px;
}

.model-section h1 {
  color: #d35400;
  font-style: italic;
  text-align: center;
  margin-top: 10px;
}

.products, .about {
  padding: 2rem;
  text-align: center;
}

.categories {
  display: flex;
  justify-content: space-around;
  margin-top: 1rem;
}

.category h3 {
  font-style: italic;
}

footer {
  text-align: center;
  padding: 1rem;
  background: #111;
  color: #d35400;
}


<!---
wefwe123/wefwe123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
