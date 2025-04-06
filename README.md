<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>José Gregorio González - Técnico Profesional</title>
  <style>
    * {
      margin: 0; padding: 0; box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #111;
      color: #fff;
      scroll-behavior: smooth;
    }

    header {
      background: url('https://img.freepik.com/vector-premium/trabajador-mantenimiento-centro-servicio-electrodomesticos-reparando-personal-mantenimiento-clientes-renovacion-hogar_654623-948.jpg') center center / cover no-repeat;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      position: relative;
      animation: fadeIn 2s ease-in-out;
    }

    header::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background-color: rgba(0, 0, 0, 0.5);
    }

    .intro {
      position: relative;
      z-index: 2;
      max-width: 90%;
      animation: slideDown 2s ease;
    }

    .intro h1 {
      font-size: 2.5rem;
      color: yellow;
      margin-bottom: 1rem;
      text-shadow: 2px 2px 4px #000;
    }

    .intro p {
      font-size: 1.2rem;
      color: #eee;
      text-shadow: 1px 1px 3px #000;
    }

    @keyframes fadeIn {
      from { opacity: 0; } to { opacity: 1; }
    }

    @keyframes slideDown {
      from { transform: translateY(-40px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    section {
      padding: 3rem 1rem;
      text-align: center;
    }

    .profile img {
      width: 130px;
      border-radius: 50%;
      border: 4px solid yellow;
      margin-bottom: 1rem;
      box-shadow: 0 0 10px yellow;
    }

    h2 {
      font-size: 2rem;
      color: yellow;
      margin-bottom: 1rem;
    }

    p {
      max-width: 800px;
      margin: auto;
      color: #ccc;
      font-size: 1rem;
    }

    .whatsapp {
      display: inline-block;
      margin-top: 1.5rem;
      padding: 1rem 2rem;
      background: yellow;
      color: black;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      animation: pulse 2s infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }

    .services {
      background-color: #222;
    }

    .services ul {
      list-style: none;
      padding: 0;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1rem;
      max-width: 1000px;
      margin: auto;
    }

    .services li {
      background: #333;
      padding: 1.5rem;
      border-left: 5px solid yellow;
      border-radius: 10px;
      transition: 0.3s ease;
    }

    .services li:hover {
      background: #444;
      transform: translateY(-5px);
    }

    .contact {
      background: #1a1a1a;
    }

    .contact p {
      margin-bottom: 1rem;
    }

    footer {
      background: #000;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      color: #bbb;
    }

    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: white;
      padding: 15px;
      border-radius: 50%;
      font-size: 25px;
      z-index: 999;
      box-shadow: 0 0 10px #25d366;
      transition: 0.3s ease;
      text-align: center;
    }

    .whatsapp-float:hover {
      transform: scale(1.1);
    }

    @media (max-width: 768px) {
      header {
        height: 80vh;
      }

      .intro h1 {
        font-size: 2rem;
      }

      .intro p {
        font-size: 1rem;
      }

      h2 {
        font-size: 1.5rem;
      }

      p {
        font-size: 0.95rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="intro">
      <h1>José Gregorio González</h1>
      <p>Técnico de confianza para tus electrodomésticos</p>
    </div>
  </header>

  <section class="profile">
    <img src="https://i.pinimg.com/236x/d0/66/fa/d066fa64ac3db395903dc9a280e1756c.jpg" alt="José Gregorio">
    <h2>¿Quién soy?</h2>
    <p>Soy un técnico especializado en reparación de electrodomésticos: neveras, lavadoras, microondas, televisores, aires acondicionados y más. Ofrezco soluciones rápidas, efectivas y con garantía. Atención personalizada y experiencia comprobada en todo Barranquilla.</p>
    <a class="whatsapp" href="https://wa.me/573212949163" target="_blank">💬 Escríbeme por WhatsApp</a>
  </section>

  <section class="services">
    <h2>Servicios que ofrezco</h2>
    <ul>
      <li>🧊 Reparación de neveras y congeladores</li>
      <li>🌀 Arreglo de lavadoras automáticas y semi</li>
      <li>🔥 Microondas y hornos eléctricos</li>
      <li>❄️ Aires acondicionados (instalación y reparación)</li>
      <li>🔧 Diagnóstico y mantenimiento preventivo</li>
      <li>🛠️ Cambio de repuestos originales</li>
    </ul>
  </section>

  <section class="contact">
    <h2>Contáctame</h2>
    <p>📍 Ubicación: Barranquilla, Colombia</p>
    <p>📞 Teléfono y WhatsApp: <strong>+57 321 2949163</strong></p>
    <p>🕒 Atención: Lunes a Sábado - 8:00am a 6:00pm</p>
    <a class="whatsapp" href="https://wa.me/573212949163" target="_blank">💬 Solicitar servicio</a>
  </section>

  <footer>
    &copy; 2025 José Gregorio González - Todos los derechos reservados
  </footer>

  <a class="whatsapp-float" href="https://wa.me/573212949163" target="_blank">💬</a>

</body>
</html>
