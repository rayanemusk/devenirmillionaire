# devenirmillionaire
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formation Gratuite sur le Dropshipping</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Formation Gratuite sur le Dropshipping</h1>
        <nav>
            <ul>
                <li><a href="#home">Accueil</a></li>
                <li><a href="#about">À Propos</a></li>
                <li><a href="#program">Programme</a></li>
                <li><a href="#signup">Inscription</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h2>Bienvenue!</h2>
        <p>Découvrez notre formation complète et gratuite sur le dropshipping.</p>
        <img src="URL_IMAGE_ACCUEIL" alt="Image attrayante">
    </section>
    document.querySelector('form').addEventListener('submit', function(event) {
    event.preventDefault();
    alert('Merci pour votre inscription !');
});
    
    <section id="about">
        <h2>À Propos de la Formation</h2>
        <p>Cette formation vous apprendra tout ce que vous devez savoir pour démarrer et réussir dans le dropshipping.</p>
        <img src="URL_IMAGE_ABOUT" alt="À Propos">
    </section>
    
    <section id="program">
        <h2>Programme de la Formation</h2>
        <ul>
            <li>Introduction au Dropshipping</li>
            <li>Étude de Marché</li>
            <li>Modèle Économique</li>
            <li>Stratégie de Produit</li>
            <li>Plan Marketing</li>
            <li>Gestion des Opérations</li>
            <li>Plan Financier</li>
        </ul>
        <img src="URL_IMAGE_PROGRAM" alt="Programme">
    </section>
    
    <section id="signup">
        <h2>Inscrivez-vous Gratuitement</h2>
        <form>
            <label for="name">Nom:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <button type="submit">S'inscrire</button>
        </form>
    </section>
    
    <section id="contact">
        <h2>Contactez-nous</h2>
        <p>Pour toute question, envoyez-nous un email à <a href="mailto:info@dropshippingformation.com">info@dropshippingformation.com</a>.</p>
    </section>
    
    <footer>
        <p>&copy; 2024 Formation Dropshipping. Tous droits réservés.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
}

section img {
    max-width: 100%;
    height: auto;
}

footer {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

form {
    display: flex;
    flex-direction: column;
}

form label, form input {
    margin-bottom: 10px;
}

form button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
}

form button:hover {
    background-color: #45a049;
}
