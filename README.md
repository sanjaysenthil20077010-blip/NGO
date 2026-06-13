
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoHarmony Foundation - Harmony with Nature</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@400;500;600&display=swap');
        
        :root {
            --primary-green: #0A3D2F;
            --accent-teal: #00C4B4;
            --light-green: #A8E6CF;
            --earth-beige: #F4EDE4;
            --warm-orange: #FF8C42;
        }
        
        * { margin: 0; padding: 0; box-sizing: border-box; }
        
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            color: #333;
            overflow-x: hidden;
        }
        
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(10, 61, 47, 0.75), rgba(10, 61, 47, 0.75)), url('https://picsum.photos/id/1015/1920/1080') center/cover no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            position: relative;
        }
        
        .hero-content {
            max-width: 800px;
            padding: 0 20px;
            z-index: 2;
        }
        
        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 4.5rem;
            margin-bottom: 20px;
            text-shadow: 0 4px 20px rgba(0,0,0,0.3);
        }
        
        .tagline {
            font-size: 1.5rem;
            margin-bottom: 40px;
            opacity: 0.95;
        }
        
        .btn {
            display: inline-block;
            padding: 16px 40px;
            background: var(--accent-teal);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(0, 196, 180, 0.3);
        }
        
        .btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(0, 196, 180, 0.4);
        }
        
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(10, 61, 47, 0.95);
            backdrop-filter: blur(10px);
            z-index: 1000;
            padding: 15px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 1.8rem;
            color: white;
            text-decoration: none;
        }
        
        .nav-links {
            display: flex;
            gap: 30px;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: var(--accent-teal);
        }
        
        section { padding: 100px 5%; }
        
        .about { background: var(--earth-beige); }
        
        .section-title {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            text-align: center;
            margin-bottom: 60px;
            color: var(--primary-green);
        }
        
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 40px;
        }
        
        .card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            transition: transform 0.4s ease;
        }
        
        .card:hover { transform: translateY(-15px); }
        
        .card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }
        
        .projects {
            background: linear-gradient(135deg, #0A3D2F 0%, #1A5C4A 100%);
            color: white;
        }
        
        .impact-stats {
            display: flex;
            justify-content: center;
            gap: 60px;
            flex-wrap: wrap;
            margin-top: 60px;
        }
        
        .stat {
            text-align: center;
        }
        
        .stat-number {
            font-size: 3.5rem;
            font-weight: 700;
            color: var(--accent-teal);
        }
        
        .footer {
            background: var(--primary-green);
            color: white;
            text-align: center;
            padding: 80px 20px 40px;
        }
        
        .donate-cta {
            background: var(--warm-orange);
            color: white;
            text-align: center;
            padding: 80px 20px;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#" class="logo">EcoHarmony</a>
        <div class="nav-links">
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#impact">Impact</a>
            <a href="#get-involved">Get Involved</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <section class="hero">
        <div class="hero-content">
            <h1>Harmony with Nature</h1>
            <p class="tagline">Protecting our planet, one community at a time. Join the movement for a sustainable future.</p>
            <a href="#get-involved" class="btn">Donate Today</a>
            <a href="#projects" class="btn" style="background: transparent; border: 2px solid white; margin-left: 20px;">Explore Projects</a>
        </div>
    </section>

    <section id="about" class="about">
        <h2 class="section-title">Our Mission</h2>
        <div class="grid">
            <div class="card">
                <img src="https://picsum.photos/id/1016/600/400" alt="Nature">
                <div class="card-content">
                    <h3>Who We Are</h3>
                    <p>EcoHarmony Foundation is a global NGO dedicated to environmental conservation, community empowerment, and climate action. Founded in 2018, we work across 12 countries to restore ecosystems and build resilient communities.</p>
                </div>
            </div>
            <div class="card">
                <img src="https://picsum.photos/id/133/600/400" alt="Community">
                <div class="card-content">
                    <h3>Our Vision</h3>
                    <p>A world where humanity lives in perfect harmony with nature. We believe in sustainable development that benefits both people and the planet.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="projects">
        <h2 class="section-title" style="color: white;">Our Impactful Projects</h2>
        <div class="grid">
            <div class="card" style="color: #333;">
                <img src="https://picsum.photos/id/1018/600/400" alt="Reforestation">
                <div class="card-content">
                    <h3>Reforestation Initiative</h3>
                    <p>Planted over 2.5 million trees across degraded lands in partnership with local communities.</p>
                    <a href="#" class="btn" style="padding: 10px 25px; font-size: 0.9rem; margin-top: 15px;">Learn More</a>
                </div>
            </div>
            <div class="card" style="color: #333;">
                <img src="https://picsum.photos/id/201/600/400" alt="Ocean Cleanup">
                <div class="card-content">
                    <h3>Ocean Guardians</h3>
                    <p>Removed 150+ tons of plastic from coastal areas and educated thousands on marine conservation.</p>
                    <a href="#" class="btn" style="padding: 10px 25px; font-size: 0.9rem; margin-top: 15px;">Learn More</a>
                </div>
            </div>
            <div class="card" style="color: #333;">
                <img src="https://picsum.photos/id/251/600/400" alt="Education">
                <div class="card-content">
                    <h3>Green Education</h3>
                    <p>Empowered 50,000 students through sustainability workshops and school greening programs.</p>
                    <a href="#" class="btn" style="padding: 10px 25px; font-size: 0.9rem; margin-top: 15px;">Learn More</a>
                </div>
            </div>
        </div>
    </section>

    <section id="impact">
        <h2 class="section-title">Our Global Impact</h2>
        <div class="impact-stats">
            <div class="stat">
                <div class="stat-number">2.5M</div>
                <p>Trees Planted</p>
            </div>
            <div class="stat">
                <div class="stat-number">150K</div>
                <p>People Empowered</p>
            </div>
            <div class="stat">
                <div class="stat-number">42</div>
                <p>Countries Reached</p>
            </div>
            <div class="stat">
                <div class="stat-number">98%</div>
                <p>Project Success Rate</p>
            </div>
        </div>
    </section>

    <section class="donate-cta" id="get-involved">
        <h2 style="font-size: 3rem; margin-bottom: 20px;">Be the Change</h2>
        <p style="font-size: 1.4rem; max-width: 700px; margin: 0 auto 40px;">Your support helps us protect endangered ecosystems and build a greener tomorrow.</p>
        <a href="#" class="btn" style="background: white; color: var(--warm-orange); font-size: 1.3rem; padding: 20px 50px;">Donate Now</a>
    </section>

    <footer class="footer" id="contact">
        <p>&copy; 2026 EcoHarmony Foundation. All Rights Reserved.</p>
        <p style="margin-top: 20px;">Contact: info@ecoharmony.org | +1 (555) 123-4567</p>
        <div style="margin-top: 30px;">
            <a href="#" style="color: white; margin: 0 15px;">Instagram</a>
            <a href="#" style="color: white; margin: 0 15px;">X</a>
            <a href="#" style="color: white; margin: 0 15px;">LinkedIn</a>
        </div>
    </footer>

    <script>
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                if (this.getAttribute('href') !== '#') {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Navbar scroll effect
        window.addEventListener('scroll', () => {
            const nav = document.querySelector('nav');
            if (window.scrollY > 100) {
                nav.style.background = 'rgba(10, 61, 47, 0.98)';
            } else {
                nav.style.background = 'rgba(10, 61, 47, 0.95)';
            }
        });
    </script>
</body>
</html>