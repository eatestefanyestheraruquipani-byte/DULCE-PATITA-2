<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dulce Patita - Minipostres</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #fffaf5;
      color: #4b2e1f;
    }
    header {
      background-color: #6B4226;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background-color: #FFA500;
      padding: 10px;
    }
    section {
      padding: 20px;
    }
    .hero {
      background-color: #f5e1d4;
      text-align: center;
      padding: 40px 20px;
    }
    .hero img {
      width: 150px;
    }
    .productos {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }
    .producto {
      border: 1px solid #e0c6b5;
      border-radius: 12px;
      padding: 15px;
      width: 200px;
      text-align: center;
      background-color: #fff;
    }
    .producto h3 {
      margin-bottom: 5px;
    }
    .afiliacion input, .afiliacion button {
      display: block;
      margin: 10px 0;
      padding: 10px;
      width: 100%;
      max-width: 400px;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 30px;
      text-decoration: none;
    }
    footer {
      background-color: #6B4226;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://cdn-icons-png.flaticon.com/512/616/616408.png" alt="Logo Patita" width="60" />
    <h1>Dulce Patita</h1>
    <p>"Una ayuda dulce a patitas reales"</p>
  </header>  <nav>
    <a href="#productos">Productos</a>
    <a href="#afiliacion">Afíliate</a>
    <a href="#tiktok">TikToks</a>
    <a href="#descarga">Descarga</a>
  </nav>  <section class="hero">
    <h2>Minipostres Destacados</h2>
    <div class="productos">
      <div class="producto">
        <h3>Tiramisú</h3>
        <p>Precio: 8 Bs</p>
      </div>
      <div class="producto">
        <h3>Brownies</h3>
        <p>Precio: 7 Bs</p>
      </div>
    </div>
  </section>  <section id="afiliacion">
    <h2>Afíliate</h2>
    <p>Recibe promociones y sé parte de la causa.</p
