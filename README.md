<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Página Inicial</title>
  <style>
    /* Estilo base */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      font-size: 16px;
      color: #333;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Hero section */
    .hero {
      height: 80vh;
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow: hidden;
    }

    .hero-text {
      text-align: center;
      z-index: 1;
      position: relative;
    }

    .hero-text h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    .hero-text p {
      font-size: 1.5rem;
      margin-bottom: 2rem;
    }

    .hero-image {
      position: absolute;
      top: 0;
      left: 0;
      height: 100%;
      width: 100%;
      object-fit: cover;
    }

    /* Services section */
    .services {
      padding: 4rem 2rem;
      text-align: center;
      background-color: #f2f2f2;
    }

    .services h2 {
      font-size: 2.5rem;
      margin-bottom: 2rem;
    }

    .services-container {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
    }

    .service {
      margin: 1rem;
      border: 1px solid #ddd;
      border-radius: 0.5rem;
      overflow: hidden;
      max-width: 300px;
    }

    .service img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .service h3 {
      font-size: 1.5rem;
      margin: 1rem;
    }

    .service p {
      font-size: 1rem;
      margin: 1rem;
    }

    .cta-button {
      display: block;
      background-color: #0077cc;
      color: #fff;
      text-align: center;
      padding: 1rem;
      font-size: 1.2rem;
      border-radius: 0.5rem;
      margin: 1rem;
      transition: background-color 0.3s ease;
    }

    .cta-button:hover {
      background-color: #005fa3;
      cursor: pointer;
    }

    /* Footer section */
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 2rem;
    }

    footer p {
      font-size: 1.2rem;
      margin-bottom: 1rem;
    }

    footer .cta-button {
      display: inline-block;
      background-color: #0077cc;
      color: #fff;
      text-align: center;
      padding: 1rem;
      font-size: 1.2rem;
      border-radius: 0.5rem;
      margin: 1rem;
      transition: background-color 0.3s ease;
    }

    footer .cta-button:hover {
      background-color: #005fa3;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <section class="hero">
    <div class="hero-text">
      <h1>Bem-vindo à minha página inicial</h1>
      <p>Encontre o serviço que atenda às suas necessidades</p>
    </div>
    <img src="background.jpg" alt="Imagem de fundo" class="hero-image">
  </section>
  <section class="services">
    <h2>Nossos serviços</h2>
    <div class="services-container">
      <div class="service">
        <img src="service1.jpg" alt="Serviço 1">
        <h3>Serviço 1</h3>
        <p>Descrição do serviço 1</p>
        <a href="#" class="cta-button">Solicitar serviço</a>
      </div>
      <div class="service">
        <img src="service2.jpg" alt="Serviço 2">
        <h3>Serviço 2</h3>
        <p>Descrição do serviço 2</p>
        <a href="#" class="cta-button">Solicitar serviço</a>
      </div>
      <div class="service">
        <img src="service3.jpg" alt="Serviço 3">
        <h3>Serviço 3</h3>
        <p>Descrição do serviço 3</p>
        <a href="#" class="cta-button">Solicitar serviço</a>
      </div>
    </div>
  </section>
  <footer>
    <p>Entre em contato para mais informações sobre nossos serviços</p>
    <a href="#" class="cta-button">Entre em contato</a>
  </footer>
</body>
</html>
