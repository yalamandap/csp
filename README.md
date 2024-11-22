
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybercrime Awareness in Rural India</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.1.3/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <style>
        /* Root Variables */
        :root {
            --primary-color: #1a5f7a;
            --secondary-color: #159895;
            --accent-color: #ff9f29;
            --text-color: #333;
            --bg-color: #f6f6f6;
        }

        body {
            font-family: 'Poppins', sans-serif;
            color: var(--text-color);
            background-color: var(--bg-color);
            margin: 0;
        }

        .navbar {
            background-color: var(--primary-color);
            box-shadow: 0 2px 4px rgba(0,0,0,.1);
        }

        .navbar-brand, .nav-link {
            color: white !important;
        }

        .jumbotron {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 6rem 2rem;
            margin-bottom: 0;
            text-align: center;
        }

        .section-title {
            color: var(--primary-color);
            border-bottom: 2px solid var(--accent-color);
            padding-bottom: 10px;
            margin-bottom: 30px;
            font-size: 2rem;
        }

        /* Footer Styles */
        footer {
            background-color: var(--primary-color);
            color: white;
            padding: 2rem 0;
        }

        footer h5 {
            margin-bottom: 1rem;
        }

        footer .container {
            max-width: 1140px;
        }

        .footer-links a {
            color: white;
            text-decoration: none;
        }

        .footer-links a:hover {
            text-decoration: underline;
        }

        .cta-section {
            background-color: var(--accent-color);
            color: white;
            padding: 4rem 0;
            text-align: center;
        }

        /* Gallery Section */
        .extended-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 1rem;
            padding: 2rem 0;
        }

        .gallery-item {
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s ease-in-out;
        }

        .gallery-item img {
            width: 100%;
            height: auto;
            display: block;
            transition: opacity 0.3s ease-in-out;
        }

        .gallery-item:hover {
            transform: scale(1.05);
        }

        .gallery-item:hover img {
            opacity: 0.8;
        }

        .gallery-caption {
            padding: 1rem;
            text-align: center;
            background-color: rgba(26, 95, 122, 0.8);
            color: white;
        }

        /* Content Section Styles */
        .content-section {
            padding: 4rem 0;
            background-color: white;
        }

        .content-section:nth-child(even) {
            background-color: #f9f9f9;
        }

        /* Responsive Design */
        @media screen and (max-width: 768px) {
            .section-title {
                font-size: 1.5rem;
            }
        }

    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark sticky-top">
        <div class="container">
            <a class="navbar-brand" href="#">Cybercrime Awareness India</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#cybercrime-india">Cybercrime in India</a></li>
                    <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
                    <li class="nav-item"><a class="nav-link" href="#impact">Impact</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="jumbotron" id="home">
        <h1 class="display-4">Cybercrime Awareness in Rural India</h1>
        <p class="lead">Empowering rural communities with knowledge to stay safe in the digital world.</p>
        <a class="btn btn-custom btn-lg" href="#about" role="button">Learn More</a>
    </div>

    <div class="content-section" id="about">
        <div class="container">
            <h2 class="section-title">About Our Project</h2>
            <p>Our student-led initiative aims to bridge the digital literacy gap in rural India, focusing on cybercrime awareness and prevention. Through workshops, informational campaigns, and community engagement, we're making a significant impact on online safety in underserved communities.</p>
        </div>
    </div>

    <div class="container" id="gallery">
        <h2 class="section-title text-center my-5">Project Gallery</h2>
        <div class="extended-gallery">
            <!-- Gallery Items -->
            <div class="gallery-item">
                <img src="C:\Users\Administrator\Downloads\IMG-20240521-WA0002.jpg" alt="Rural Workshop">
                <div class="gallery-caption">
                    <h5>Rural Outreach Program</h5>
                    <p>Conducting an awareness workshop in a village community center.</p>
                </div>
            </div>
            <div class="gallery-item">
                <img src="C:\Users\Administrator\Downloads\IMG-20240521-WA0010.jpg" alt="Mobile Safety Demo">
                <div class="gallery-caption">
                    <h5>Mobile Safety Demonstration</h5>
                    <p>Teaching participants about secure mobile banking practices.</p>
                </div>
            </div>
            <div class="gallery-item">
                <img src="C:\Users\Administrator\Downloads\IMG-20240518-WA0011.jpg" alt="Women's Group Session">
                <div class="gallery-caption">
                    <h5>Women's Empowerment Session</h5>
                    <p>Focused group discussion on online safety for rural women.</p>
                </div>
            </div>
            <div class="gallery-item">
                <img src="C:\Users\Administrator\Downloads\IMG-20240518-WA0009.jpg" alt="School Program">
                <div class="gallery-caption">
                    <h5>School Outreach</h5>
                    <p>Educating young students about responsible internet use.</p>
                </div>
            </div>
            <div class="gallery-item">
                <img src="C:\Users\Administrator\Downloads\IMG-20240521-WA0004.jpg" alt="Helpline Center">
                <div class="gallery-caption">
                    <h5>Cybercrime Helpline</h5>
                    <p>Our team managing the 24/7 cybercrime assistance helpline.</p>
                </div>
            </div>
        </div>
    </div>

    <div class="cta-section">
        <h2>Join Our Mission</h2>
        <p>Help us create a safer digital environment for rural India.</p>
        <a href="#contact" class="btn btn-light btn-lg">Get Involved</a>
    </div>

    <div class="content-section" id="contact">
        <div class="container">
            <h2 class="section-title">Contact Us</h2>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Your Name</label>
                    <input type="text" class="form-control" id="name" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email Address</label>
                    <input type="email" class="form-control" id="email" required>
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Your Message</label>
                    <textarea class="form-control" id="message" rows="4" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Send Message</button>
            </form>
        </div>
    </div>

    <footer>
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h5>Cybercrime Awareness India</h5>
                    <p>Contact us for more information or collaboration opportunities.</p>
                </div>
                <div class="col-md-6 text-md-end footer-links">
                    <a href="#">Privacy Policy</a> | <a href="#">Terms & Conditions</a>
                </div>
            </div>
        </div>
    </footer>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.1.3/js/bootstrap.bundle.min.js"></script>
</body>
</html>
