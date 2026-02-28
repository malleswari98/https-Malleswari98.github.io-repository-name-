<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SmartFit Pro</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>

/* GLOBAL */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* HEADER */
header {
    background: #111;
    color: #fff;
    padding: 20px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav a {
    color: #fff;
    text-decoration: none;
    margin-left: 20px;
    transition: 0.3s;
}

nav a:hover {
    color: #ff6347;
    text-decoration: underline;
}

/* HERO */
.hero {
    background: linear-gradient(to right, #ff6347, #ff8c66);
    color: #fff;
    text-align: center;
    padding: 80px 20px;
}

.hero h2 {
    font-size: 40px;
    margin-bottom: 20px;
}

.hero button {
    padding: 12px 25px;
    border: none;
    background: #fff;
    color: #ff6347;
    font-weight: 600;
    cursor: pointer;
    border-radius: 5px;
    transition: 0.3s;
}

.hero button:hover {
    background-color: #ff6347;
    color: #fff;
}

.hero button:active {
    background-color: #e5533d;
}

.hero button:focus {
    outline: 3px solid #fff;
}

/* =========================
   PRODUCT SECTION
========================= */
.product {
    padding: 60px 20px;
    background: #fff;
}

.product-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    max-width: 1100px;
    margin: auto;
    gap: 40px;
}

.product img {
    width: 350px;
    border-radius: 20px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    transition: 0.3s;
}

.product img:hover {
    transform: scale(1.05);
}

.product-text h2 {
    margin-bottom: 20px;
}

.product-text p {
    margin-bottom: 20px;
}

.product-text button {
    padding: 10px 20px;
    border: none;
    background: #ff6347;
    color: #fff;
    cursor: pointer;
    border-radius: 5px;
    transition: 0.3s;
}

.product-text button:hover {
    background: #e5533d;
}

/* FEATURES */
.features {
    padding: 60px 20px;
    text-align: center;
    background: #f9f9f9;
}

.feature-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 30px;
    margin-top: 40px;
}

.feature-box {
    padding: 20px;
    border-radius: 10px;
    background: #fff;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    transition: 0.3s;
}

.feature-box:hover {
    transform: translateY(-5px);
}

.feature-box i {
    font-size: 40px;
    color: #ff6347;
    margin-bottom: 15px;
}

/* CONTACT */
.contact {
    padding: 60px 20px;
    background: #fff;
}

form {
    max-width: 500px;
    margin: auto;
    display: flex;
    flex-direction: column;
}

form label {
    margin: 10px 0 5px;
    font-weight: 600;
}

form input, form textarea {
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

form input:focus,
form textarea:focus {
    border: 2px solid #ff6347;
    outline: none;
}

form button {
    margin-top: 20px;
    padding: 12px;
    border: none;
    background: #ff6347;
    color: #fff;
    cursor: pointer;
    border-radius: 5px;
}

form button:hover {
    background: #e5533d;
}

/* FOOTER */
footer {
    background: #111;
    color: #fff;
    text-align: center;
    padding: 20px;
}

.social-icons a {
    color: #fff;
    margin: 0 10px;
    font-size: 22px;
    transition: 0.3s;
}

.social-icons a:hover {
    color: #ff6347;
}

/* RESPONSIVE */
@media (max-width: 768px) {

    header {
        flex-direction: column;
        text-align: center;
    }

    .product-container {
        flex-direction: column;
        text-align: center;
    }

    .feature-grid {
        grid-template-columns: 1fr;
    }

    .hero h2 {
        font-size: 28px;
    }
}

</style>
</head>

<body>

<header>
    <h1>SmartFit Pro</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#features">Features</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Track Your Fitness Smarter</h2>
    <p>The ultimate smartwatch to monitor your health and workouts.</p>
    <button>Buy Now</button>
</section>

<!-- NEW PRODUCT IMAGE SECTION -->
<section class="product">
    <div class="product-container">
     
        <div class="product-text">
            <h2>SmartFit Pro Smartwatch</h2>
            <p>Designed for modern fitness enthusiasts, SmartFit Pro helps you track your heart rate, steps, calories, sleep patterns, and more with precision and style.</p>
            <button>Order Now</button>
        </div>
    </div>
</section>

<section class="features" id="features">
    <h2>Product Features</h2>
    <div class="feature-grid">
        <div class="feature-box">
            <i class="fas fa-heartbeat"></i>
            <h3>Heart Rate Monitor</h3>
            <p>24/7 heart tracking support.</p>
        </div>
        <div class="feature-box">
            <i class="fas fa-walking"></i>
            <h3>Activity Tracking</h3>
            <p>Steps, calories & workouts.</p>
        </div>
        <div class="feature-box">
            <i class="fas fa-battery-full"></i>
            <h3>Long Battery</h3>
            <p>Up to 7 days backup.</p>
        </div>
    </div>
</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" required>

        <label for="message">Message:</label>
        <textarea id="message" rows="4"></textarea>

        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <p>© 2026 SmartFit Pro</p>
    <div class="social-icons">
        <a href="#"><i class="fab fa-facebook"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
    </div>
</footer>

</body>
</html>
