# <!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Villemandeur Auto École</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <nav>
      <ul>
        <li><a href="#accueil">Accueil</a></li>
        <li><a href="#renseignements">Renseignements</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#avis">Avis Clients</a></li>
        <li><a href="#compte">Le Compte</a></li>
      </ul>
    </nav>
    <h1>Villemandeur Auto École</h1>
    <div class="hero">
      <img src="bmw-s1-s2.jpg" alt="BMW Série 1 et 2" />
      <p>Découvrez nos BMW Série 1 et 2 de 2024 pour vos cours de conduite</p>
    </div>
  </header>

  <main>
    <section id="accueil">
      <h2>Bienvenue à Villemandeur Auto École</h2>
      <p>Des cours de conduite dans un cadre moderne et professionnel, avec les BMW Série 1 et 2 de 2024.</p>
    </section>

    <section id="renseignements">
      <h2>Renseignements</h2>
      <p><strong>Adresse :</strong> 123 Rue de Villemandeur, 45210 Villemandeur, France</p>
      <p><strong>Email :</strong> contact@villemandeurautoecole.fr</p>
      <p><strong>Téléphone :</strong> 01 23 45 67 89</p>
    </section>

    <section id="contact">
      <h2>Contactez-nous</h2>
      <form action="#">
        <label for="name">Nom</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Message</label>
        <textarea id="message" name="message" required></textarea>
        
        <button type="submit">Envoyer</button>
      </form>
    </section>

    <section id="avis">
      <h2>Avis Clients</h2>
      <div class="testimonial">
        <p>"Une auto-école sérieuse et professionnelle, avec des voitures modernes et une équipe très compétente."</p>
        <p>- Jean D.</p>
      </div>
    </section>

    <section id="compte">
      <h2>Mon Compte</h2>
      <p>Connectez-vous pour réserver vos leçons de conduite et suivre votre progression.</p>
      <button>Se connecter</button>
    </section>
  </main>

  <footer>
    <p>&copy; 2024 Villemandeur Auto École</p>
  </footer>

</body>
</html>
