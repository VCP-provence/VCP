<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Distributeur de vins, spiritueux, jus de fruits et boissons artisanales à Marseille. Produits bio, HVE, vegan et grandes maisons. Livraison rapide.">
  <title>Vieilles Caves de Provence</title>
  <style>
    body {
      margin: 0;
      font-family: 'Merriweather', serif;
      background-color: #1a1a1a;
      color: #f9f5ef;
    }
    header {
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1514361892635-e7f51f3d3b53?auto=format&fit=crop&w=1500&q=80') no-repeat center center/cover;
      padding: 100px 20px;
      text-align: center;
      position: relative;
    }
    header img.logo {
      width: 120px;
      position: absolute;
      top: 20px;
      left: 20px;
      background-color: rgba(255, 255, 255, 0.05);
      border-radius: 8px;
      padding: 5px;
    }
    header h1 {
      font-size: 48px;
      color: #f9f5ef;
    }
    header p {
      font-size: 20px;
      margin-top: 10px;
      color: #e5d3b3;
    }
    .cta {
      display: inline-block;
      margin-top: 30px;
      padding: 15px 30px;
      background-color: #7a1e1e;
      color: #fff;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }
    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }
    section h2 {
      color: #e5d3b3;
      font-size: 32px;
      margin-bottom: 20px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }
    .card {
      background-color: #2a2a2a;
      padding: 20px;
      border-radius: 12px;
    }
    .contact, footer {
      background-color: #111;
      padding: 40px 20px;
      color: #f9f5ef;
    }
    .contact a, footer a {
      color: #e5d3b3;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://raw.githubusercontent.com/fucarelos2912/vcp-provence/main/assets/vcp-logo.png" alt="Logo VCP" class="logo">
    <h1>Vieilles Caves de Provence</h1>
    <p>Distributeur de vins, jus, softs et spiritueux pour professionnels et particuliers</p>
    <a href="#contact" class="cta">Demander le catalogue</a>
  </header>

  <section>
    <h2>Qui sommes-nous ?</h2>
    <p>Basés à Marseille, nous distribuons vins, spiritueux, jus et boissons artisanales. Notre sélection valorise les producteurs bio, HVE, vegan, et les grandes maisons reconnues. Nous servons restaurants, bars, cavistes, épiceries, collectivités et particuliers exigeants. Réactivité, stock local, livraisons rapides : notre expertise à votre service.</p>
  </section>

  <section>
    <h2>Nos produits</h2>
    <div class="grid">
      <div class="card">
        <h3>🍷 Vins</h3>
        <p>AOC et IGP : Provence, Languedoc, Vallée du Rhône, Bourgogne, Bordeaux... Rouges, blancs, rosés, formats classiques et magnums.</p>
      </div>
      <div class="card">
        <h3>🥂 Champagnes & Pétillants</h3>
        <p>Maisons : Ruinart, Drappier, Chassenay d’Arce. Vins mousseux, ancestraux, sans alcool.</p>
      </div>
      <div class="card">
        <h3>🥤 Jus & Softs</h3>
        <p>Jus bio Emile Vergeois, bières artisanales, boissons sans alcool.</p>
      </div>
      <div class="card">
        <h3>🥃 Spiritueux</h3>
        <p>Whisky, rhum, vodka, Cap Corse, crèmes, liqueurs locales et internationales.</p>
      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact</h2>
    <p>Une question ? Un devis ? Contactez-nous :</p>
    <p>📍 137 boulevard Longchamps, 13001 Marseille</p>
    <p>📞 04 91 62 21 37</p>
    <p>📧 <a href="mailto:vcp13001@gmail.com">vcp13001@gmail.com</a></p>
  </section>

  <footer>
    <p>© Vieilles Caves de Provence – Tous droits réservés</p>
  </footer>

</body>
</html>
