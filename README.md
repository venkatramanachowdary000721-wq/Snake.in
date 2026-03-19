# Snake.in
Snake game
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ram Babu Builders</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
}

/* Header */
header {
    background: #1a1a1a;
    color: white;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    color: #00c3ff;
}

nav a {
    color: white;
    margin-left: 20px;
    text-decoration: none;
}

nav a:hover {
    color: #00c3ff;
}

/* Hero */
.hero {
    height: 90vh;
    background: url('https://images.unsplash.com/photo-1503387762-592deb58ef4e') no-repeat center/cover;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}

.hero h2 {
    font-size: 45px;
}

.btn {
    background: #00c3ff;
    padding: 10px 20px;
    color: black;
    text-decoration: none;
    margin-top: 10px;
    display: inline-block;
}

/* Sections */
section {
    padding: 50px;
    text-align: center;
}

/* Services */
.services {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.card {
    background: #f4f4f4;
    margin: 15px;
    padding: 20px;
    width: 260px;
    border-radius: 10px;
}

/* Contact */
.contact p {
    margin: 10px 0;<h3>Our Location</h3>
<iframe 
    src="https://www.google.com/maps?q=Ameerpet,Hyderabad&output=embed"
    width="100%" 
    height="300" 
    style="border:0;">
</iframe>
}

/* Booking */
.booking {
    background: #f9f9f9;
    padding: 40px;
}

.booking input, .booking button {
    padding: 10px;
    margin: 10px;
    width: 250px;
}

.booking button {
    background: #00c3ff;
    border: none;
    cursor: pointer;
}

/* Footer */
footer {
    background: #1a1a1a;
    color: white;
    text-align: center;
    padding: 15px;
}
</style>

</head>
<body>

<!-- Header -->
<header>
    <h1>Ram Babu Builders</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#booking">Book Slot</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- Hero -->
<section class="hero" id="home">
    <div>
        <h2>Building Your Dream Spaces</h2>
        <p>Houses | Apartments | Commercial Buildings</p>
        <a href="#booking" class="btn">Book Consultation</a>
    </div>
</section>

<!-- Services -->
<section id="services">
    <h2>Our Services</h2>
    <p>Serving across Andhra Pradesh & Telangana</p>
    <div class="services">
        <div class="card">
            <h3>House Construction</h3>
            <p>We build modern and durable homes tailored to your needs.</p>
        </div>
        <div class="card">
            <h3>Apartments</h3>
            <p>High-quality apartment construction with modern designs.</p>
        </div>
        <div class="card">
            <h3>Commercial Buildings</h3>
            <p>Offices, shops, and commercial complexes with top quality.</p>
        </div>
    </div>
</section>

<!-- Booking -->
<section id="booking" class="booking">
    <h2>Book a 1-Hour Consultation</h2>
    <p>Available between 11 AM – 1 PM</p>
    <form>
        <input type="text" placeholder="Your Name" required><br>
        <input type="tel" placeholder="Phone Number" required><br>
        <input type="date" required><br>
        <button type="submit">Book Now</button>
    </form>
</section>

<!-- Contact -->
<section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> +91 78423 34392</p>
    <p><strong>Location:</strong> Parvath Nagar</p>
    <p><strong>Office Timings:</strong> 8 AM – 8 PM</p>
    <p><strong>Instagram:</strong> @they_call_me_karna</p>
</section>

<!-- Footer -->
<footer>
    <p>© 2026 Ram Babu Builders | All Rights Reserved</p>
</footer>
<a href="https://wa.me/917842334392" target="_blank" class="whatsapp-btn">💬</a>

<style>
.whatsapp-btn {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25D366;
    color: white;
    font-size: 25px;
    padding: 15px;
    border-radius: 50%;
    text-decoration: none;
}
</style>
</body>
</html>
<section id="gallery">
<h2>Our Work</h2>

<div class="gallery">
    <img src="https://via.placeholder.com/200">
    <img src="https://via.placeholder.com/200">
    <img src="https://via.placeholder.com/200">
</div>

<style>
.gallery {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}
.gallery img {
    margin: 10px;
    width: 200px;
    border-radius: 10px;
}
</style>

</section>
<section id="booking">
<h2>Book a Consultation</h2>

<form>
<input type="text" placeholder="Your Name" required><br>
<input type="tel" placeholder="Phone Number" required><br>
<input type="date" required><br>
<input type="time" required><br>

<button type="submit">Book Now</button>
</form>
</section>
<section id="pricing">
<h2>Our Pricing</h2>

<div class="pricing">
    <div class="plan">
        <h3>Basic</h3>
        <p>₹3000</p>
        <p>Simple Website</p>
    </div>

    <div class="plan">
        <h3>Standard</h3>
        <p>₹6000</p>
        <p>Website + Gallery + Contact</p>
    </div>

    <div class="plan">
        <h3>Premium</h3>
        <p>₹10000</p>
        <p>Full Website + Booking + WhatsApp</p>
    </div>
</div>

<style>
.pricing {
    display: flex;
    justify-content: center;
}
.plan {
    background: #f4f4f4;
    margin: 10px;
    padding: 20px;
    width: 200px;
    border-radius: 10px;
}
</style>

</section>
