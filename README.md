<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luxentry - Conciergerie de Luxe</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap');
        body {
            font-family: 'Playfair Display', serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }
        header {
            background: url('header-background.jpeg') center/cover no-repeat;
            color: #fff;
            padding: 50px 20px;
            text-align: center;
            position: relative;
        }
        header img {
            position: absolute;
            top: 20px;
            left: 20px;
            width: 80px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgba(0, 0, 0, 0.8);
            padding: 15px;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            color: #fff;
            margin: 0 20px;
            text-decoration: none;
            font-size: 18px;
            transition: transform 0.3s ease-in-out;
        }
        nav a:hover {
            transform: scale(1.1);
            color: gold;
        }
        .container {
            width: 90%;
            margin: auto;
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
        }
        .section img {
            width: 100%;
            border-radius: 10px;
            margin-top: 15px;
        }
        .button-container {
            text-align: center;
            margin: 20px 0;
        }
        .btn {
            background-color: gold;
            color: #000;
            padding: 12px 20px;
            border: none;
            cursor: pointer;
            font-size: 16px;
            margin: 10px;
            transition: all 0.3s ease-in-out;
            border-radius: 5px;
            text-decoration: none;
        }
        .btn:hover {
            background-color: darkgoldenrod;
            transform: scale(1.1);
        }
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Luxentry Logo">
        <h1>Luxentry - Conciergerie de Luxe</h1>
    </header>
    <nav>
        <a href="#accueil">Accueil</a>
        <a href="#services">Nos Services</a>
        <a href="#transport">Transport</a>
        <a href="#hotels">Hôtels</a>
        <a href="#activites">Activités</a>
        <a href="#contact">Contact</a>
        <a href="#mentions">Mentions Légales</a>
    </nav>
    <div class="container">
        <section id="accueil" class="section">
            <h2>Bienvenue chez Luxentry</h2>
            <p>Votre conciergerie de luxe pour des voyages sur-mesure. Nous organisons chaque détail pour un séjour inoubliable.</p>
            <img src="images.jpeg" alt="Voyage de Luxe">
        </section>
        <section id="services" class="section">
            <h2>Nos Services</h2>
            <p>Découvrez nos services exclusifs allant des voyages personnalisés aux expériences inoubliables.</p>
            <div class="button-container">
                <a href="#transport" class="btn">Transport</a>
                <a href="#hotels" class="btn">Hôtels</a>
                <a href="#activites" class="btn">Activités</a>
            </div>
        </section>
        <section id="transport" class="section">
            <h2>Transport de Luxe</h2>
            <p>Nous proposons des jets privés, limousines et yachts pour vos déplacements.</p>
            <img src="classe-affaire.jpg" alt="Jet privé">
        </section>
        <section id="hotels" class="section">
            <h2>Hébergements de Prestige</h2>
            <p>Des villas privées, hôtels 5 étoiles et resorts exclusifs.</p>
            <img src="hotels-luxe-dubai.jpg" alt="Hôtel de luxe">
        </section>
        <section id="activites" class="section">
            <h2>Activités Exclusives</h2>
            <p>Expériences VIP, événements privés, découvertes gastronomiques et bien plus.</p>
            <img src="VIP.jpg" alt="Événement privé">
        </section>
        <section id="contact" class="section">
            <h2>Contactez-nous</h2>
            <p>Email : <a href="mailto:contact@luxentry.com">contact@luxentry.com</a></p>
            <p>Téléphone : 06 58 02 75 63</p>
        </section>
        <section id="mentions" class="section">
            <h2>Mentions Légales</h2>
            <p>Luxentry SARL, 37 Avenue Louis Enjolras, France</p>
            <p>SIRET : 123 456 789 00000</p>
            <p>Hébergeur : OVH, 2 Rue Kellermann, 59100 Roubaix, France</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 Luxentry - Tous droits réservés.</p>
    </footer>
</body>
</html>
