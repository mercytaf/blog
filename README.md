<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>SportLive - Chez Patrick Tshibangu</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #0b0b0b;
      color: #fff;
      margin: 0;
    }
    header {
      background: linear-gradient(90deg, #001f3f, #003366);
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: #0af;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #fff;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      padding: 8px 12px;
      border-radius: 4px;
      transition: 0.3s;
    }
    nav a:hover {
      background-color: #0af;
      color: #000;
    }
    main {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    section {
      margin-bottom: 50px;
    }
    h2 {
      color: #0af;
      border-bottom: 2px solid #0af;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }
    .match-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .match {
      background-color: #1a1a1a;
      width: 220px;
      padding: 20px;
      border-radius: 8px;
      text-align: center;
      text-decoration: none;
      color: #fff;
      box-shadow: 0 0 10px #000;
      transition: 0.3s ease;
    }
    .match:hover {
      background-color: #0af;
      color: #000;
      transform: scale(1.05);
    }
    footer {
      background-color: #111;
      text-align: center;
      padding: 20px;
      color: #666;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <header>
    <h1>SportLive</h1>
    <nav>
      <a href="#">Accueil</a>
      <a href="https://liveball.uno" target="_blank">Matchs en direct</a>
      <a href="#">Replays</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Bienvenue chez Patrick Tshibangu</h2>
      <p>Regardez les meilleurs matchs en direct et suivez toute l'actualité sportive sur votre plateforme 100% passion !</p>
    </section>

    <section>
      <h2>Sports du jour</h2>
      <div class="match-list">
        <a class="match" href="https://liveball.uno/football" target="_blank">
          <strong>Football</strong><br>
          PSG vs Marseille
        </a>
        <a class="match" href="https://liveball.uno/basket" target="_blank">
          <strong>Basket</strong><br>
          Lakers vs Celtics
        </a>
        <a class="match" href="https://liveball.uno/tennis" target="_blank">
          <strong>Tennis</strong><br>
          Roland-Garros - Demi-finales
        </a>
        <a class="match" href="https://liveball.uno/formule1" target="_blank">
          <strong>Formule 1</strong><br>
          Grand Prix de Monaco
        </a>
      </div>
    </section>
  </main>

  <footer>
    © 2025 SportLive - Créé par Patrick Tshibangu. Tous droits réservés.
  </footer>

</body>
</html>
