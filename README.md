# quality-machine-site.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Quality Machine | Machinery & Hydraulic Repairs</title>
<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: Arial, sans-serif;
    }

    body {
        line-height: 1.6;
        color: #333;
    }

    header {
        background: linear-gradient(rgba(0,0,0,.7), rgba(0,0,0,.7)),
                    url('https://images.unsplash.com/photo-1565008447742-97f6f38c985c?auto=format&fit=crop&w=1600&q=80');
        background-size: cover;
        background-position: center;
        color: white;
        text-align: center;
        padding: 120px 20px;
    }

    header h1 {
        font-size: 3rem;
        margin-bottom: 10px;
    }

    header p {
        font-size: 1.3rem;
    }

    nav {
        background: #1d3557;
        padding: 15px;
        text-align: center;
    }

    nav a {
        color: white;
        text-decoration: none;
        margin: 0 15px;
        font-weight: bold;
    }

    section {
        padding: 60px 20px;
        max-width: 1100px;
        margin: auto;
    }

    h2 {
        color: #1d3557;
        margin-bottom: 20px;
    }

    .services {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 25px;
    }

    .card {
        background: #f4f4f4;
        padding: 25px;
        border-radius: 10px;
        box-shadow: 0 3px 8px rgba(0,0,0,.1);
    }

    .card h3 {
        color: #1d3557;
        margin-bottom: 10px;
    }

    .contact {
        background: #1d3557;
        color: white;
        text-align: center;
        border-radius: 10px;
        padding: 40px;
    }

    .contact p {
        margin: 10px 0;
        font-size: 1.1rem;
    }

    .btn {
        display: inline-block;
        margin-top: 20px;
        padding: 12px 25px;
        background: #e63946;
        color: white;
        text-decoration: none;
        border-radius: 5px;
        font-weight: bold;
    }

    footer {
        text-align: center;
        background: #111;
        color: white;
        padding: 20px;
    }
</style>
</head>
<body>

<header>
    <h1>Quality Machine</h1>
    <p>Professional Machinery & Hydraulic Repair Services</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Us</h2>
    <p>
        Quality Machine provides dependable machinery and hydraulic repair services
        for industrial, agricultural, and heavy equipment applications. We are
        committed to quality workmanship, fast turnaround times, and customer
        satisfaction. Whether you need hydraulic cylinder repair, machine rebuilding,
        or preventive maintenance, we have the experience to get the job done right.
    </p>
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">
            <h3>Hydraulic Repairs</h3>
            <p>Expert repair and rebuilding of hydraulic cylinders, pumps, valves, and systems.</p>
        </div>

        <div class="card">
            <h3>Machinery Repair</h3>
            <p>Complete machinery troubleshooting, repair, restoration, and maintenance services.</p>
        </div>

        <div class="card">
            <h3>Fabrication & Welding</h3>
            <p>Custom fabrication, structural repairs, and professional welding solutions.</p>
        </div>

        <div class="card">
            <h3>Preventive Maintenance</h3>
            <p>Scheduled inspections and maintenance programs to reduce downtime and increase reliability.</p>
        </div>
    </div>
</section>

<section id="contact">
    <div class="contact">
        <h2>Contact Quality Machine</h2>
        <p><strong>Owner:</strong> Larry Mitchell</p>
        <p><strong>Phone:</strong> (678) 360-4784</p>
        <a class="btn" href="tel:6783604784">Call Now</a>
    </div>
</section>

<footer>
    <p>&copy; 2026 Quality Machine. All Rights Reserved.</p>
</footer>

</body>
</html>