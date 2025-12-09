<?php
session_start();

$secret = "6LdmtSUsAAAAAG567RoPJokDkr4r3C0dCLmOuSRo"; // SECRET KEY DE GOOGLE

// Si no se ha verificado el captcha → mostrar pantalla de verificación
if (!isset($_SESSION['captcha_ok'])) {

    // Si el usuario envió el formulario de captcha
    if (isset($_POST['g-recaptcha-response'])) {

        $response = $_POST['g-recaptcha-response'];
        $verify = file_get_contents("https://www.google.com/recaptcha/api/siteverify?secret={$secret}&response={$response}");
        $captcha_success = json_decode($verify);

        if ($captcha_success->success) {
            $_SESSION['captcha_ok'] = true; // Guardar sesión
            header("Location: index.php");
            exit;
        } else {
            $error = "❌ Verificación incorrecta. Intenta de nuevo.";
        }
    }

    // FORMULARIO DE CAPTCHA
    ?>
    <!doctype html>
    <html lang="es">
    <head>
        <meta charset="UTF-8">
        <title>Verificación | Axel Velasco</title>
        <script src="https://www.google.com/recaptcha/api.js" async defer></script>

        <style>
            body {
                background-color: #000;
                color: white;
                font-family: Arial;
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;
                margin: 0;
            }
            .box {
                padding: 30px;
                background: #111;
                border-radius: 10px;
                text-align: center;
                width: 350px;
                box-shadow: 0 0 20px rgba(0,0,0,0.5);
            }
            button {
                background: #0d6efd;
                border: none;
                padding: 10px 25px;
                border-radius: 5px;
                color: white;
                cursor: pointer;
                margin-top: 20px;
            }
            button:hover {
                background: #0b5ed7;
            }
        </style>
    </head>
    <body>

    <div class="box">
        <h2>Verificación de Acceso</h2>
        <p>Por favor verifica que no eres un robot para acceder a mi página.</p>

        <?php if (!empty($error)) echo "<p style='color:red;'>{$error}</p>"; ?>

        <form method="POST">
            <div class="g-recaptcha" data-sitekey="6LdmtSUsAAAAABsr8JjAAz3qNc5chCk4dvwoflF-"></div>
            <button type="submit">Entrar</button>
        </form>
    </div>

    </body>
    </html>
    <?php
    exit;
}
?>

<!--
SI EL USUARIO YA PASÓ EL CAPTCHA,
DE AQUÍ PARA ABAJO SE MUESTRA TU PÁGINA COMPLETA
-->
<!doctype html>
<html lang="es">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="Axel Velasco">
    <title>Mis Logros | Axel Velasco</title>    

    <link href="css/bootstrap.min.css" rel="stylesheet">

    <style>
      body {
        background-color: #000;
        color: #fff;
      }
      .navbar {
        background-color: #0d6efd !important;
        padding-top: 1rem;
        padding-bottom: 1rem;
      }
      .navbar-brand, .nav-link {
        color: #fff !important;
        font-weight: 500;
      }
      .nav-link:hover {
        text-decoration: underline;
      }
      h2 {
        color: #0d6efd;
        font-weight: bold;
        margin-bottom: 1rem;
        text-shadow: 0 0 15px rgba(13, 110, 253, 0.8), 0 0 30px rgba(13, 110, 253, 0.5);
      }
      h4 {
        color: #0dcaf0;
        margin-top: 2rem;
        margin-bottom: 1rem;
        text-transform: uppercase;
        text-shadow: 0 0 10px rgba(13, 202, 240, 0.8), 0 0 20px rgba(13, 202, 240, 0.4);
      }
      ul li {
        margin-bottom: 0.5rem;
        font-size: 1.05rem;
      }
      footer {
        background-color: #111;
        padding: 1rem 0;
      }
      footer span {
        color: #aaa;
      }
      .carousel img {
        border-radius: 10px;
      }

      /* Animación de brillo */
      @keyframes glow {
        from {
          text-shadow: 0 0 10px rgba(13, 110, 253, 0.7), 0 0 20px rgba(13, 110, 253, 0.4);
        }
        to {
          text-shadow: 0 0 20px rgba(13, 110, 253, 1), 0 0 40px rgba(13, 110, 253, 0.8);
        }
      }

      h2:hover {
        animation: glow 1.5s infinite alternate;
      }
    </style>
  </head>

  <body>
    <main>
      <div class="container mb-5">

        <!-- Navbar -->
        <header class="d-flex flex-wrap py-3 mb-5 border-bottom">
          <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
            <div class="container">
              <a class="navbar-brand" href="#">Axel Velasco</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <!-- Enlaces a la derecha -->
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                  <li class="nav-item">
                    <a class="nav-link" href="index.html">Acerca de mí</a>                    
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" href="metas.html">Mis metas</a>                    
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="contacto.html">Contacto</a>                    
                  </li>
                </ul>
              </div>
            </div>
          </nav>
        </header>

        <!-- Carousel -->
