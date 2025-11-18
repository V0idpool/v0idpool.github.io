<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Software Developer & Open Source Contributor</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;500;700&display=swap" rel="stylesheet">
    
    <meta name="description" content="[Your Name]'s personal developer page, showcasing projects, skills, and open-source contributions.">
    <meta property="og:title" content="Your Name | Developer" />
    <meta property="og:url" content="https://yourusername.github.io" />
    <link rel="icon" type="image/png" href="path/to/your/favicon.png" />

    <style>
/* --- Custom Styles from BotPulse Example --- */

/* Apply Ubuntu font family to body */
body {
    font-family: 'Ubuntu', sans-serif;
    background-color: #121212; /* Darker background for a sleek look */
    color: #e0e0e0;
}

/* Card Hover Effect */
.card-hover:hover {
    transform: translateY(-10px);
    box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.4);
    transition: all 0.3s ease-in-out;
}

/* Hero Section */
.hero-section {
    /* **Replace with your own background image URL if desired, otherwise remove or use a solid color** */
    /* background-image: url('path/to/your/background.jpg'); */ 
    background-color: #1a1a1a; /* Solid dark color as fallback/alternative */
    background-size: cover;
    background-position: center;
    color: #ffffff;
    height: 55vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    border-bottom: 3px solid #b71349;
}

.hero-content {
    background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent overlay for text readability */
    padding: 30px;
    border-radius: 15px;
    max-width: 1000px;
}

.hero-title {
    font-size: 3rem;
    font-weight: 700;
    color: #d40045; /* Darker red accent for title */
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8);
}


.hero-subtitle {
    font-size: 1.5rem;
    font-weight: 400;
    color: #ffffff;
}

/* Custom Primary Button (matches BotPulse red) */
.btn-primary1 {
    background-color: #b71349; /* Primary Accent Red */
    border-color: #b71349;
    font-size: 1.2rem;
    color: #ffffff;
    transition: all 0.3s ease;
}

.btn-primary1:hover {
    background-color: #8b2946; /* Darker red on hover */
    border-color: #8b2946;
}

.section-title {
    font-size: 2.5rem;
    font-weight: 700;
    margin-bottom: 2rem;
    color: #b71349; /* Accent Red */
}

/* Call to Action Section (used for projects/skills) */
.cta-section {
    background-color: #1a1a1a; /* Dark neutral background */
    padding: 50px 0;
    color: #ffffff;
    text-align: center;
    border-top: 3px solid #8b2946; /* Darker red accent */
}

.cta-content {
    max-width: 800px;
    margin: 0 auto;
}

/* Footer */
.footer {
    background-color: #2b2b2b;
    color: #e0e0e0;
    padding: 20px;
    text-align: center;
    border-top: 2px solid #b71349;
}

/* Highlighted Banner */
.highlighted-links {
    background-color: #444444; /* Dark gray for the banner */
    color: #eeeeee;
    text-align: center;
    padding: 10px 0;
    font-size: 0.9rem;
}

/* Navbar adjustments to match spacing and dark theme */
.navbar-brand {
    font-weight: 700;
    color: #ffffff !important;
}

.nav-link {
    color: #e0e0e0 !important;
}

.bg-dark {
    background-color: #212121 !important; /* Slightly darker than default bg-dark */
}

    </style>
</head>

