# 7sevendrink<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>7seven - Boisson Naturelle Ivoirienne</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #fff;
      color: #333;
    }
    header {
      background-color: #e60026;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .section-title {
      font-size: 28px;
      margin-bottom: 20px;
      color: #e60026;
    }
    .ingredients, .saveurs {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .item {
      flex: 1 1 40%;
      background: #f7f7f7;
      padding: 15px;
      border-radius: 10px;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
    }
    a {
      color: #e60026;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>7seven</h1>
    <p>L'&eacute;nergie naturelle made in C&ocirc;te d'Ivoire</p>
  </header>

  <section>
    <h2 class="section-title">Nos Ingr&eacute;dients</h2>
    <div class="ingredients">
      <div class="item"><strong>Bissap :</strong> riche en antioxydants, saveur acidul&eacute;e</div>
      <div class="item"><strong>Gingembre :</strong> tonifiant, stimulant naturel</div>
      <div class="item"><strong>Citron vert :</strong> source de vitamine C</div>
      <div class="item"><strong>Baobab :</strong> fibres, vitamines et go&ucirc;t unique</div>
    </div>
  </section>

  <section>
    <h2 class="section-title">Nos Saveurs</h2>
    <div class="saveurs">
      <div class="item">Bissap Original</div>
      <div class="item">Bissap-Gingembre</div>
      <div class="item">Baobab-Citron</div>
      <div class="item">Nouvelles saveurs &agrave; venir...</div>
    </div>
  </section>

  <section>
    <h2 class="section-title">O&ugrave; nous trouver ?</h2>
    <p>Disponible prochainement dans les supermarch&eacute;s d'Abidjan.<br />
    Int&eacute;ress&eacute; pour devenir distributeur ? <a href="#contact">Contactez-nous</a>.</p>
  </section>

  <section id="contact">
    <h2 class="section-title">Contact</h2>
    <p>Email : contact@7sevenboissonenergetique.com<br />
    WhatsApp : +225 07 89 44 11 32<br />
    Instagram : <a href="https://instagram.com/7seven">@7seven</a></p>
  </section>

  <footer>
    <p>&copy; 2025 7seven – Boisson naturelle ivoirienne</p>
  </footer>
</body>
</html>