<div class="row justify-content-center mt-4">
  <div id="carouselExampleCaptions" class="carousel slide col-md-8" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"></button>
    </div>

    <div class="carousel-inner text-center">
      <div class="carousel-item active">
        <img src="img/carru1.jpg" class="d-block mx-auto img-fluid rounded shadow" style="max-width: 69%; height: auto;" alt="Imagen 1">
      </div>
      <div class="carousel-item">
        <img src="img/carru2.jpg" class="d-block mx-auto img-fluid rounded shadow" style="max-width: 92%; height: auto;" alt="Imagen 2">
      </div>
      <div class="carousel-item">
        <img src="img/carru3.jpg" class="d-block mx-auto img-fluid rounded shadow" style="max-width: 90.6%; height: auto;" alt="Imagen 3">
      </div>
    </div>

    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
      <span class="carousel-control-prev-icon"></span>
      <span class="visually-hidden">Anterior</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon"></span>
      <span class="visually-hidden">Siguiente</span>
    </button>
  </div>
</div>

        <!-- MIS LOGROS -->
        <div class="row">
          <div class="text-center mt-5 mb-3">

            <!-- linea arriba -->
            <hr style="border: 1px solid white; width: 100%; margin-bottom: 25px;">

            <h2>Mis Logros</h2>

            <!-- linea abajo -->
            <hr style="border: 1px solid white; width: 100%; margin-top: 25px;">
          </div>

          <div class="col-12">
            <div class="p-4">

              <h4>1.🎓 Formación Académica y Técnica</h4>
              <ul>
                <li>Estudiante de la carrera de Informática, con interés en el desarrollo de software, redes y sistemas operativos.</li>
                <li>Participación activa en proyectos escolares relacionados con auditoría informática, bases de datos y administración de servidores.</li>
                <li>Conocimientos sólidos en programación, sistemas operativos Linux y Windows, redes y seguridad informática.</li>
              </ul>

              <h4>2.💻 Proyectos Relevantes</h4>
              <ul>
                <li><strong>Proyecto “Café Aroma”:</strong> Diseño y desarrollo de una base de datos para gestionar inventario, pedidos y ventas de una cafetería.</li>
                <li>Instalación y configuración de un servidor DNS en Ubuntu Server, administrando usuarios y permisos.</li>
                <li>Auditoría de hardware con herramientas como WinAudit y System Profiler, aplicada a un laboratorio escolar.</li>
                <li>Desarrollo de sitios web con HTML, CSS y PHP, implementando menús y navegación moderna.</li>
              </ul>

              <h4>3.🏅 Logros Académicos y Personales</h4>
              <ul>
                <li>Reconocido por la responsabilidad y trabajo en equipo en proyectos grupales.</li>
                <li>Elaboración de informes técnicos y documentación profesional en formato IEEE.</li>
                <li>Mejora continua en el manejo de entornos cliente-servidor y programación de aplicaciones distribuidas.</li>
                <li>Interés constante por aprender nuevas tecnologías y herramientas del ámbito TI.</li>
              </ul>

              <h4>4.⚙️ Habilidades Destacadas</h4>
              <ul>
                <li><strong>Lenguajes de programación:</strong> Python, Java, PHP, CSS.</li>
                <li>Administración básica de redes, servidores y sistemas operativos Linux.</li>
                <li>Manejo de software de auditoría, virtualización y bases de datos.</li>
                <li>Trabajo colaborativo y capacidad para resolver problemas técnicos.</li>
              </ul>

            </div>
          </div>
        </div>
      </div>
    </main>

    <!-- Footer -->
    <footer class="footer mt-auto">
      <div class="container text-center">
        <span class="text-muted">© Axel Velasco 
          <script>document.write(new Date().getFullYear());</script>
        </span>
      </div>
    </footer>

    <!-- Archivo JS Bootstrap 5 -->  
    <script src="js/bootstrap.bundle.min.js"></script>
  </body>
</html>