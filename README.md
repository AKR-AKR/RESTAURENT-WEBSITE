# RESTAURENT-WEBSITE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Restaurant Name</div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to Restaurant Name</h1>
        <p>Enjoy our delicious dishes in a cozy atmosphere.</p>
        <a href="#menu" class="cta-button">View Menu</a>
    </section>

    <section id="menu" class="menu">
        <h2>Menu</h2>
        <!-- Add menu items here -->
    </section>

    <section class="about">
        <h2>About Us</h2>
        <p>Learn about our history and commitment to quality.</p>
    </section>

    <section class="contact">
        <h2>Contact Us</h2>
        <p>Get in touch with us to make a reservation or for any inquiries.</p>
        <!-- Add contact form or contact details here -->
    </section>

    <footer>
        <p>&copy; 2023 Restaurant Name</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* styles.css */

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}

.nav-links li a {
    text-decoration: none;
    color: white;
}

.hero {
    background-image: url('restaurant-image.jpg');
    background-size: cover;
    text-align: center;
    padding: 100px 0;
    color: white;
}

.cta-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #ff6600;
    color: white;
    text-decoration: none;
    border: none;
    border-radius: 5px;
    font-weight: bold;
    margin-top: 20px;
}

.menu, .about, .contact {
    padding: 40px 0;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}
// script.js

// Example: Show an alert when the "View Menu" button is clicked
document.querySelector('.cta-button').addEventListener('click', function() {
    alert('Menu page coming soon!');
});
