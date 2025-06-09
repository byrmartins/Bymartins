<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jojo - Moda Fubanga</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: #fff8f0;
      color: #333;
    }
    header {
      background: url('https://i.imgur.com/bkgOEVU.jpg') no-repeat center center;
      background-size: cover;
      padding: 40px;
      color: #fff;
      text-align: center;
    }
    header h1 {
      font-size: 3em;
      font-weight: bold;
      text-shadow: 2px 2px #000;
    }
    nav {
      background-color: #000;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: #f5c542;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .produtos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 30px;
    }
    .produto {
      background-color: #fff;
      border: 2px solid #f5c542;
      width: 250px;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
    }
    .produto img {
      width: 100%;
      height: auto;
      border-radius: 10px;
    }
    .btn-comprar {
      background-color: #f5c542;
      border: none;
      padding: 10px 20px;
      color: #000;
      font-weight: bold;
      margin-top: 10px;
      cursor: pointer;
    }
    footer {
      background-color: #000;
      color: #f5c542;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Jojo</h1>
    <p>Roupas femininas & acessórios no estilo fubanga 🐆</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Coleção</a>
    <a href="#">Acessórios</a>
    <a href="#">Carrinho</a>
    <a href="#">Contato</a>
  </nav>

  <section class="produtos">
    <div class="produto">
      <img src="https://i.imgur.com/jGOWnCg.jpg" alt="Corset Jojo">
      <h3>Corset Jojo Trap Queen</h3>
      <p>R$ 129,90</p>
      <button class="btn-comprar">Adicionar ao carrinho</button>
    </div>
    <div class="produto">
      <img src="https://i.imgur.com/YjupMde.jpg" alt="Short jeans">
      <h3>Short Jeans Manchado</h3>
      <p>R$ 89,90</p>
      <button class="btn-comprar">Adicionar ao carrinho</button>
    </div>
    <!-- Adicione mais produtos aqui -->
  </section>

  <footer>
    <p>&copy; 2025 Loja Jojo. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
