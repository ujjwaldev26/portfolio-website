# Power Gym Landing Page

A modern gym landing page built using HTML and CSS.

## Features

- Responsive design
- Modern UI
- Hero section
- Services section
- Trainers section
- Contact form
- Smooth animations

## Technologies Used

- HTML5
- CSS3
- Flexbox
- CSS Grid

## Live Website

Add your Netlify link here

## Author

Ujjwal Anand
Frontend Developer

## HTML Structure
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Power Gym - Build Your Dream Body</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>

<body>
    <!--Navbar-->
    <nav class="navbar">
        <div class="logo">
            <i class="fas fa-dumbbell"></i>
            <span>Power Gym</span>
        </div>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#trainers">Trainers</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <div class="hamburger">
            <i class="fas fa-bars"></i>
        </div>
    </nav>

    <!--Hero Section-->
    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Build Your <span class="highlight">Dream Body</span></h1>
            <p>Transform your fitness journey with state-of-the-art equipment and expert trainers</p>
            <div class="hero-buttons">
                <button class="btn-primary">Join Now</button>
                <button class="btn-secondary">Learn More</button>
            </div>
            <div class="hero-stats">
                <div class="stat">
                    <span class="stat-number">500+</span>
                    <span class="stat-label">Members</span>
                </div>
                <div class="stat">
                    <span class="stat-number">20+</span>
                    <span class="stat-label">Trainers</span>
                </div>
                <div class="stat">
                    <span class="stat-number">10+</span>
                    <span class="stat-label">Programs</span>
                </div>
            </div>
        </div>
    </section>

    <!--Services Section-->
    <section class="services" id="services">
        <h2 class="section-title">Our <span class="highlight">Services</span></h2>
        <div class="services-container">
            <div class="service-card">
                <div class="service-icon">
                    <i class="fas fa-dumbbell"></i>
                </div>
                <h3>Strength Training</h3>
                <p>Professional weight training equipment and expert guidance for building muscle and strength</p>
            </div>
            <div class="service-card">
                <div class="service-icon">
                    <i class="fas fa-running"></i>
                </div>
                <h3>Cardio Zone</h3>
                <p>Advanced cardio equipment including treadmills, bikes, and ellipticals for optimal heart health</p>
            </div>
            <div class="service-card">
                <div class="service-icon">
                    <i class="fas fa-user-tie"></i>
                </div>
                <h3>Personal Training</h3>
                <p>One-on-one sessions with certified fitness trainers to achieve your specific goals</p>
            </div>
            <div class="service-card">
                <div class="service-icon">
                    <i class="fas fa-apple-alt"></i>
                </div>
                <h3>Nutrition Plans</h3>
                <p>Customized meal plans and nutrition guidance to fuel your workouts and recovery</p>
            </div>
            <div class="service-card">
                <div class="service-icon">
                    <i class="fas fa-clock"></i>
                </div>
                <h3>24/7 Access</h3>
                <p>Round-the-clock gym access for members who want to workout anytime</p>
            </div>
            <div class="service-card">
                <div class="service-icon">
                    <i class="fas fa-spa"></i>
                </div>
                <h3>Recovery Zone</h3>
                <p>Sauna, steam room, and massage services for post-workout recovery</p>
            </div>
        </div>
    </section>

    <!--Trainers Section-->
    <section class="trainers" id="trainers">
        <h2 class="section-title">Meet Our <span class="highlight">Trainers</span></h2>
        <div class="trainers-container">
            <div class="trainer-card">
                <div class="trainer-image">
                    <i class="fas fa-user"></i>
                </div>
                <h3>John Smith</h3>
                <p class="trainer-title">Head Trainer</p>
                <p>10+ years experience in strength and conditioning</p>
            </div>
            <div class="trainer-card">
                <div class="trainer-image">
                    <i class="fas fa-user"></i>
                </div>
                <h3>Sarah Johnson</h3>
                <p class="trainer-title">Cardio Specialist</p>
                <p>Expert in HIIT and weight loss programs</p>
            </div>
            <div class="trainer-card">
                <div class="trainer-image">
                    <i class="fas fa-user"></i>
                </div>
                <h3>Mike Davis</h3>
                <p class="trainer-title">Nutrition Coach</p>
                <p>Certified sports nutritionist</p>
            </div>
        </div>
    </section>

    <!--Contact Section-->
    <section class="contact" id="contact">
        <h2 class="section-title">Contact <span class="highlight">Us</span></h2>
        <div class="contact-container">
            <div class="contact-info">
                <div class="contact-item">
                    <i class="fas fa-phone"></i>
                    <span>+91 9000000087</span>
                </div>
                <div class="contact-item">
                    <i class="fas fa-envelope"></i>
                    <span>powergym@gmail.com</span>
                </div>
                <div class="contact-item">
                    <i class="fas fa-map-marker-alt"></i>
                    <span>123 Fitness Street, Gym City</span>
                </div>
            </div>
            <form class="contact-form">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="5" required></textarea>
                <button type="submit" class="btn-primary">Send Message</button>
            </form>
        </div>
    </section>

    <!--Footer-->
    <footer>
        <div class="footer-content">
            <p>&copy; 2024 Power Gym. All Rights Reserved.</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-youtube"></i></a>
            </div>
        </div>
    </footer>

