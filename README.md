<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Billetterie Festival SunWave</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, sans-serif;
      background: linear-gradient(135deg, #ff0080, #7928ca, #2afadf);
      color: #fff;
    }

    header {
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    .tickets {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
      padding: 40px;
      max-width: 1100px;
      margin: auto;
    }

    .ticket {
      background: rgba(255, 255, 255, 0.15);
      border-radius: 20px;
      padding: 25px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.25);
      backdrop-filter: blur(10px);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .ticket:hover {
      transform: translateY(-8px) scale(1.02);
      box-shadow: 0 20px 40px rgba(0,0,0,0.35);
    }

    .ticket h2 {
      margin-top: 0;
      font-size: 1.6rem;
    }

    .price {
      font-size: 2rem;
      font-weight: bold;
      margin: 15px 0;
      color: #ffe600;
    }

    ul {
      padding-left: 20px;
      margin-bottom: 20px;
    }

    button {
      width: 100%;
      padding: 14px;
      border: none;
      border-radius: 30px;
      background: linear-gradient(135deg, #ffea00, #ff9f00);
      color: #000;
      font-size: 1rem;
      font-weight: bold;
      cursor: pointer;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    button:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    }

    footer {
      text-align: center;
      padding: 25px;
      font-size: 0.9rem;
      opacity: 0.85;
    }
  </style>
</head>
<body>

  <header>
    <h1>🎶 SunWave Festival 2026 🎉</h1>
    <p>3 jours de musique, de soleil et de vibes incroyables</p>
  </header>

  <section class="tickets">
    <div class="ticket">
      <h2>Pass 1 Jour</h2>
      <p class="price">49 €</p>
      <ul>
        <li>Accès à 1 journée</li>
        <li>Concerts & DJ sets</li>
        <li>Zones food & chill</li>
      </ul>
      <button>Acheter</button>
    </div>

    <div class="ticket">
      <h2>Pass 3 Jours</h2>
      <p class="price">119 €</p>
      <ul>
        <li>Accès complet 3 jours</li>
        <li>Artistes internationaux</li>
        <li>After-parties incluses</li>
      </ul>
      <button>Acheter</button>
    </div>

    <div class="ticket">
      <h2>Pass VIP ✨</h2>
      <p class="price">199 €</p>
      <ul>
        <li>Accès 3 jours</li>
        <li>Espace VIP & bar privé</li>
        <li>Entrée coupe-file</li>
      </ul>
      <button>Acheter</button>
    </div>
  </section>

  <footer>
    © 2026 SunWave Festival – Musique • Couleurs • Liberté
  </footer>

</body>
</html>
