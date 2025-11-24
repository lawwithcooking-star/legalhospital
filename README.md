# LEGAL HOSPITAL
FOR EVERY DISPUTE, THERE’S A CURE

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Legal Hospital – by Mohd Meraj</title>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">

<style>
    body {
        font-family: "Segoe UI", sans-serif;
        margin: 0;
        background: #f5f7fa;
        color: #222;
    }

    /* ===== HEADER + LOGO ===== */
    header {
        background: #0A2A43;
        padding: 20px 15px;
        color: white;
    }

    .header-inner {
        max-width: 1100px;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 15px;
        flex-wrap: wrap;
    }

    .logo {
        display: flex;
        align-items: center;
        gap: 14px;
    }

    .logo-badge {
        width: 58px;
        height: 58px;
        border-radius: 50%;
        border: 2px solid #4FC3F7;
        display: flex;
        align-items: center;
        justify-content: center;
        background: rgba(255,255,255,0.06);
        box-shadow: 0 0 0 3px rgba(79,195,247,0.25);
    }

    .logo-badge i {
        font-size: 30px;
        color: #FFFFFF;
    }

    .logo-text {
        display: flex;
        flex-direction: column;
        line-height: 1.2;
    }

    .logo-main {
        font-size: 22px;
        font-weight: 700;
        letter-spacing: 2px;
        text-transform: uppercase;
    }

    .logo-sub {
        font-size: 13px;
        opacity: 0.85;
    }

    /* ===== NAVBAR ===== */
    nav {
        background: #12385A;
        padding: 10px 20px;
        text-align: center;
    }

    nav a {
        color: white;
        margin: 0 20px;
        font-weight: 600;
        text-decoration: none;
        font-size: 16px;
    }

    nav a:hover {
        color: #4FC3F7;
    }

    /* ===== HERO ===== */
    .hero {
        background: url('https://images.unsplash.com/photo-1589820296156-2454bb8a6ad9') center/cover no-repeat;
        padding: 150px 20px;
        text-align: center;
        color: white;
        text-shadow: 2px 2px 6px black;
        animation: fadeIn 1.5s ease-in-out;
    }

    .hero h1 {
        font-size: 52px;
        margin: 0;
    }

    .hero p {
        font-size: 22px;
    }

    /* ===== SECTIONS ===== */
    .section {
        padding: 50px 20px;
        max-width: 1100px;
        margin: auto;
        animation: slideUp 1s ease;
    }

    /* ===== SERVICES ===== */
    .services {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
        gap: 25px;
    }

    .card {
        background: white;
        padding: 25px;
        border-radius: 10px;
        box-shadow: 0px 4px 12px rgba(0,0,0,0.1);
        text-align: center;
        transition: transform .3s;
    }

    .card:hover {
        transform: translateY(-6px);
    }

    .card i {
        font-size: 40px;
        color: #0A2A43;
        margin-bottom: 10px;
    }

    /* ===== CONTACT ===== */
    .contact-box {
        background: white;
        padding: 25px;
        border-radius: 10px;
        box-shadow: 0px 4px 12px rgba(0,0,0,0.1);
        max-width: 600px;
        margin: auto;
        font-size: 18px;
    }

    /* ===== SOCIAL ICONS ===== */
    .social-links {
        text-align: center;
        margin-top: 20px;
    }

    .social-links a {
        color: #0A2A43;
        font-size: 28px;
        margin: 0 15px;
        transition: .3s;
    }

    .social-links a:hover {
        color: #4FC3F7;
    }

    /* ===== FOOTER ===== */
    footer {
        background: #0A2A43;
        color: white;
        text-align: center;
        padding: 18px;
        margin-top: 40px;
    }

    /* ===== ANIMATIONS ===== */
    @keyframes fadeIn {
        from {opacity: 0;}
        to {opacity: 1;}
    }

    @keyframes slideUp {
        from {opacity: 0; transform: translateY(40px);}
        to {opacity: 1; transform: translateY(0);}
    }

    /* Mobile tweaks */
    @media (max-width: 600px) {
        .logo-main {
            font-size: 18px;
        }
        .hero h1 {
            font-size: 34px;
        }
        .hero p {
            font-size: 18px;
        }
    }
</style>
</head>

<body>

<!-- ===== HEADER WITH LOGO ===== -->
<header>
  <div class="header-inner">
    <div class="logo">
      <div class="logo-badge">
        <i class="fa-solid fa-scale-balanced"></i>
      </div>
      <div class="logo-text">
        <div class="logo-main">Legal Hospital</div>
        <div class="logo-sub">Adv. Mohd Meraj · Advocate</div>
      </div>
    </div>
  </div>
</header>

<!-- ===== NAVBAR ===== -->
<nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<!-- ===== HERO ===== -->
<section class="hero">
    <h1>Adv. Mohd Meraj</h1>
    <p>Civil • Criminal • Arbitration • All Legal Disputes</p>
</section>

<!-- ===== ABOUT ===== -->
<section id="about" class="section">
    <h2>About Me</h2>
    <p>
        I am <b> Mohd Meraj</b>, practicing in <b>Lucknow</b>, providing professional 
        legal solutions across civil, criminal, and arbitration matters.  
        With dedication, accuracy, and commitment to justice, I aim to deliver 
        reliable legal care — just like a hospital heals patients.
    </p>
</section>

<!-- ===== SERVICES ===== -->
<section id="services" class="section">
    <h2>Legal Services</h2>

    <div class="services">
        <div class="card">
            <i class="fa-solid fa-landmark"></i>
            <h3>Civil Cases</h3>
            <p>Property, contracts, family matters, recovery suits, injunctions, etc.</p>
        </div>

        <div class="card">
            <i class="fa-solid fa-gavel"></i>
            <h3>Criminal Matters</h3>
            <p>Bail, FIR, trial, appeals, and complete criminal defence.</p>
        </div>

        <div class="card">
            <i class="fa-solid fa-handshake"></i>
            <h3>Arbitration</h3>
            <p>Commercial arbitration, settlements, and dispute resolution.</p>
        </div>

        <div class="card">
            <i class="fa-solid fa-scale-balanced"></i>
            <h3>All Legal Disputes</h3>
            <p>Complete legal support for individuals and businesses.</p>
        </div>
    </div>
</section>

<!-- ===== CONTACT ===== -->
<section id="contact" class="section">
    <h2>Contact</h2>
    <div class="contact-box">
        <p><b>Name:</b>  Mohd Meraj</p>
        <p><b>Phone:</b> <a href="tel:6386420246">6386420246</a></p>
        <p><b>Location:</b> Lucknow, Uttar Pradesh</p>
        <p><b>Email:</b> 
            mohdmerajkhanalig@gmail.com</p> 
            legalhospital@gmail.com</p>
    </div>

    <div class="social-links">
        <a href="#" title="Facebook"><i class="fa-brands fa-facebook"></i></a>
        <a href="#" title="Instagram"><i class="fa-brands fa-instagram"></i></a>
        <a href="https://wa.me/916386420246" title="WhatsApp"><i class="fa-brands fa-whatsapp"></i></a>
    </div>
</section>

<footer>
    © 2025 Legal Hospital – Adv. Mohd Meraj
</footer>

</body>
