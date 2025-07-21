
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Entre Líneas y Latidos</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #f8f5ef;
      color: #1e2d5a;
      scroll-behavior: smooth;
    }
    header {
      background-color: #1e2d5a;
      color: #f8f5ef;
      padding: 20px;
      text-align: center;
      animation: fadeInDown 1.5s ease-in-out;
    }
    nav {
      background-color: #e9e6dd;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      padding: 10px 0;
      animation: fadeIn 2s;
    }
    nav a {
      text-decoration: none;
      color: #1e2d5a;
      font-weight: bold;
    }
    section {
      padding: 40px;
      animation: fadeInUp 1.5s ease-in-out;
    }
    h2 {
      border-bottom: 2px solid #1e2d5a;
      padding-bottom: 10px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #1e2d5a;
      color: #f8f5ef;
    }
    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 20px auto;
    }
    form {
      display: flex;
      flex-direction: column;
      max-width: 400px;
      margin: 0 auto;
      gap: 10px;
    }
    input, textarea, button {
      padding: 10px;
      font-family: inherit;
      font-size: 1em;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #1e2d5a;
      color: #f8f5ef;
      border: none;
      cursor: pointer;
    }
    iframe {
      width: 100%;
      height: 300px;
      border: none;
      margin-top: 20px;
    }
    .icon {
      margin-right: 10px;
    }
    @keyframes fadeInDown {
      0% { opacity: 0; transform: translateY(-20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }
  </style>
</head>
<body>

  <header>
    <h1><i class="fas fa-heartbeat icon"></i>Entre Líneas y Latidos</h1>
    <p>"Todos los días construyes tu identidad"</p>
    <img src="portada.jpg" alt="Portada del sitio">
  </header>

  <nav>
    <a href="#filosofia"><i class="fas fa-lightbulb icon"></i>Filosofía</a>
    <a href="#arte"><i class="fas fa-palette icon"></i>Arte</a>
    <a href="#musica"><i class="fas fa-music icon"></i>Música</a>
    <a href="#lecturas"><i class="fas fa-book icon"></i>Lecturas</a>
    <a href="#contacto"><i class="fas fa-envelope icon"></i>Contacto</a>
  </nav>

  <section id="filosofia">
    <h2><i class="fas fa-brain icon"></i>Filosofía</h2>
    <p>Reflexiones inspiradas en Albert Camus, Séneca y la vida cotidiana.</p>
    <img src="filosofia.jpg" alt="Imagen filosofía">
  </section>

  <section id="arte">
    <h2><i class="fas fa-paint-brush icon"></i>Arte</h2>
    <p>Ideas, artistas, emociones y la belleza de observar el mundo con otros ojos.</p>
    <img src="arte.jpg" alt="Imagen arte">
  </section>

  <section id="musica">
    <h2><i class="fas fa-headphones-alt icon"></i>Música</h2>
    <p>Desde Luis Miguel hasta Kendrick Lamar. Canciones que construyen memorias.</p>
    <iframe src="https://open.spotify.com/embed/playlist/37i9dQZF1DWXRqgorJj26U" allowfullscreen></iframe>
  </section>

  <section id="lecturas">
    <h2><i class="fas fa-book-reader icon"></i>Lecturas</h2>
    <p>Libros que dejan huella: El extranjero, Rulfo, Cortázar y más.</p>
    <img src="libros.jpg" alt="Imagen lecturas">
  </section>

  <section id="contacto">
    <h2><i class="fas fa-comments icon"></i>Contacto</h2>
    <p>¿Te gustaría colaborar o escribirme? ¡Aquí puedes hacerlo!</p>
    <form action="#" method="post">
      <input type="text" name="nombre" placeholder="Tu nombre" required>
      <input type="email" name="email" placeholder="Tu correo electrónico" required>
      <textarea name="mensaje" rows="4" placeholder="Tu mensaje..." required></textarea>
      <button type="submit"><i class="fas fa-paper-plane"></i> Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Entre Líneas y Latidos</p>
  </footer>

</body>
</html>
