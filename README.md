<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Carte de restaurant élégante et interactive">
    <title>Carte du Restaurant</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #6a1b9a;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #4a148c;
            padding: 10px 0;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #d1c4e9;
        }

        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        section {
            margin-bottom: 40px;
        }

        section h2 {
            margin-bottom: 10px;
            color: #6a1b9a;
            border-bottom: 2px solid #4a148c;
            display: inline-block;
            padding-bottom: 5px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px solid #ddd;
        }

        ul li:last-child {
            border-bottom: none;
        }

        ul li span {
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #4a148c;
            color: #fff;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue au Restaurant Gourmet</h1>
    </header>
    <nav>
        <a href="#entrees">Entrées</a>
        <a href="#plats">Plats Principaux</a>
        <a href="#desserts">Desserts</a>
        <a href="#boissons">Boissons</a>
    </nav>
    <main>
        <section id="entrees">
            <h2>Entrées</h2>
            <ul>
                <li><span>Soupe à l'oignon</span> <span>7€</span></li>
                <li><span>Salade César</span> <span>8€</span></li>
                <li><span>Foie gras maison</span> <span>12€</span></li>
            </ul>
        </section>

        <section id="plats">
            <h2>Plats Principaux</h2>
            <ul>
                <li><span>Filet de boeuf</span> <span>20€</span></li>
                <li><span>Risotto aux champignons</span> <span>16€</span></li>
                <li><span>Poulet rôti aux herbes</span> <span>18€</span></li>
            </ul>
        </section>

        <section id="desserts">
            <h2>Desserts</h2>
            <ul>
                <li><span>Crème brûlée</span> <span>6€</span></li>
                <li><span>Tarte au citron</span> <span>7€</span></li>
                <li><span>Moelleux au chocolat</span> <span>8€</span></li>
            </ul>
        </section>

        <section id="boissons">
            <h2>Boissons</h2>
            <ul>
                <li><span>Café</span> <span>2€</span></li>
                <li><span>Thé</span> <span>3€</span></li>
                <li><span>Vin rouge (verre)</span> <span>5€</span></li>
            </ul>
        </section>
    </main>
    <footer>
        <p>© 2025 Restaurant Gourmet - Tous droits réservés</p>
    </footer>
</body>
</html>
