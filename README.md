# mazighcherifi.github.io
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mazigh CHERIFI - Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --accent: #e74c3c;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f8f9fa;
        }
        .navbar-brand {
            font-weight: bold;
            color: var(--primary) !important;
        }
        .hero {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            padding: 100px 0;
        }
        .section-title {
            color: var(--primary);
            margin-bottom: 2rem;
            position: relative;
        }
        .section-title::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 60px;
            height: 3px;
            background: var(--secondary);
        }
        .skill-card {
            background: white;
            border-radius: 10px;
            padding: 2rem;
            margin-bottom: 1.5rem;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .skill-card:hover {
            transform: translateY(-5px);
        }
        .project-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
        }
        .timeline {
            position: relative;
            padding-left: 2rem;
        }
        .timeline::before {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            bottom: 0;
            width: 2px;
            background: var(--secondary);
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm">
        <div class="container">
            <a class="navbar-brand" href="#">Mazigh CHERIFI</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">À propos</a></li>
                    <li class="nav-item"><a class="nav-link" href="#skills">Compétences</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projets</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero text-center">
        <div class="container">
            <h1 class="display-4 fw-bold">Mazigh CHERIFI</h1>
            <p class="lead">Étudiant en Bac Pro Systèmes Numériques</p>
            <p>Passionné par les nouvelles technologies et le développement</p>
            <a href="#contact" class="btn btn-light btn-lg mt-3">Me contacter</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-5">
        <div class="container">
            <h2 class="section-title">À propos de moi</h2>
            <div class="row">
                <div class="col-md-6">
                    <p>Je m'appelle Mazigh CHERIFI, j'ai 19 ans et je suis titulaire d'un Baccalauréat Professionnel Systèmes Numériques. Actuellement en formation au CNED, je me spécialise dans le domaine des technologies numériques.</p>
                </div>
                <div class="col-md-6">
                    <p>Passionné par l'informatique et l'électronique depuis mon plus jeune âge, j'aime comprendre le fonctionnement des systèmes et créer des solutions innovantes.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-5 bg-light">
        <div class="container">
            <h2 class="section-title">Mes compétences</h2>
            <div class="row">
                <div class="col-md-6">
                    <div class="skill-card">
                        <h4><i class="fas fa-microchip me-2"></i>Électronique</h4>
                        <p>Conception et dépannage de circuits électroniques</p>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="skill-card">
                        <h4><i class="fas fa-network-wired me-2"></i>Réseaux</h4>
                        <p>Configuration et gestion de réseaux informatiques</p>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="skill-card">
                        <h4><i class="fas fa-code me-2"></i>Programmation</h4>
                        <p>HTML, CSS, JavaScript, Python, Arduino</p>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="skill-card">
                        <h4><i class="fas fa-robot me-2"></i>Systèmes embarqués</h4>
                        <p>Programmation de microcontrôleurs et IoT</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-5">
        <div class="container">
            <h2 class="section-title">Mes projets</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="project-card">
                        <div class="p-4">
                            <h4>Station météo connectée</h4>
                            <p>Conception d'une station météo autonome avec Arduino</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="project-card">
                        <div class="p-4">
                            <h4>Site web personnel</h4>
                            <p>Développement de mon portfolio en HTML/CSS/JS</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="project-card">
                        <div class="p-4">
                            <h4>Système d'alarme</h4>
                            <p>Création d'un système d'alarme domestique intelligent</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5 bg-dark text-white">
        <div class="container">
            <h2 class="section-title text-white">Contact</h2>
            <div class="row">
                <div class="col-md-6">
                    <p><i class="fas fa-envelope me-2"></i>mazigh.cherifi@example.com</p>
                    <p><i class="fas fa-phone me-2"></i>+33 6 12 34 56 78</p>
                </div>
                <div class="col-md-6">
                    <div class="d-flex gap-3">
                        <a href="#" class="text-white"><i class="fab fa-github fa-2x"></i></a>
                        <a href="#" class="text-white"><i class="fab fa-linkedin fa-2x"></i></a>
                        <a href="#" class="text-white"><i class="fab fa-twitter fa-2x"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
