# index.html
&lt;!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FreshCuts Barber Shop</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
    }

    header {
      background-color: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background: #333;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      padding: 60px;
      text-align: center;
      background: #222;
      color: white;
    }

    .container {
      padding: 20px;
    }

    .services {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }

    .card {
      background: white;
      padding: 20px;
      flex: 1;
      min-width: 200px;
      border-radius: 8px;
    }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }

    button {
      background: #ff9800;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
      font-weight: bold;
    }
  </style>
</head>
<body>
<header>
  <h1>FreshCuts Barber Shop</h1>
  <p>Your Style, Our Passion</p>
</header>
<nav>
  <a href="#">Home</a>
  <a href="#">Services</a>
  <a href="#">Contact</a>
</nav>
<section class="hero">
  <h2>Look Sharp. Feel Confident.</h2>
  <p>Professional haircuts at affordable prices</p>
  <button onclick="alert('Call us at 07123 456789')">Book Now</button>
</section>
<div class="container">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">
      <h3>Haircut</h3>
      <p>Clean and stylish cuts tailored to you.</p>
    </div>
<div class="card">
  <h3>Beard Trim</h3>
  <p>Sharp beard shaping and grooming.</p>
</div>

<div class="card">
  <h3>Full Grooming</h3>
  <p>Complete haircut and beard combo.</p>
</div><div class="container">
  <h2>Contact Us</h2>
  <p>📍 London</p>
  <p>📞 07123 456789</p>
  <p>📧 info@freshcuts.com</p>
</div>
<footer>
  <p>© 2026 FreshCuts Barber Shop</p>
</footer>
</body>
</html>
