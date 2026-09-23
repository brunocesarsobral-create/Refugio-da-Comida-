i# Refu-gio-da-Comida-
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Refúgio da Comida | Marmitas</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #fff8ef;
      color: #333;
    }

    header {
      background: #8b2e1e;
      color: white;
      text-align: center;
      padding: 30px 15px;
    }

    header h1 {
      font-size: 36px;
      margin-bottom: 8px;
    }

    header p {
      font-size: 18px;
    }

    .hero {
      text-align: center;
      padding: 45px 20px;
      background: #f4d2a8;
    }

    .hero h2 {
      font-size: 32px;
      color: #7a2417;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 25px;
    }

    .botao {
      display: inline-block;
      background: #25d366;
      color: white;
      text-decoration: none;
      padding: 15px 25px;
      border-radius: 30px;
      font-size: 18px;
      font-weight: bold;
    }

    .cardapio {
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .cardapio h2 {
      text-align: center;
      color: #8b2e1e;
      margin-bottom: 30px;
      font-size: 30px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      border-radius: 15px;
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(0,0,0,0.12);
      text-align: center;
      padding-bottom: 20px;
    }

    .card img {
      width: 100%;
      height: 190px;
      object-fit: cover;
    }

    .card h3 {
      color: #8b2e1e;
      margin: 15px 10px 8px;
      font-size: 21px;
    }

    .card p {
      padding: 0 15px;
      line-height: 1.5;
    }

    .preco {
      display: block;
      margin: 15px 0;
      font-size: 24px;
      font-weight: bold;
      color: #d35400;
    }

    .pedido {
      background: #8b2e1e;
      color: white;
      text-align: center;
      padding: 45px 20px;
    }

    .pedido h2 {
      font-size: 30px;
      margin-bottom: 15px;
    }

    .pedido p {
      font-size: 18px;
      margin-bottom: 25px;
    }

    footer {
      background: #42150e;
      color: white;
      text-align: center;
      padding: 25px 15px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 29px;
      }

      .hero h2 {
        font-size: 26px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>🍲 REFÚGIO DA COMIDA</h1>
    <p>Comida caseira, saborosa e feita com carinho!</p>
  </header>

  <section class="hero">
    <h2>Uma comida que dá vontade de repetir!</h2>
    <p>Marmitas deliciosas para o seu almoço, todos os dias.</p>

    <a class="botao"
       href="https://wa.me/5511966620625"
       target="_blank">
       📲 Pedir pelo WhatsApp
    </a>
  </section>

  <section class="cardapio">

    <h2>🍛 Nosso Cardápio</h2>

    <div class="cards">

      <div class="card">
        <img src="https://images.unsplash.com/photo-1547592180-85f173990554?auto=format&fit=crop&w=800&q=80"
             alt="Marmita de comida caseira">

        <h3>Marmita Tradicional</h3>

        <p>Arroz, feijão, acompanhamento, salada e proteína.</p>

        <span class="preco">A partir de R$ 22,00</span>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1515003197210-e0cd71810b5f?auto=format&fit=crop&w=800&q=80"
             alt="Prato de comida caseira">

        <h3>Marmita Executiva</h3>

        <p>Uma refeição completa e caprichada para o seu dia.</p>

        <span class="preco">A partir de R$ 25,00</span>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1547592180-85f173990554?auto=format&fit=crop&w=800&q=80"
             alt="Marmita saborosa">

        <h3>Marmita Especial</h3>

        <p>Porções generosas e proteínas especiais.</p>

        <span class="preco">A partir de R$ 29,00</span>
      </div>

    </div>
  </section>

  <section class="pedido">
    <h2>📲 Faça seu pedido!</h2>

    <p>
      Chame o Refúgio da Comida pelo WhatsApp
      e consulte o cardápio do dia.
    </p>

    <a class="botao"
       href="https://wa.me/5511966620625"
       target="_blank">
       Fazer pedido agora
    </a>
  </section>

  <footer>
    <p>REFÚGIO DA COMIDA</p>
    <p>Comida caseira feita com carinho ❤️</p>
  </footer>

</body>
</html>
