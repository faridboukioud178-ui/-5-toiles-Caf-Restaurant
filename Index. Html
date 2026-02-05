# -5-toiles-Caf-Restaurant
Index. Html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>5 Étoiles | Luxury Café & Restaurant</title>
    
    <!-- Fonts: Playfair Display (Luxury Serif) & Lato (Clean Sans-Serif) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&family=Playfair+Display:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">

    <style>
        /* --- CSS VARIABLES & RESET --- */
        :root {
            --gold: #D4AF37;
            --gold-light: #F3E5AB;
            --black: #0a0a0a;
            --charcoal: #1c1c1c;
            --white: #ffffff;
            --cream: #f9f8f4;
            --text-grey: #4a4a4a;
            --transition: all 0.4s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Lato', sans-serif;
            background-color: var(--cream);
            color: var(--text-grey);
            line-height: 1.6;
            overflow-x: hidden;
        }

        h1, h2, h3, h4 {
            font-family: 'Playfair Display', serif;
            color: var(--black);
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        ul {
            list-style: none;
        }

        img {
            width: 100%;
            display: block;
            object-fit: cover;
        }

        /* --- UTILITIES --- */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .section-padding {
            padding: 100px 0;
        }

        .text-center {
            text-align: center;
        }

        .gold-text {
            color: var(--gold);
        }

        .section-title {
            font-size: 3rem;
            margin-bottom: 1rem;
            font-weight: 700;
            letter-spacing: 1px;
        }

        .section-subtitle {
            font-size: 1.1rem;
            text-transform: uppercase;
            letter-spacing: 4px;
            color: var(--gold);
            margin-bottom: 10px;
            display: block;
        }

        .btn {
            display: inline-block;
            padding: 15px 35px;
            background-color: var(--gold);
            color: var(--white);
            text-transform: uppercase;
            letter-spacing: 2px;
            font-size: 0.9rem;
            font-weight: 700;
            border: 1px solid var(--gold);
            transition: var(--transition);
            cursor: pointer;
        }

        .btn:hover {
            background-color: transparent;
            color: var(--gold);
        }

        .btn-outline {
            background-color: transparent;
            border: 1px solid var(--white);
            color: var(--white);
        }

        .btn-outline:hover {
            background-color: var(--white);
            color: var(--black);
        }

        /* --- NAVIGATION --- */
        .navbar {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            padding: 25px 0;
            z-index: 1000;
            transition: var(--transition);
        }

        .navbar.scrolled {
            background-color: rgba(255, 255, 255, 0.95);
            box-shadow: 0 5px 20px rgba(0,0,0,0.05);
            padding: 15px 0;
        }

        .nav-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--white);
            letter-spacing: 2px;
        }
        
        .navbar.scrolled .logo {
            color: var(--black);
        }

        .nav-links {
            display: flex;
            gap: 40px;
        }

        .nav-links a {
            color: var(--white);
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            position: relative;
        }

        .navbar.scrolled .nav-links a {
            color: var(--black);
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            width: 0;
            height: 1px;
            bottom: -5px;
            left: 0;
            background-color: var(--gold);
            transition: var(--transition);
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        /* --- HERO SECTION --- */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1554118811-1e0d58224f24?q=80&w=1920&auto=format&fit=crop') no-repeat center center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: var(--white);
        }

        .hero-content h1 {
            font-size: 5rem;
            color: var(--white);
            margin-bottom: 20px;
            text-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .hero-content p {
            font-size: 1.2rem;
            margin-bottom: 40px;
            font-weight: 300;
            letter-spacing: 1px;
        }

        /* --- ABOUT SECTION --- */
        .about {
            background-color: var(--white);
        }

        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
        }

        .about-text p {
            margin-bottom: 20px;
            font-size: 1.05rem;
        }

        .about-img {
            position: relative;
        }

        .about-img::before {
            content: '';
            position: absolute;
            top: -20px;
            left: -20px;
            width: 100%;
            height: 100%;
            border: 2px solid var(--gold);
            z-index: -1;
        }

        /* --- MENU SECTION --- */
        .menu-section {
            background-color: var(--cream);
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
            margin-top: 60px;
        }

        .menu-item {
            background: var(--white);
            padding: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            transition: var(--transition);
            text-align: center;
        }

        .menu-item:hover {
            transform: translateY(-10px);
        }

        .menu-img {
            height: 300px;
            margin-bottom: 20px;
            overflow: hidden;
        }

        .menu-img img {
            height: 100%;
            transition: var(--transition);
        }

        .menu-item:hover .menu-img img {
            transform: scale(1.1);
        }

        .menu-item h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }

        .menu-item .price {
            display: block;
            color: var(--gold);
            font-weight: 700;
            font-size: 1.2rem;
            margin-bottom: 10px;
        }

        /* --- INTERIOR/GALLERY --- */
        .gallery {
            background-color: var(--black);
            color: var(--white);
        }

        .gallery .section-title {
            color: var(--white);
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-template-rows: repeat(2, 300px);
            gap: 10px;
            margin-top: 50px;
        }

        .gallery-item {
            position: relative;
            overflow: hidden;
        }

        .gallery-item img {
            height: 100%;
            transition: var(--transition);
            filter: brightness(0.8);
        }

        .gallery-item:hover img {
            transform: scale(1.05);
            filter: brightness(1);
        }

        /* Spanning grid items */
        .g-item-1 { grid-column: span 2; grid-row: span 1; }
        .g-item-2 { grid-column: span 1; grid-row: span 2; }
        
        /* --- RESERVATION --- */
        .reservation {
            background: linear-gradient(rgba(255,255,255,0.9), rgba(255,255,255,0.9)), url('https://images.unsplash.com/photo-1559339352-11d035aa65de?q=80&w=1920&auto=format&fit=crop') no-repeat center center/cover;
            background-attachment: fixed;
        }

        .reservation-form {
            max-width: 600px;
            margin: 0 auto;
            background: var(--white);
            padding: 50px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            border: 1px solid var(--gold);
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-control {
            width: 100%;
            padding: 15px;
            border: 1px solid #ddd;
            background: transparent;
            font-family: 'Lato', sans-serif;
            font-size: 1rem;
        }

        .form-control:focus {
            outline: none;
            border-color: var(--gold);
        }

        /* --- FOOTER --- */
        footer {
            background-color: var(--black);
            color: #888;
            padding: 80px 0 30px;
            text-align: center;
        }

        .footer-logo {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            color: var(--white);
            margin-bottom: 20px;
            display: inline-block;
        }

        .footer-info p {
            margin-bottom: 10px;
            font-size: 0.9rem;
        }

        .social-links {
            margin: 30px 0;
        }

        .social-links a {
            display: inline-block;
            width: 40px;
            height: 40px;
            border: 1px solid #444;
            border-radius: 50%;
            line-height: 40px;
            color: var(--white);
            margin: 0 5px;
            transition: var(--transition);
        }

        .social-links a:hover {
            background-color: var(--gold);
            border-color: var(--gold);
        }

        /* --- RESPONSIVE --- */
        @media (max-width: 768px) {
            .hero-content h1 { font-size: 3rem; }
            .about-grid { grid-template-columns: 1fr; }
            .gallery-grid { grid-template-columns: 1fr; grid-template-rows: auto; }
            .g-item-1, .g-item-2 { grid-column: span 1; grid-row: span 1; }
            .navbar { background-color: rgba(255,255,255,0.95); }
            .navbar .logo, .nav-links a { color: var(--black); }
            .nav-links { display: none; } /* Simple hide for demo, usually hamburger menu */
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav class="navbar">
        <div class="container nav-content">
            <a href="#" class="logo">5 <span class="gold-text">Étoiles</span></a>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">The Experience</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#gallery">Interiors</a></li>
                <li><a href="#reserve">Reservations</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content container">
            <span class="section-subtitle">Café & Restaurant</span>
            <h1>Taste the Elegance</h1>
            <p>An exquisite sanctuary of flavor, sophistication, and luxury.</p>
            <a href="#reserve" class="btn btn-outline">Book a Table</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section-padding about">
        <div class="container">
            <div class="about-grid">
                <div class="about-img">
                    <!-- Image: Marble table, gold accents, coffee -->
                    <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?q=80&w=1000&auto=format&fit=crop" alt="Luxury Interior">
                </div>
                <div class="about-text">
                    <span class="section-subtitle">Our Story</span>
                    <h2 class="section-title">Classic Sophistication</h2>
                    <p>Nestled in the heart of the city, <strong>5 Étoiles</strong> redefines the art of coffee and dining. Inspired by the golden age of European cafés, we blend modern culinary techniques with timeless elegance.</p>
                    <p>From our hand-selected arabica beans to our locally-sourced gastronomy, every detail is curated to provide a sensory journey. Experience the warmth of golden lighting, the touch of refined marble, and the silence of true luxury.</p>
                    <br>
                    <a href="#menu" class="btn">View Menu</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Menu Highlights -->
    <section id="menu" class="section-padding menu-section">
        <div class="container">
            <div class="text-center">
                <span class="section-subtitle">Culinary Highlights</span>
                <h2 class="section-title">Signature Selections</h2>
            </div>

            <div class="menu-grid">
                <!-- Item 1 -->
                <div class="menu-item">
                    <div class="menu-img">
                        <img src="https://images.unsplash.com/photo-1572442388796-11668a67e53d?q=80&w=800&auto=format&fit=crop" alt="Latte Art">
                    </div>
                    <h3>The Royal Latte</h3>
                    <span class="price">$18</span>
                    <p>Single-origin Ethiopian beans, steamed gold milk, edible 24k gold dust.</p>
                </div>

                <!-- Item 2 -->
                <div class="menu-item">
                    <div class="menu-img">
                        <img src="https://images.unsplash.com/photo-1559586616-361e18714958?q=80&w=800&auto=format&fit=crop" alt="Fine Dining Dish">
                    </div>
                    <h3>Truffle Risotto</h3>
                    <span class="price">$45</span>
                    <p>Arborio rice, black truffle shavings, saffron, aged parmesan crisp.</p>
                </div>

                <!-- Item 3 -->
                <div class="menu-item">
                    <div class="menu-img">
                        <img src="https://images.unsplash.com/photo-1551024709-8f23befc6f87?q=80&w=800&auto=format&fit=crop" alt="Dessert">
                    </div>
                    <h3>Midnight Tart</h3>
                    <span class="price">$22</span>
                    <p>Dark Belgian chocolate ganache, raspberry coulis, gold leaf finish.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery / Interiors -->
    <section id="gallery" class="section-padding gallery">
        <div class="container">
            <div class="text-center">
                <span class="section-subtitle">Ambience</span>
                <h2 class="section-title">A Visual Feast</h2>
            </div>
            
            <div class="gallery-grid">
                <div class="gallery-item g-item-1">
                    <!-- Wide shot of interior -->
                    <img src="https://images.unsplash.com/photo-1550966871-3ed3c47e2ce2?q=80&w=1000&auto=format&fit=crop" alt="Restaurant Interior">
                </div>
                <div class="gallery-item">
                    <!-- Close up of table setting -->
                    <img src="https://images.unsplash.com/photo-1533089862017-5614a957146d?q=80&w=800&auto=format&fit=crop" alt="Table Setting">
                </div>
                <div class="gallery-item g-item-2">
                    <!-- Tall shot of bar / coffee machine -->
                    <img src="https://images.unsplash.com/photo-1497935586351-b67a49e012bf?q=80&w=800&auto=format&fit=crop" alt="Coffee Bar">
                </div>
                <div class="gallery-item">
                    <!-- Greenery/Window shot -->
                    <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?q=80&w=800&auto=format&fit=crop" alt="Window Seat">
                </div>
            </div>
        </div>
    </section>

    <!-- Reservation -->
    <section id="reserve" class="section-padding reservation">
        <div class="container">
            <div class="text-center">
                <span class="section-subtitle">Join Us</span>
                <h2 class="section-title">Reserve Your Table</h2>
            </div>

            <div class="reservation-form">
                <form>
                    <div class="form-group">
                        <input type="text" class="form-control" placeholder="Your Name">
                    </div>
                    <div class="form-group">
                        <input type="email" class="form-control" placeholder="Email Address">
                    </div>
                    <div class="form-group">
                        <input type="date" class="form-control">
                    </div>
                    <div class="form-group">
                        <select class="form-control">
                            <option>2 Guests</option>
                            <option>4 Guests</option>
                            <option>6 Guests</option>
                            <option>Private Event</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <textarea class="form-control" rows="4" placeholder="Special Requests (Dietary, Occasion)"></textarea>
                    </div>
                    <button type="submit" class="btn" style="width: 100%;">Confirm Reservation</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <a href="#" class="footer-logo">5 <span class="gold-text">Étoiles</span></a>
            <div class="footer-info">
                <p>123 Luxury Avenue, Golden District</p>
                <p>Open Daily: 8:00 AM - 11:00 PM</p>
                <p>+1 (555) 019-2834</p>
            </div>
            <div class="social-links">
                <a href="#">IG</a>
                <a href="#">FB</a>
                <a href="#">TW</a>
            </div>
            <p style="font-size: 0.8rem; opacity: 0.5;">&copy; 2023 5 Étoiles Café. All Rights Reserved.</p>
        </div>
    </footer>

    <!-- Scripts -->
    <script>
        // Navbar scroll effect
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('.navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('scrolled');
            } else {
                navbar.classList.remove('scrolled');
            }
        });
    </script>
</body>
</html>
