<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Junta de Acción Comunal Vereda La Garrapata Bienvenidos</title>
  <link rel="icon" href="imagen/Logojac.png" />
  <meta name="description" content="Junta de Acción Comunal Vereda La Garrapata - Caucasia, Antioquia. Comunidad, participación y desarrollo." />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    .fade-in-up {
      animation: fadeInUp 1s ease-out forwards;
    }
    body, html {
      height: 100%;
      margin: 0;
      color: white;
    }
  </style>
</head>
<body class="position-relative overflow-hidden">

  <!-- Fondo de video -->
  <video autoplay muted loop playsinline class="position-absolute top-0 start-0 w-100 h-100 object-fit-cover z-n1">
    <source src="imagen/fondojac.mp4" type="video/mp4" />
    Tu navegador no soporta video HTML5.
  </video>

  <!-- Capa oscura para mejor legibilidad -->
  <div class="position-absolute top-0 start-0 w-100 h-100 bg-black bg-opacity-50 z-0"></div>

  <!-- Contenido principal -->
  <div class="position-relative z-1 d-flex flex-column justify-content-center align-items-center text-center h-100 px-3 fade-in-up">
    <img src="imagen/Logojac.png" alt="Logo JAC" class="mb-4" style="width: 96px; height: 96px; animation-delay: 0.2s" />
    <h1 class="display-5 fw-bold fade-in-up" style="animation-delay: 0.4s">
      Bienvenidos a la Junta de Acción Comunal Vereda la Garrapata
    </h1>
    <p class="lead text-light mt-3 fade-in-up" style="animation-delay: 0.6s">
      Comunidad, participación y desarrollo Jac Vereda la Garrapata, Caucasia Ant.
    </p>
    <div class="d-flex flex-column flex-md-row gap-3 mt-4 fade-in-up" style="animation-delay: 0.8s">
      <a href="home.html" class="btn btn-success px-4 py-2">Entrar al sitio</a>
      <a href="certificado.html" class="btn btn-success px-4 py-2">Entrar a Certificado</a>
    </div>
  </div>

  <!-- Footer -->
  <footer class="position-relative z-1 bg-dark bg-opacity-75 text-center py-3 text-white small">
    <p class="mb-1">&copy; 2025 Junta de Acción Comunal Vereda La Garrapata - Caucasia, Antioquia</p>
    <p class="mb-0">Contacto: junta@garrapata.org | Tel: 312 345 6789</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