</body>

</html>

## CSS Styling
/* CSS Variables for Modern Design */
:root {
    --primary-color: #ff4d4d;
    --primary-dark: #e63946;
    --secondary-color: #00d4ff;
    --dark-bg: #0a0a0a;
    --dark-secondary: #151515;
    --dark-tertiary: #1a1a1a;
    --text-light: #ffffff;
    --text-gray: #a0a0a0;
    --gradient: linear-gradient(135deg, #ff4d4d 0%, #ff6b35 100%);
    --gradient-blue: linear-gradient(135deg, #00d4ff 0%, #0099cc 100%);
    --shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
    --transition: all 0.3s ease;
}

/* Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Poppins', sans-serif;
    background-color: var(--dark-bg);
    color: var(--text-light);
    line-height: 1.6;
    overflow-x: hidden;
}

/* Navbar Styles */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
    background: rgba(10, 10, 10, 0.95);
    backdrop-filter: blur(10px);
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1000;
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}

.logo {
    display: flex;
    align-items: center;
    gap: 10px;
    font-size: 24px;
    font-weight: 800;
    color: var(--primary-color);
}

.logo i {
    font-size: 28px;
}

.nav-links {
    display: flex;
    gap: 30px;
    list-style: none;
}

.nav-links li a {
    color: var(--text-light);
    text-decoration: none;
    font-weight: 500;
    font-size: 15px;
    transition: var(--transition);
    position: relative;
}

.nav-links li a::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 0;
    height: 2px;
    background: var(--primary-color);
    transition: var(--transition);
}

.nav-links li a:hover::after {
    width: 100%;
}

.nav-links li a:hover {
    color: var(--primary-color);
}

.hamburger {
    display: none;
    font-size: 24px;
    cursor: pointer;
    color: var(--text-light);
}

/* Hero Section */
.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: linear-gradient(135deg, rgba(10, 10, 10, 0.85) 0%, rgba(20, 20, 20, 0.75) 100%),
                url('https://images.unsplash.com/photo-1534438327276-14e5300c3a48?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    padding: 120px 20px 80px;
    position: relative;
    overflow: hidden;
}

.hero::before {
    content: '';
    position: absolute;
    top: -50%;
    right: -30%;
    width: 80%;
    height: 150%;
    background: radial-gradient(ellipse, rgba(255, 77, 77, 0.15) 0%, transparent 70%);
    pointer-events: none;
}

.hero-content {
    text-align: center;
    max-width: 800px;
    z-index: 1;
    position: relative;
}

.hero h1 {
    font-size: 64px;
    font-weight: 800;
    line-height: 1.1;
    margin-bottom: 20px;
    text-transform: uppercase;
    letter-spacing: -1px;
}

