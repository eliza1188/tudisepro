<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crearte Studio - Diseño Creativo</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="container">
            <h1 class="logo">Crearte Studio</h1>
            <nav>
                <ul class="nav-links">
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#servicios">Servicios</a></li>
                    <li><a href="#portafolio">Portafolio</a></li>
                    <li><a href="#testimonios">Testimonios</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="inicio" class="hero">
        <div class="hero-content">
            <h2>Diseños que Destacan, Soluciones Digitales que Conectan</h2>
            <a href="#servicios" class="btn primary">Conoce nuestros servicios</a>
        </div>
    </section>

    <!-- Sobre Nosotros -->
    <section id="sobre-nosotros" class="about">
        <div class="container">
            <h2 class="section-title">¿Quiénes Somos?</h2>
            <p>En <strong>Crearte Studio</strong>, creemos que el diseño tiene el poder de contar historias, construir marcas y crear conexiones auténticas. Somos un equipo apasionado por transformar ideas en realidades visuales que inspiran.</p>
        </div>
    </section>

    <!-- Servicios -->
    <section id="servicios" class="services">
        <div class="container">
            <h2 class="section-title">Nuestros Servicios</h2>
            <div class="service-grid">
                <div class="service-item">
                    <img src="icons/invitaciones.png" alt="Invitaciones">
                    <h3>Invitaciones Personalizadas</h3>
                    <p>Diseñamos invitaciones únicas para tus momentos más especiales.</p>
                </div>
                <div class="service-item">
                    <img src="icons/instagram.png" alt="Instagram">
                    <h3>Diseño de Feeds de Instagram</h3>
                    <p>Feeds visualmente impactantes y alineados con tu marca.</p>
                </div>
                <div class="service-item">
                    <img src="icons/presentaciones.png" alt="Presentaciones">
                    <h3>Presentaciones WOW</h3>
                    <p>Presentaciones profesionales que sorprenden y comunican con estilo.</p>
                </div>
                <div class="service-item">
                    <img src="icons/videos.png" alt="Videos">
                    <h3>Edición de Videos y Audios</h3>
                    <p>Videos promocionales y reels con calidad profesional.</p>
                </div>
                <div class="service-item">
                    <img src="icons/cv.png" alt="Hojas de vida">
                    <h3>Hojas de Vida Creativas</h3>
                    <p>Impresiona a los reclutadores con CVs modernos y originales.</p>
                </div>
                <div class="service-item">
                    <img src="icons/flyers.png" alt="Flyers">
                    <h3>Flyers y Anuncios Digitales</h3>
                    <p>Promociona tus eventos o servicios con diseños que captan la atención.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Portafolio -->
    <section id="portafolio" class="portfolio">
        <div class="container">
            <h2 class="section-title">Nuestro Trabajo</h2>
            <div class="portfolio-grid">
                <div class="portfolio-item">
                    <img src="project1.jpg" alt="Proyecto 1">
                </div>
                <div class="portfolio-item">
                    <img src="project2.jpg" alt="Proyecto 2">
                </div>
                <div class="portfolio-item">
                    <img src="project3.jpg" alt="Proyecto 3">
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonios -->
    <section id="testimonios" class="testimonials">
        <div class="container">
            <h2 class="section-title">Lo que dicen nuestros clientes</h2>
            <div class="testimonial-carousel">
                <div class="testimonial-item">
                    <p>"Crearte Studio transformó mi marca. Su trabajo es increíble."</p>
                    <h4>- Maria G.</h4>
                </div>
                <div class="testimonial-item">
                    <p>"Excelente atención y diseños que realmente destacan."</p>
                    <h4>- Carlos P.</h4>
                </div>
            </div>
        </div>
    </section>

    <!-- Contacto -->
    <section id="contacto" class="contact">
        <div class="container">
            <h2 class="section-title">Ponte en contacto</h2>
            <form>
                <input type="text" placeholder="Nombre" required>
                <input type="email" placeholder="Correo electrónico" required>
                <textarea placeholder="Tu mensaje" required></textarea>
                <button type="submit" class="btn primary">Enviar mensaje</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 Crearte Studio. Todos los derechos reservados.</p>
        </div>
    </footer>
</body>
</html>