<body>

    <div class="highlighted-links">
        👋 Welcome to my GitHub Pages site! See my latest project below.
    </div>
    
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark" style="padding: 30px 15px;">
        <div class="container-fluid container">
            <a class="navbar-brand" href="/">
                **[Your Name]**
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
                
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fa-solid fa-house"></i> Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#projects"><i class="fa-solid fa-code"></i> Projects</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#skills"><i class="fa-solid fa-bolt"></i> Skills</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="https://github.com/YourUsername" target="_blank"><i class="fa-brands fa-github"></i> GitHub</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link btn btn-primary1 btn-sm text-white d-flex align-items-center justify-content-center" href="mailto:youremail@example.com">
                            <i class="fa-solid fa-envelope" style="margin-right: 8px;"></i>  
                            <span>Contact Me</span>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <section class="hero-section">
        <div class="hero-content">
            <h1 class="hero-title">[Your Name]</h1>
            <p class="hero-subtitle">Software Developer | Open Source Enthusiast</p>
            <p>Welcome to my corner of the internet. I focus on modern web development, scalable systems, and contributing to open-source projects.</p>
            <ul style="list-style-type: none;display: flex;padding: 0;margin: 20px 0;justify-content: center; gap: 20px;">
                <li><a href="https://github.com/YourUsername" target="_blank" class="text-white"><i class="fa-brands fa-github fa-2x"></i></a></li>
                <li><a href="https://linkedin.com/in/YourProfile" target="_blank" class="text-white"><i class="fa-brands fa-linkedin fa-2x"></i></a></li>
                <li><a href="https://twitter.com/YourHandle" target="_blank" class="text-white"><i class="fa-brands fa-x-twitter fa-2x"></i></a></li>
            </ul>
            <a class="btn btn-primary1 text-white" href="#projects">View Projects</a>
            <a class="btn btn-primary1 text-white" href="path/to/your/resume.pdf" target="_blank">Download Resume</a>
        </div>
    </section>
    
    <section class="cta-section" id="projects">
        <div class="container">
            <div class="cta-content">
                <h2 class="section-title">Featured Projects</h2>
                <p>Check out some of my recent work and contributions.</p>
                
                <div class="row text-center mt-5">
                    <div class="col-md-4 mb-4">
                        <div class="card card-hover h-100 bg-dark border-secondary">
                            <div class="card-body">
                                <i class="fa-solid fa-cubes fa-3x mb-3" style="color: #d40045;"></i>
                                <h5 class="card-title text-white">Project One</h5>
                                <p class="card-text text-light">A brief description of your first major project, technologies used (e.g., React, Node.js).</p>
                                <a href="#" class="btn btn-sm btn-primary1">View Details</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 mb-4">
                        <div class="card card-hover h-100 bg-dark border-secondary">
                            <div class="card-body">
                                <i class="fa-solid fa-terminal fa-3x mb-3" style="color: #d40045;"></i>
                                <h5 class="card-title text-white">Project Two</h5>
                                <p class="card-text text-light">An open-source library or utility tool. Highlight a key feature or benefit.</p>
                                <a href="#" class="btn btn-sm btn-primary1">View Details</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 mb-4">
                        <div class="card card-hover h-100 bg-dark border-secondary">
                            <div class="card-body">
                                <i class="fa-solid fa-database fa-3x mb-3" style="color: #d40045;"></i>
                                <h5 class="card-title text-white">Project Three</h5>
                                <p class="card-text text-light">A full-stack application demonstrating database and API design skills.</p>
                                <a href="#" class="btn btn-sm btn-primary1">View Details</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <section class="cta-section" id="skills" style="border-top: none;">
        <div class="container">
            <h2 class="section-title">Technical Skills</h2>
            <div class="row">
                <div class="col-12">
                    <span class="badge badge-pill badge-primary1 p-3 m-2" style="background-color: #b71349;">JavaScript / TypeScript</span>
                    <span class="badge badge-pill badge-primary1 p-3 m-2" style="background-color: #b71349;">React / Vue / Angular</span>
                    <span class="badge badge-pill badge-primary1 p-3 m-2" style="background-color: #b71349;">Python / Go</span>
                    <span class="badge badge-pill badge-primary1 p-3 m-2" style="background-color: #b71349;">Node.js / Express</span>
                    <span class="badge badge-pill badge-primary1 p-3 m-2" style="background-color: #b71349;">SQL / NoSQL (e.g., MongoDB)</span>
                    <span class="badge badge-pill badge-primary1 p-3 m-2" style="background-color: #b71349;">AWS / Azure / GCP</span>
                    <span class="badge badge-pill badge-primary1 p-3 m-2" style="background-color: #b71349;">Docker / Kubernetes</span>
                    </div>
            </div>
        </div>
    </section>


    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 [Your Name]. All rights reserved.</p>
            <p class="mb-0">
                <a href="https://github.com/YourUsername" class="text-light" style="text-decoration: none;">GitHub</a> |
                <a href="mailto:youremail@example.com" class="text-light" style="text-decoration: none;">Email</a>
            </p>
        </div>
    </footer>
    
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
