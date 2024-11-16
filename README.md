<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deoxy Store - Loja de Kits</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #4caf50;
      color: white;
      padding: 15px 20px;
      text-align: center;
    }

    .container {
      max-width: 800px;
      margin: 20px auto;
      padding: 10px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    .kit {
      border-bottom: 1px solid #ddd;
      padding: 15px 0;
      display: flex;
      align-items: center;
    }

    .kit img {
      width: 50px;
      height: 50px;
      margin-right: 15px;
    }

    .kit:last-child {
      border-bottom: none;
    }

    .kit-info {
      flex: 1;
    }

    .kit h3 {
      margin: 0;
      font-size: 18px;
      color: #333;
    }

    .kit p {
      margin: 5px 0;
      color: #666;
      font-size: 14px;
    }

    .kit button {
      background-color: #4caf50;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 14px;
    }

    .kit button:hover {
      background-color: #45a049;
    }

    footer {
      text-align: center;
      padding: 10px;
      background-color: #4caf50;
      color: white;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Deoxy Store</h1>
    <p>Escolha o kit ideal para sua aventura!</p>
  </header>

  <div class="container">
    <div class="kit">
      <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/c/c7/Coal_JE2_BE2.png" alt="Kit Carvão">
      <div class="kit-info">
        <h3>Kit Carvão</h3>
        <p>Kit simples com recursos de diamante.</p>
        <p><strong>Preço:</strong> 10 moedas</p>
      </div>
      <button>Comprar</button>
    </div>
    <div class="kit">
      <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/9/99/Iron_Ingot_JE2_BE2.png" alt="Kit Ferro">
      <div class="kit-info">
        <h3>Kit Ferro</h3>
        <p>Kit mediano, itens de diamante encantados e bônus semanal.</p>
        <p><strong>Preço:</strong> 15 moedas</p>
      </div>
      <button>Comprar</button>
    </div>
    <div class="kit">
      <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/c/ca/Diamond_JE3_BE3.png" alt="Kit Diamante">
      <div class="kit-info">
        <h3>Kit Diamante</h3>
        <p>Kit avançado, itens de diamante com encantamentos e elytra + bônus semanal.</p>
        <p><strong>Preço:</strong> 25 moedas</p>
      </div>
      <button>Comprar</button>
    </div>
    <div class="kit">
      <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/0/0e/Netherite_Ingot_JE1_BE1.png" alt="Kit Netherite">
      <div class="kit-info">
        <h3>Kit Netherite</h3>
        <p>Kit máximo: itens de netherite e elytra + bônus semanal.</p>
        <p><strong>Preço:</strong> 35 moedas</p>
      </div>
      <button>Comprar</button>
    </div>
  </div>

  <footer>
    <p>Deoxy Store © 2024 - Todos os direitos reservados.</p>
  </footer>
</body>
</html>
