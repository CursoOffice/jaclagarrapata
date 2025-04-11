<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Junta de Acción Comunal Vereda La Garrapata Bienvenidos</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    .fade-in-up {
      animation: fadeInUp 1s ease-out forwards;
    }
  </style>
</head>
<body class="relative text-white overflow-hidden">

  <!-- Fondo de video -->
  <video autoplay muted loop playsinline class="absolute inset-0 w-full h-full object-cover z-0">
    <source src="imagen/fondojac (1).mp4" type="video/mp4" />
    Tu navegador no soporta video HTML5.
  </video>

  <!-- Capa oscura para mejor legibilidad -->
  <div class="absolute inset-0 bg-black bg-opacity-50 z-10"></div>

  <!-- Contenido sobre el video -->
  <div class="relative z-20 flex flex-col items-center justify-center h-screen text-center px-6">
    <img src="imagen/_Logojac-removebg-preview (1).png" alt="Logo JAC" class="w-24 h-24 mb-4 fade-in-up" style="animation-delay: 0.2s" />
    <h1 class="text-3xl md:text-4xl font-bold fade-in-up" style="animation-delay: 0.4s">
      Bienvenidos a la Junta de Acción Comunal Vereda la Garrapata
    </h1>
    <p class="text-md md:text-lg text-gray-200 mt-4 fade-in-up" style="animation-delay: 0.6s">
      Comunidad, participación y desarrollo Jac Vereda la Garrapata, Caucasia Ant.
    </p>
    <a href="home.html" class="mt-8 inline-block bg-green-600 text-white px-6 py-3 rounded-full hover:bg-green-700 transition fade-in-up" style="animation-delay: 0.8s">
      Entrar al sitio
    </a>
    <a href="certificado.html" class="mt-8 inline-block bg-green-600 text-white px-6 py-3 rounded-full hover:bg-green-700 transition fade-in-up" style="animation-delay: 0.8s">
      Entrar a Certificado
    </a>
  </div>

</body>
</html>
