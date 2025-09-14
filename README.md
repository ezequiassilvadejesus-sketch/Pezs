# Pezs[13/09, 23:43] Ezequias Silva De Jesus: <!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Meu primeiro site">
  <title>Meu Site</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Bem-vindo ao meu site!</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <main>
    <section id="sobre">
      <h2>Sobre</h2>
      <p>Esse é um site de exemplo.</p>
    </section>

    <section id="contato">
      <h2>Contato</h2>
      <form id="form-contato">
        <input type="text" placeholder="Seu nome" required>
        <input type="email" placeholder="Seu email" required>
        <button type="submit">Enviar</button>
      </form>
      <p id="msg"></p>
    </section>
  </main>

  <footer>
    <p>&copy; 2024 Meu Site</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
[13/09, 23:43] Ezequias Silva De Jesus: body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f9f9f9;
}

header {
  background: #007bff;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

section {
  padding: 20px;
  margin: 20px;
  background: white;
  border-radius: 5px;
}

button {
  background: #007bff;
  color: white;
  border: none;
  padding: 10px 15px;
  cursor: pointer;
  border-radius: 3px;
}
[13/09, 23:44] Ezequias Silva De Jesus: // Interação simples no formulário
const form = document.getElementById('form-contato');
const msg = document.getElementById('msg');

form.addEventListener('submit', function(event) {
  event.preventDefault();
  msg.textContent = 'Mensagem enviada com sucesso!';
  form.reset();
});
Ele vai criar personagens de aí,  vai criar  aparência 
