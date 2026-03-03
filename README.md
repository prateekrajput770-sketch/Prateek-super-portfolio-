<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Prateek Singh | Startup Founder Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: #0f172a;
            color: #f1f5f9;
            line-height: 1.6;
        }

        a {
            text-decoration: none;
            color: #38bdf8;
        }

        section {
            padding: 60px 20px;
            max-width: 1100px;
            margin: auto;
        }

        h1, h2, h3 {
            margin-bottom: 20px;
        }

        .btn {
            display: inline-block;
            padding: 12px 24px;
            background: #38bdf8;
            color: #0f172a;
            border-radius: 8px;
            font-weight: 600;
            transition: 0.3s;
        }

        .btn:hover {
            background: #0ea5e9;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding-top: 80px;
        }

        .hero img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #38bdf8;
            margin-bottom: 20px;
        }

        .hero h1 {
            font-size: 2.5rem;
        }

        .hero p {
            font-size: 1.1rem;
            color: #cbd5e1;
            margin-bottom: 20px;
        }

        /* Skills Section */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .skill-card {
            background: #1e293b;
            padding: 20px;
            border-radius: 12px;
            transition: 0.3s;
        }

        .skill-card:hover {
            transform: translateY(-5px);
            background: #334155;
        }

        .highlight {
            color: #38bdf8;
            font-weight: 600;
        }

        /* Experience Section */
        .experience-item {
            margin-bottom: 30px;
            background: #1e293b;
            padding: 20px;
            border-radius: 12px;
        }

        .experience-item h3 {
            margin-bottom: 5px;
        }

        .experience-item span {
            font-size: 0.9rem;
            color: #94a3b8;
        }

        /* Contact Section */
        .contact-links a {
            display: inline-block;
            margin-right: 15px;
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #020617;
            font-size: 0.9rem;
            color: #64748b;
        }

        /* Responsive */
        @media (max-width: 600px) {
            .hero h1 {
                font-size: 1.8rem;
            }

            .hero img {
                width: 120px;
                height: 120px;
            }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <section class="hero">
        <!-- Replace src with your photo -->
        <img src="your-photo.jpg" alt="Prateek Singh Photo Placeholder">
        <h1>Prateek Singh</h1>
        <p>Aspiring <span class="highlight">Next-Generation Startup Founder</span> building impactful digital solutions.</p>
        <a href="#contact" class="btn">Contact Me</a>
    </section>

    <!-- About Section -->
    <section>
        <h2>About Me</h2>
        <p>
            I am Prateek Singh, a focused and ambitious entrepreneur dedicated to building innovative digital products. 
            My goal is to create scalable startups that solve real-world problems and generate long-term impact.
        </p>
    </section>

    <!-- Skills Section -->
    <section>
        <h2>Skills & Strengths</h2>
        <div class="skills-grid">
            <div class="skill-card">
                <h3>Startup Vision</h3>
                <p>Strong strategic thinking with a founder mindset and long-term growth planning.</p>
            </div>
            <div class="skill-card">
                <h3>Product Development</h3>
                <p>Understanding of app building, MVP strategy, and user-focused product design.</p>
            </div>
            <div class="skill-card">
                <h3>Digital Marketing</h3>
                <p>Knowledge of content strategy, branding, and audience building.</p>
            </div>
            <div class="skill-card">
                <h3>Web & Tech</h3>
                <p>Basic HTML, CSS, and modern web tools to bring ideas to life.</p>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section>
        <h2>Experience</h2>

        <div class="experience-item">
            <h3>Founder - Your Startup Name</h3>
            <span>Year – Present</span>
            <p>
                Leading product development, business strategy, and growth planning for an emerging startup concept.
                Focused on solving practical problems through technology.
            </p>
        </div>

        <div class="experience-item">
            <h3>Independent Projects</h3>
            <span>Year – Year</span>
            <p>
                Built and experimented with digital products, content platforms, and online business models 
                to gain real-world experience in execution and learning.
            </p>
        </div>

    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Let’s connect and build something impactful.</p>
        <div class="contact-links">
            <!-- Replace # with your actual links -->
            <a href="#" target="_blank">LinkedIn</a>
            <a href="#" target="_blank">GitHub</a>
            <a href="#" target="_blank">Twitter</a>
            <a href="mailto:your-email@example.com">Email</a>
        </div>
    </section>

    <footer>
        © 2026 Prateek Singh. All Rights Reserved.
    </footer>

</body>
</html>