.hero h1 .highlight {
    background: var(--gradient);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.hero p {
    font-size: 18px;
    color: var(--text-gray);
    margin-bottom: 40px;
    max-width: 600px;
    margin-left: auto;
    margin-right: auto;
}

.hero-buttons {
    display: flex;
    gap: 20px;
    justify-content: center;
    margin-bottom: 60px;
}

.btn-primary,
.btn-secondary {
    padding: 16px 40px;
    font-size: 16px;
    font-weight: 600;
    border-radius: 50px;
    cursor: pointer;
    transition: var(--transition);
    text-transform: uppercase;
    letter-spacing: 1px;
}

.btn-primary {
    background: var(--gradient);
    color: white;
    border: none;
    box-shadow: 0 5px 20px rgba(255, 77, 77, 0.4);
}

.btn-primary:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 30px rgba(255, 77, 77, 0.5);
}

.btn-secondary {
    background: transparent;
    color: var(--text-light);
    border: 2px solid var(--text-gray);
}

.btn-secondary:hover {
    border-color: var(--primary-color);
    color: var(--primary-color);
}

.hero-stats {
    display: flex;
    justify-content: center;
    gap: 60px;
}

.stat {
    text-align: center;
}

.stat-number {
    display: block;
    font-size: 42px;
    font-weight: 800;
    color: var(--primary-color);
    line-height: 1;
}

.stat-label {
    font-size: 14px;
    color: var(--text-gray);
    text-transform: uppercase;
    letter-spacing: 2px;
}

/* Section Styles */
section {
    padding: 100px 50px;
}

.section-title {
    font-size: 42px;
    font-weight: 800;
    text-align: center;
    margin-bottom: 60px;
    text-transform: uppercase;
}

.section-title .highlight {
    background: var(--gradient);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

/* Services Section */
.services {
    background: var(--dark-secondary);
}

.services-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    max-width: 1200px;
    margin: 0 auto;
}

.service-card {
    background: var(--dark-tertiary);
    padding: 40px 30px;
    border-radius: 20px;
    text-align: center;
    transition: var(--transition);
    border: 1px solid rgba(255, 255, 255, 0.05);
    position: relative;
    overflow: hidden;
}

.service-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 3px;
    background: var(--gradient);
    transform: scaleX(0);
    transition: var(--transition);
}

.service-card:hover {
    transform: translateY(-10px);
    box-shadow: var(--shadow);
}

.service-card:hover::before {
    transform: scaleX(1);
}

.service-icon {
    width: 80px;
    height: 80px;
    background: var(--gradient);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 25px;
    font-size: 32px;
    color: white;
}

.service-card h3 {
    font-size: 22px;
    margin-bottom: 15px;
    font-weight: 700;
}

.service-card p {
    color: var(--text-gray);
    font-size: 15px;
    line-height: 1.7;
}

/* Trainers Section */
.trainers {
    background: var(--dark-bg);
}

.trainers-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    max-width: 1200px;
    margin: 0 auto;
}

.trainer-card {
    background: var(--dark-secondary);
    padding: 40px 30px;
    border-radius: 20px;
    text-align: center;
    transition: var(--transition);
    border: 1px solid rgba(255, 255, 255, 0.05);
}

.trainer-card:hover {
    transform: translateY(-10px);
    box-shadow: var(--shadow);
}

.trainer-image {
    width: 120px;
    height: 120px;
    background: var(--gradient);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 25px;
    font-size: 48px;
    color: white;
}

.trainer-card h3 {
    font-size: 22px;
    margin-bottom: 10px;
    font-weight: 700;
}

.trainer-title {
    color: var(--primary-color);
    font-weight: 600;
    margin-bottom: 15px;
    font-size: 14px;
    text-transform: uppercase;
    letter-spacing: 1px;
}

.trainer-card p {
    color: var(--text-gray);
    font-size: 14px;
}

/* Contact Section */
.contact {
    background: var(--dark-secondary);
}

.contact-container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    max-width: 1000px;
    margin: 0 auto;
}

.contact-info {
    display: flex;
    flex-direction: column;
    gap: 30px;
}

