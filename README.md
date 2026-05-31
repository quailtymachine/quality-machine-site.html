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
<section id="testimonials" class="testimonials">
    <div class="container">
        <h2>What Our Customers Say</h2>
        <p class="section-subtitle">
            Trusted by businesses that depend on reliable machinery and hydraulic repairs.
        </p>

        <div class="testimonial-grid">

            <div class="testimonial-card">
                <div class="stars">★★★★★</div>
                <p>
                    "Quality Machine rebuilt several hydraulic cylinders for our
                    excavation equipment. Fast turnaround and outstanding workmanship."
                </p>
                <h4>Mike R.</h4>
                <span>Construction Contractor</span>
            </div>

            <div class="testimonial-card">
                <div class="stars">★★★★★</div>
                <p>
                    "Larry and his team got our production equipment running again
                    quickly. Professional service and fair pricing."
                </p>
                <h4>David S.</h4>
                <span>Manufacturing Manager</span>
            </div>

            <div class="testimonial-card">
                <div class="stars">★★★★★</div>
                <p>
                    "We've used Quality Machine for hydraulic repairs and preventive
                    maintenance. Their work is always top-notch."
                </p>
                <h4>Sarah T.</h4>
                <span>Fleet Operations Supervisor</span>
            </div>

        </div>
    </div>
</section>
.testimonials {
    background: #f7f7f7;
    padding: 80px 20px;
    text-align: center;
}

.testimonials h2 {
    color: #1d3557;
    margin-bottom: 10px;
    font-size: 2.5rem;
}

.section-subtitle {
    max-width: 700px;
    margin: 0 auto 40px;
    color: #666;
}

.testimonial-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
}

.testimonial-card {
    background: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,.08);
}

.stars {
    color: #f4b400;
    font-size: 1.4rem;
    margin-bottom: 15px;
}

.testimonial-card p {
    margin-bottom: 15px;
    font-style: italic;
}

.testimonial-card h4 {
    color: #1d3557;
}
<section id="service-request" class="service-request">
    <div class="container">

        <div class="request-header">
            <h2>Request Service</h2>
            <p>
                Need machinery or hydraulic repairs? Submit your information below
                and we'll contact you as soon as possible.
            </p>
        </div>

        <form class="request-form" action="#" method="post">

            <div class="form-row">
                <div class="form-group">
                    <label>Full Name *</label>
                    <input type="text" name="name" required>
                </div>

                <div class="form-group">
                    <label>Company Name</label>
                    <input type="text" name="company">
                </div>
            </div>

            <div class="form-row">
                <div class="form-group">
                    <label>Phone Number *</label>
                    <input type="tel" name="phone" required>
                </div>

                <div class="form-group">
                    <label>Email Address</label>
                    <input type="email" name="email">
                </div>
            </div>

            <div class="form-row">
                <div class="form-group full-width">
                    <label>Equipment Type</label>
                    <input type="text"
                           placeholder="Excavator, Loader, Hydraulic Cylinder, Press, etc.">
                </div>
            </div>

            <div class="form-row">
                <div class="form-group full-width">
                    <label>Service Needed *</label>
                    <select required>
                        <option value="">Select Service</option>
                        <option>Hydraulic Repair</option>
                        <option>Machinery Repair</option>
                        <option>Fabrication & Welding</option>
                        <option>Preventive Maintenance</option>
                        <option>Emergency Service</option>
                        <option>Other</option>
                    </select>
                </div>
            </div>

            <div class="form-row">
                <div class="form-group full-width">
                    <label>Describe the Problem *</label>
                    <textarea rows="6" required
                              placeholder="Tell us about your equipment issue, repair needs, or maintenance request..."></textarea>
                </div>
            </div>

            <button type="submit" class="submit-btn">
                Submit Service Request
            </button>

        </form>

    </div>
</section>
.service-request {
    background: #f8f9fb;
    padding: 80px 20px;
}

.request-header {
    text-align: center;
    margin-bottom: 40px;
}

.request-header h2 {
    font-size: 2.5rem;
    color: #1d3557;
    margin-bottom: 10px;
}

.request-form {
    max-width: 900px;
    margin: auto;
    background: #fff;
    padding: 40px;
    border-radius: 12px;
    box-shadow: 0 10px 25px rgba(0,0,0,.08);
}

.form-row {
    display: flex;
    gap: 20px;
    margin-bottom: 20px;
}

.form-group {
    flex: 1;
}

.full-width {
    width: 100%;
}

label {
    display: block;
    margin-bottom: 8px;
    font-weight: 600;
}

input,
select,
textarea {
    width: 100%;
    padding: 14px;
    border: 1px solid #d5d5d5;
    border-radius: 6px;
    font-size: 16px;
}

input:focus,
select:focus,
textarea:focus {
    outline: none;
    border-color: #1d3557;
}

.submit-btn {
    background: #f4b400;
    color: #111;
    border: none;
    padding: 16px 30px;
    font-size: 18px;
    font-weight: bold;
    border-radius: 6px;
    cursor: pointer;
    width: 100%;
}

.submit-btn:hover {
    opacity: 0.9;
}

@media (max-width: 768px) {
    .form-row {
        flex-direction: column;
    }
}
<section class="contact-banner">
    <h2>Need Immediate Assistance?</h2>
    <p>Call Larry Mitchell directly for machinery and hydraulic repair service.</p>

    <a href="tel:6783604784" class="call-btn">
        Call (678) 360-4784
    </a>
</section>