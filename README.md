<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet">
</head>
<body>

    <header class="header">
        <a href="#home" class="logo">Noreak <span>Sattya</span></a>
        <i class='bx bx-menu' id="menu-icon"></i>

        <nav class="navbar">
            <a href="#home" class="active">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="home" id="home">
        <div class="home-img">
            <img src="image.jpg" alt="Profile Image">
        </div>
        <div class="home-content">
            <h1>It's <span>Sattya</span></h1>
            <h3 class="text-animation">I'm a <span></span></h3>
            <p>Your trust partner for digital growth. Build your vision into a stunning website.</p>

            <div class="social-icons">
                <a href="#"><i class='bx bxl-linkedin-square'></i></a>
                <a href="https://www.instagram.com/lilsyaz_?igsh=MTB0OWg0ZXM5a2J2bg%3D%3D&utm_source=qr" target="_blank"><i class='bx bxl-instagram-alt'></i></a>
                <a href="https://www.facebook.com/share/1Eyu9L8FEY/?mibextid=wwXIfr" target="_blank"><i class='bx bxl-facebook-circle'></i></a>
                <a href="https://t.me/Sot_noreaksattya" target="_blank"><i class='bx bxl-telegram'></i></a>
            </div>

            <a href="#" class="btn">Hire Me</a>
        </div>
    </section>

    <section class="about" id="about">
        <div class="about-content">
            <h2 class="heading">About <span>Me</span></h2>
            <h3 class="text-animation"><span></span></h3>
            <p>Currently I am a year 2 student at Cambodia Academy Of Digital Technology, specializing in Software Engineering.</p>
            <a href="#" class="btn">Read More</a>
        </div>
        <div class="about-img">
            <img src="image.jpg" alt="About Image">
        </div>
    </section>

    <section class="services" id="services">
        <h2 class="heading">Services</h2>

        <div class="services-container">
            <div class="service-box">
                <div class="service-info">
                    <h4>Graphic Design</h4>
                    <p>Creating visually appealing designs for various media.</p>
                </div>
            </div>
        
            <div class="service-box">
                <div class="service-info">
                    <h4>Web Development</h4>
                    <p>Building and maintaining websites and web applications.</p>
                </div>
            </div>

            <div class="service-box">
                <div class="service-info">
                    <h4>UI / UX Design</h4>
                    <p>Designing user interfaces and experiences for digital products.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2 class="heading">Contact <span>Me</span></h2>

        <form action="https://formspree.io/f/mqayrrqq" method="POST">
            <div class="input-box">
                <input type="text" name="name" placeholder="Full Name" required>
                <input type="email" name="email" placeholder="Email Address" required>
            </div>

            <div class="input-box">
                <input type="number" name="phone" placeholder="Phone Number" required>
                <input type="text" name="subject" placeholder="Subject" required>
            </div>

            <textarea name="message" cols="30" rows="10" placeholder="Your Message" required></textarea>
            <input type="submit" value="Send Message" class="btn">
        </form>
    </section>

    <footer class="footer">
        <div class="social">
            <a href="#"><i class='bx bxl-linkedin-square'></i></a>
            <a href="https://www.instagram.com/lilsyaz_?igsh=MTB0OWg0ZXM5a2J2bg%3D%3D&utm_source=qr"><i class='bx bxl-instagram-alt'></i></a>
            <a href="https://www.facebook.com/share/1Eyu9L8FEY/?mibextid=wwXIfr" target="_blank"><i class='bx bxl-facebook-circle'></i></a>
            <a href="https://t.me/Sot_noreaksattya"><i class='bx bxl-telegram'></i></a>
        </div>

        <ul class="list">
            <li><a href="#">FAQ</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#about">About me</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#">Privacy Policy</a></li>
        </ul>

        <p class="copyright">
            &copy; 2025 Noreak Sattya. All rights reserved.
        </p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
