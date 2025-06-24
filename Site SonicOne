
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SonicOne - Loja de Eletrônicos</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #000;
      color: #fff;
    }

    .navbar {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0.75rem 2rem;
      background-color: #000;
      color: white;
      z-index: 1000;
      border-bottom: 2px solid #e60000;
    }

    .navbar .logo {
      font-size: 1.5rem;
      font-weight: bold;
      color: #e60000;
    }

    .navbar .nav-links a {
      color: white;
      text-decoration: none;
      margin: 0 0.75rem;
      font-size: 0.95rem;
      transition: color 0.3s;
    }

    .navbar .nav-links a:hover {
      color: #e60000;
    }

    .hero {
      position: relative;
      width: 100%;
      height: 92vh;
      margin-top: 60px;
      overflow: hidden;
    }

    .carousel {
      display: flex;
      width: 300%;
      height: 100%;
      animation: slide 15s infinite;
    }

    .carousel img {
      width: 100vw;
      height: 100%;
      object-fit: cover;
    }

    @keyframes slide {
      0% { transform: translateX(0); }
      33% { transform: translateX(-100vw); }
      66% { transform: translateX(-200vw); }
      100% { transform: translateX(0); }
    }

    .hero-content {
      position: absolute;
      top: 55%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: white;
      text-align: center;
      background: rgba(0, 0, 0, 0.4);
      padding: 2rem;
      border-radius: 10px;
    }

    .hero-content h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .hero-content button {
      background-color: #fff;
      color: #000;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 25px;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .hero-content button:hover {
      background-color: #e60000;
      color: #fff;
    }

    footer {
      background-color: #000;
      color: white;
      padding: 3rem 2rem;
    }

    .footer-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2rem;
      margin-bottom: 2rem;
    }

    .footer-grid h4 {
      margin-bottom: 1rem;
      color: #e60000;
    }

    .footer-grid ul {
      list-style: none;
    }

    .footer-grid ul li {
      margin-bottom: 0.5rem;
    }

    .footer-grid ul li a {
      color: #ccc;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    .footer-grid ul li a:hover {
      color: #e60000;
    }

    .footer-feedback {
      text-align: center;
    }

    .footer-feedback textarea {
      width: 100%;
      max-width: 500px;
      padding: 0.75rem;
      border: none;
      border-radius: 5px;
      margin-bottom: 1rem;
    }

    .footer-feedback button {
      background-color: #e60000;
      color: #000;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 4px;
      cursor: pointer;
    }

    .footer-feedback button:hover {
      background-color: #b30000;
    }

    .copyright {
      text-align: center;
      font-size: 0.875rem;
      color: #888;
    }
  </style>
</head>
<body>
  <header class="navbar">
    <div class="logo">SonicOne</div>
    <nav class="nav-links">
      <a href="Págin inicial.html">Início</a>
      <a href="Página produtos.html">Produtos</a>
      <a href="sobre.html">Sobre</a>
      <a href="Contato.html">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <div class="carousel">
      <img src="AirPods Pro.webp" alt="Promoção Airpods">
      <img src="Galaxy Buds 2 Pro.png" alt="Promoção Galaxy Buds">
      <img src="Sony WH-1000XM5.png" alt="Promoção Sony WH-1000XM5">
    </div>
    <div class="hero-content">
      <h1>Ofertas Incríveis Esperam Por Você</h1>
      <button onclick="window.location.href='Página produtos.html'">Ver Produtos</button>
    </div>
  </section>

  <footer>
    <div class="footer-grid">
      <div>
        <h4>Empresa</h4>
        <ul>
          <li><a href="sobre.html">Sobre nós</a></li>
          <li><a href="construção.html">Carreiras</a></li>
          <li><a href="construção.html">Loja Física</a></li>
        </ul>
      </div>
      <div>
        <h4>Atendimento</h4>
        <ul>
          <li><a href="Contato.html">Fale conosco</a></li>
          <li><a href="Contato.html">Trocas e devoluções</a></li>
          <li><a href="Contato.html">Suporte</a></li>
        </ul>
      </div>
      <div>
        <h4>Redes Sociais</h4>
        <ul>
          <li><a href="construção.html">Instagram</a></li>
          <li><a href="construção.html">Facebook</a></li>
          <li><a href="construção.html">YouTube</a></li>
        </ul>
      </div>
    </div>
    <div class="footer-feedback">
      <form onsubmit="feedbackIndisponivel(); return false;">
        <textarea id="feedback" rows="4" placeholder="Deixe seu feedback..." required></textarea><br>
        <button type="submit">Enviar</button>
      </form>
    </div>
    
    <script>
      function feedbackIndisponivel() {
        alert('Não foi possível enviar. Este site é apenas uma simulação educacional.');
        document.getElementById('feedback').value = '';
      }
    </script>
    
    <div class="copyright">
      &copy; 2025 SonicOne. Todos os direitos reservados.
    </div>
  </footer>
</body>
</html>