.contact-item {
    display: flex;
    align-items: center;
    gap: 20px;
    padding: 25px;
    background: var(--dark-tertiary);
    border-radius: 15px;
    transition: var(--transition);
}

.contact-item:hover {
    transform: translateX(10px);
    box-shadow: var(--shadow);
}

.contact-item i {
    width: 50px;
    height: 50px;
    background: var(--gradient);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 20px;
    color: white;
}

.contact-item span {
    font-size: 16px;
    font-weight: 500;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.contact-form input,
.contact-form textarea {
    padding: 18px 25px;
    background: var(--dark-tertiary);
    border: 1px solid rgba(255, 255, 255, 0.1);
    border-radius: 12px;
    color: var(--text-light);
    font-size: 15px;
    font-family: 'Poppins', sans-serif;
    transition: var(--transition);
}

.contact-form input:focus,
.contact-form textarea:focus {
    outline: none;
    border-color: var(--primary-color);
    box-shadow: 0 0 20px rgba(255, 77, 77, 0.2);
}

.contact-form input::placeholder,
.contact-form textarea::placeholder {
    color: var(--text-gray);
}

.contact-form button {
    padding: 18px 40px;
    font-size: 16px;
    font-weight: 600;
    border-radius: 50px;
    cursor: pointer;
    transition: var(--transition);
    text-transform: uppercase;
    letter-spacing: 1px;
    background: var(--gradient);
    color: white;
    border: none;
    box-shadow: 0 5px 20px rgba(255, 77, 77, 0.4);
}

.contact-form button:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 30px rgba(255, 77, 77, 0.5);
}

/* Footer */
footer {
    background: var(--dark-tertiary);
    padding: 40px 50px;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
}

.footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
}

.footer-content p {
    color: var(--text-gray);
    font-size: 14px;
}

.social-links {
    display: flex;
    gap: 20px;
}

.social-links a {
    width: 45px;
    height: 45px;
    background: var(--dark-secondary);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--text-light);
    text-decoration: none;
    transition: var(--transition);
    font-size: 18px;
}

.social-links a:hover {
    background: var(--primary-color);
    transform: translateY(-5px);
}

/* Responsive Design */
@media (max-width: 968px) {
    .navbar {
        padding: 15px 30px;
    }

    .nav-links {
        display: none;
    }

    .hamburger {
        display: block;
    }

    .hero h1 {
        font-size: 42px;
    }

    .hero-stats {
        gap: 30px;
    }

    .stat-number {
        font-size: 32px;
    }

    .contact-container {
        grid-template-columns: 1fr;
    }

    section {
        padding: 60px 30px;
    }
}

@media (max-width: 576px) {
    .hero h1 {
        font-size: 32px;
    }

    .hero p {
        font-size: 16px;
    }

    .hero-buttons {
        flex-direction: column;
    }

    .btn-primary,
    .btn-secondary {
        width: 100%;
    }

    .hero-stats {
        flex-direction: column;
        gap: 25px;
    }

    .section-title {
        font-size: 28px;
    }

    .services-container,
    .trainers-container {
        grid-template-columns: 1fr;
    }

    .footer-content {
        flex-direction: column;
        gap: 20px;
        text-align: center;
    }
}

/* Animation Keyframes */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.hero-content {
    animation: fadeInUp 1s ease-out;
}

.service-card,
.trainer-card {
    animation: fadeInUp 1s ease-out;
    animation-fill-mode: both;
}

.service-card:nth-child(1) { animation-delay: 0.1s; }
.service-card:nth-child(2) { animation-delay: 0.2s; }
.service-card:nth-child(3) { animation-delay: 0.3s; }
.service-card:nth-child(4) { animation-delay: 0.4s; }
.service-card:nth-child(5) { animation-delay: 0.5s; }
.service-card:nth-child(6) { animation-delay: 0.6s; }

.trainer-card:nth-child(1) { animation-delay: 0.1s; }
.trainer-card:nth-child(2) { animation-delay: 0.2s; }
.trainer-card:nth-child(3) { animation-delay: 0.3s; }


