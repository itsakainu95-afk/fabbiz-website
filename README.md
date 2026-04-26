<!DOCTYPE html>
<html>
<head>
    <title>Fabbiz Platinum Interiors</title>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin:0;
            font-family: Arial;
            background:#f8fafc;
        }

        /* HEADER */
        .nav {
            background:#0f172a;
            padding:10px;
            text-align:center;
            display:flex;
            align-items:center;
            justify-content:center;
            flex-wrap:wrap;
        }

        .nav img {
            height:50px;
            margin-right:15px;
            border-radius:5px;
        }

        .nav a {
            color:white;
            margin:10px;
            text-decoration:none;
            font-weight:bold;
        }

        .nav a:hover {
            color:#facc15;
        }

        /* HERO */
        .hero {
            background:#1e293b;
            color:white;
            padding:70px 20px;
            text-align:center;
        }

        .hero h1 {
            color:#facc15;
            font-size:40px;
        }

        .btn {
            background:#facc15;
            padding:12px 20px;
            text-decoration:none;
            color:black;
            border-radius:5px;
            margin:10px;
            display:inline-block;
            font-weight:bold;
            transition:0.3s;
        }

        .btn:hover {
            background:white;
        }

        /* SECTIONS */
        .section {
            padding:50px 20px;
            text-align:center;
        }

        h2 {
            color:#0f172a;
        }

        /* GRID CARDS */
        .grid {
            display:flex;
            flex-wrap:wrap;
            justify-content:center;
        }

        .card {
            background:white;
            width:250px;
            margin:15px;
            padding:20px;
            border-radius:10px;
            box-shadow:0 4px 10px rgba(0,0,0,0.1);
            transition:0.3s;
        }

        .card:hover {
            transform:scale(1.05);
        }

        .price {
            color:#16a34a;
            font-weight:bold;
        }

        /* GALLERY */
        .gallery img {
            width:250px;
            margin:10px;
            border-radius:10px;
        }

        /* CONTACT */
        .contact-box {
            background:white;
            width:280px;
            margin:auto;
            padding:20px;
            border-radius:10px;
            box-shadow:0 4px 10px rgba(0,0,0,0.1);
        }

        footer {
            background:#0f172a;
            color:white;
            text-align:center;
            padding:20px;
        }

        @media (max-width:600px) {
            .hero h1 {
                font-size:28px;
            }
        }
    </style>
</head>

<body>

<!-- NAV + LOGO -->
<div class="nav">
    <img src="logo.png" alt="Fabbiz Logo">

    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#products">Shop</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
</div>

<!-- HERO -->
<div class="hero" id="home">
    <h1>Fabbiz Platinum Interiors</h1>
    <p>Elegant Interior Design & Quality Home Décor Solutions</p>

    <a href="https://wa.me/254726216607" class="btn">WhatsApp Us</a>
    <a href="tel:+254726216607" class="btn">Call Now</a>
</div>

<!-- SERVICES -->
<div class="section" id="services">
    <h2>Our Services</h2>

    <div class="grid">
        <div class="card">
            <h3>🏠 Home Interiors</h3>
            <p>Modern and stylish home designs.</p>
        </div>

        <div class="card">
            <h3>🏢 Office Design</h3>
            <p>Professional workspace interiors.</p>
        </div>

        <div class="card">
            <h3>🛋 Interior Styling</h3>
            <p>We arrange and style your space beautifully.</p>
        </div>
    </div>
</div>

<!-- PRODUCTS -->
<div class="section" id="products">
    <h2>Our Products</h2>
    <p>Order quality interior décor items directly from us</p>

    <div class="grid">

        <div class="card">
            <h3>🪟 Curtains</h3>
            <p>Elegant modern curtains for homes & offices.</p>
            <p class="price">From KSh 3,500</p>
            <a href="https://wa.me/254726216607?text=I%20want%20curtains" class="btn">Order</a>
        </div>

        <div class="card">
            <h3>🛏 Bed Runners</h3>
            <p>Luxury bedroom finishing touch.</p>
            <p class="price">From KSh 2,000</p>
            <a href="https://wa.me/254726216607?text=I%20want%20bed%20runners" class="btn">Order</a>
        </div>

        <div class="card">
            <h3>🪑 Table Covers</h3>
            <p>Beautiful dining & coffee table covers.</p>
            <p class="price">From KSh 1,500</p>
            <a href="https://wa.me/254726216607?text=I%20want%20table%20covers" class="btn">Order</a>
        </div>

        <div class="card">
            <h3>🌸 Flower Vases</h3>
            <p>Decorative modern home vases.</p>
            <p class="price">From KSh 1,200</p>
            <a href="https://wa.me/254726216607?text=I%20want%20flower%20vases" class="btn">Order</a>
        </div>
<div class="card">
            <h3>🪟 Vertical Blinds</h3>
            <p>Modern vertical blinds for your house or office.</p>
            <p class="price"><Var>Varies with material and size</Var></p>
            <a href="https://wa.me/254726216607?text=I%20want%20vertical%20blinds" class="btn">Order</a>
    </div>
</div>

<!-- GALLERY -->
<div class="section gallery" id="gallery">
    <h2>Our Work</h2>

    <img src="design1.jpg">
    <img src="design2.jpg">
    <img src="design3.jpg">
</div>

<!-- CONTACT -->
<div class="section" id="contact">
    <h2>Contact Us</h2>

    <div class="contact-box">
        <p>📞 +254 726 216 607</p>
        <p>📍 Eldoret, Kenya</p>

        <a href="https://wa.me/254726216607" class="btn">WhatsApp</a>
    </div>
</div>

<!-- FOOTER -->
<footer>
    <p>© 2026 Fabbiz Platinum Interiors</p>
</footer>

</body>
</html># fabbiz-website
