<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MasterClass de Guitarra Pro - Aprende con Expertos</title>
    <!-- Bootstrap CSS CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;800&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            color: #333;
        }
        h1, h2, h3, h4, h5, h6 {
            font-family: 'Montserrat', sans-serif;
        }
        .hero-section {
            background: linear-gradient(rgba(0, 0, 0, 0.75), rgba(179, 0, 0, 0.6)), url('https://images.unsplash.com/photo-1511379938547-c1f69419868d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80') center/cover;
            color: white;
            padding: 120px 0;
            text-align: center;
        }
        .section-title {
            font-weight: 800;
            text-transform: uppercase;
            margin-bottom: 50px;
            color: #1a1a1a;
        }
        .benefit-icon {
            font-size: 2.5rem;
            color: #b30000;
            margin-bottom: 20px;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            transition: transform 0.3s ease;
        }
    </style>
</head>
<body>

    <!-- 1. HEADER & NAVBAR -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top shadow">
            <div class="container">
                <a class="navbar-brand fw-bold text-uppercase" href="#">Acordes<span class="text-danger">&</span>Teclas</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                    <ul class="navbar-nav align-items-center gap-3">
                        <li class="nav-item"><a class="nav-link" href="#beneficios">Beneficios</a></li>
                        <li class="nav-item"><a class="nav-link" href="#cursos">Cursos</a></li>
                        <li class="nav-item"><a class="nav-link" href="#testimonios">Testimonios</a></li>
                        <li class="nav-item"><a href="#inscripcion" class="btn btn-danger btn-sm text-uppercase fw-bold px-4 py-2">Inscríbete Ya</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <main style="margin-top: 56px;">

        <!-- 2. HERO / MASTHEAD & CTA -->
        <section class="hero-section">
            <div class="container">
                <span class="badge bg-danger text-uppercase px-3 py-2 mb-3 fs-6">Cupos Limitados 2026</span>
                <h1 class="display-3 fw-bold mb-4">Domina la Guitarra Desde Cero a Pro</h1>
                <p class="lead mb-5 mx-auto" style="max-width: 700px;">Aprende las técnicas avanzadas, teoría musical aplicada y los secretos de los grandes guitarristas con nuestro método 100% práctico.</p>
                <a href="#inscripcion" class="btn btn-danger btn-lg text-uppercase fw-bold px-5 py-3 shadow">
                    Comprar ahora - S/ 149.00
                </a>
            </div>
        </section>

        <!-- 3. BENEFICIOS -->
        <section id="beneficios" class="py-5 bg-light">
            <div class="container py-5">
                <h2 class="text-center section-title">¿Por qué elegir esta MasterClass?</h2>
                <div class="row g-4 text-center">
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100 card-hover">
                            <div class="benefit-icon">🎸</div>
                            <h4>Acceso de Por Vida</h4>
                            <p class="text-muted">Estudia a tu propio ritmo, desde cualquier dispositivo y con actualizaciones gratuitas para siempre.</p>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100 card-hover">
                            <div class="benefit-icon">📜</div>
                            <h4>Certificado Oficial</h4>
                            <p class="text-muted">Obtén un diploma avalado por nuestra academia al finalizar satisfactoriamente todos los módulos.</p>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100 card-hover">
                            <div class="benefit-icon">👥</div>
                            <h4>Comunidad Privada</h4>
                            <p class="text-muted">Accede a un grupo exclusivo de Discord para resolver dudas directamente con instructores profesionales.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 4. SERVICIOS / PRODUCTOS (CURSOS) -->
        <section id="cursos" class="py-5">
            <div class="container py-5">
                <h2 class="text-center section-title">Nuestros Programas Destacados</h2>
                <div class="row g-4">
                    <div class="col-md-4">
                        <div class="card h-100 shadow-sm card-hover border-0">
                            <img src="images (1).jpg" class="card-img-top" alt="Curso Guitarra">
                            <div class="card-body d-flex flex-column">
                                <span class="badge bg-dark text-white align-self-start mb-2">Nivel Principiante</span>
                                <h5 class="card-title fw-bold">Fundamentos de Guitarra Acústica</h5>
                                <p class="card-text text-muted">Acordes abiertos, ritmos esenciales y tus primeras 10 canciones completas en 4 semanas.</p>
                                <div class="mt-auto d-flex justify-content-between align-items-center pt-3 border-top">
                                    <span class="fs-4 fw-bold text-danger">S/ 99.00</span>
                                    <a href="#inscripcion" class="btn btn-outline-dark btn-sm text-uppercase fw-bold">Ver más</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card h-100 shadow-sm card-hover border-0">
                            <img src="MAESTRIA.jpg" class="card-img-top" alt="Curso Guitarra Electrica">
                            <div class="card-body d-flex flex-column">
                                <span class="badge bg-danger text-white align-self-start mb-2">Nivel Intermedio</span>
                                <h5 class="card-title fw-bold">Maestría en Guitarra Eléctrica</h5>
                                <p class="card-text text-muted">Pentatónicas, técnicas de solo, bending, sweep picking y uso avanzado de efectos.</p>
                                <div class="mt-auto d-flex justify-content-between align-items-center pt-3 border-top">
                                    <span class="fs-4 fw-bold text-danger">S/ 149.00</span>
                                    <a href="#inscripcion" class="btn btn-outline-dark btn-sm text-uppercase fw-bold">Ver más</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card h-100 shadow-sm card-hover border-0">
                            <img src="https://images.unsplash.com/photo-1552422535-c45813c61732?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" class="card-img-top" alt="Curso Teclados">
                            <div class="card-body d-flex flex-column">
                                <span class="badge bg-secondary text-white align-self-start mb-2">Multidisciplinario</span>
                                <h5 class="card-title fw-bold">Teclado y Arreglos Musicales</h5>
                                <p class="card-text text-muted">Harmonización moderna, lectura de partituras y acompañamiento para bandas en vivo.</p>
                                <div class="mt-auto d-flex justify-content-between align-items-center pt-3 border-top">
                                    <span class="fs-4 fw-bold text-danger">S/ 129.00</span>
                                    <a href="#inscripcion" class="btn btn-outline-dark btn-sm text-uppercase fw-bold">Ver más</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 5. TESTIMONIOS -->
        <section id="testimonios" class="py-5 bg-light">
            <div class="container py-5">
                <h2 class="text-center section-title">Lo que dicen nuestros estudiantes</h2>
                <div class="row g-4">
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100">
                            <p class="text-muted fst-italic">"Nunca pensé que podría tocar solos de guitarra fluidos en tan poco tiempo. Las explicaciones son directas al grano."</p>
                            <h6 class="fw-bold mb-0 text-dark">— Carlos Mendoza</h6>
                            <small class="text-danger">Estudiante de Guitarra Eléctrica</small>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100">
                            <p class="text-muted fst-italic">"La plataforma es excelente y el soporte de los profesores en el canal privado resuelve cualquier traba técnica."</p>
                            <h6 class="fw-bold mb-0 text-dark">— Lucía Torres</h6>
                            <small class="text-danger">Estudiante de Piano</small>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100">
                            <p class="text-muted fst-italic">"Relación calidad-precio insuperable. Los recursos descargables y las pistas de práctica valen oro."</p>
                            <h6 class="fw-bold mb-0 text-dark">— Mateo Silva</h6>
                            <small class="text-danger">Estudiante Avanzado</small>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 6. LLAMADA A LA ACCIÓN (INSCRIPCIÓN) -->
        <section id="inscripcion" class="py-5 bg-dark text-white text-center">
            <div class="container py-5">
                <div class="alert alert-danger d-inline-block px-4 py-2 mb-3 fw-bold text-uppercase" role="alert">
                    ⚠️ ¡Últimas horas con 50% de descuento!
                </div>
                <h2 class="fw-bold mb-3">Transforma tu talento musical hoy mismo</h2>
                <p class="lead mb-4 mx-auto" style="max-width: 600px;">Únete a más de 5,000 estudiantes satisfechos y empieza tu camino hacia el profesionalismo.</p>
                <a href="#" class="btn btn-danger btn-lg text-uppercase fw-bold px-5 py-3 shadow">
                    Comprar ahora por S/ 149.00
                </a>
            </div>
        </section>

    </main>

    <!-- 7. FOOTER & SUB-FOOTER -->
    <footer class="bg-black text-secondary py-5 text-center">
        <div class="container">
            <h3 class="text-white fw-bold mb-2">Acordes & Teclas</h3>
            <p class="mb-4">La academia líder en formación musical online en el Perú.</p>
            <div class="border-top border-secondary pt-4 text-muted small">
                <p>&copy; 2026 Acordes & Teclas. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS Bundle CDN -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
