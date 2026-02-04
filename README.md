<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Furn w Fekhar</title>
<style>
/* ===== GENERAL STYLES ===== */
body { font-family: Arial, sans-serif; margin: 0; background: #fdf6ed; color: #333; line-height: 1.6; }
header { background: #8B0000; color: white; padding: 15px; text-align: center; position: sticky; top: 0; z-index: 100; }
nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
nav a:hover { color: #FFDAB9; }
section { padding: 60px 20px; }
footer { background: #8B0000; color: white; text-align: center; padding: 20px; }

/* ===== HERO ===== */
.hero { background: #B22222; color: white; text-align: center; padding: 100px 20px; }
.hero h1 { font-size: 3em; margin-bottom: 15px; }
.hero p { font-size: 1.3em; }

/* ===== ABOUT ===== */
.about p { max-width: 700px; margin: 0 auto; font-size: 1.1em; text-align: center; }

/* ===== SERVICES ===== */
.services ul { list-style: none; padding: 0; max-width: 600px; margin: 0 auto; }
.services li { background: #fff; padding: 20px; margin: 10px 0; border-left: 5px solid #B22222; box-shadow: 0 2px 4px rgba(0,0,0,0.1); font-weight: bold; text-align: center; }

/* ===== CONTACT ===== */
.contact p { text-align: center; font-size: 1.1em; margin: 10px 0; }

/* ===== BUTTONS ===== */
button { background: #B22222; color: white; border: none; padding: 12px 25px; margin-top: 15px; font-size: 1em; cursor: pointer; border-radius: 5px; }
button:hover { background: #8B0000; }

/* ===== SMOOTH SCROLL ===== */
html { scroll-behavior: smooth; }

</style>
</head>
<body>

<header>
  <h2>Furn w Fekhar</h2>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home" class="hero">
  <h1>Welcome to Furn w Fekhar</h1>
  <p>Experience traditional Lebanese Manakeesh baked with love!</p>
  <button onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'});">Contact Us</button>
</section>

<section id="about" class="about">
  <h2>About Us</h2>
  <p>At Furn w Fekhar, we continue the Lebanese tradition of baking fresh, delicious Manakeesh and other specialties. Our mission is to bring the authentic flavors of Tripoli to every table.</p>
</section>

<section id="services" class="services">
  <h2>Our Services</h2>
  <ul>
    <li>Fresh Manakeesh daily</li>
    <li>Custom orders for parties</li>
    <li>Traditional Lebanese baked goods</li>
  </ul>
</section>

<section id="contact" class="contact">
  <h2>Contact Us</h2>
  <p>Phone: 0622-6060</p>
  <p>Address: Tripoli, Lebanon</p>
  <form>
    <input type="text" placeholder="Your Name" style="padding:10px;width:80%;margin:10px 0;"><br>
    <input type="text" placeholder="Message" style="padding:10px;width:80%;margin:10px 0;"><br>
    <button type="submit">Send</button>
    <p style="font-size:0.8em;color:#555;">*This is a placeholder form, submissions won't be sent.</p>
  </form>
</section>

<footer>
  <p>© 2026 Furn w Fekhar</p>
</footer>

</body>
</html>