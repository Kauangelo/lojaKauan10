# lojaKauan10
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sua Loja</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Loja Kauan</h1>
    <nav>
      <ul>
        <li><a href="#produtos">Produtos</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>
  
  <section id="produtos">
    <h2>Produtos em Destaque</h2>
    <div class="produto">
      <img src="produto1.jpg" alt="Produto 1">
      <p>Produto 1</p>
      <p>R$ 100,00</p>
      <button>Comprar</button>
    </div>
    <!-- Adicione mais produtos aqui -->
  </section>

  <section id="contato">
    <h2>Entre em Contato</h2>
    <form action="mailto:seuemail@dominio.com" method="POST" enctype="text/plain">
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome" required>
      <label for="email">E-mail:</label>
      <input type="email" id="email" name="email" required>
      <label for="mensagem">Mensagem:</label>
      <textarea id="mensagem" name="mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Loja Kauan - Todos os direitos reservados</p>
  </footer>
  
  <script src="script.js"></script>
</body>
</html>
