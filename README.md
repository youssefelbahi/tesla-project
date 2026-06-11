# menu-delicieux
Mon dossier (med Youssef el bahi)
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu Délicieux - Organisation</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- HEADER -->
    <header class="header">
        <div class="header-content">
            <h1>🍽️ Menu Délicieux 🍽️</h1>
            <p class="tagline">Savourez l'excellence culinaire française</p>
            <p class="description">Découvrez nos plats préparés avec passion et ingrédients de qualité</p>
        </div>
    </header>

    <!-- NAVIGATION -->
    <nav class="navbar">
        <div class="nav-container">
            <ul class="nav-menu">
                <li><a href="#home" class="nav-link active">Accueil</a></li>
                <li><a href="#entrees" class="nav-link">Entrées</a></li>
                <li><a href="#plats" class="nav-link">Plats Principaux</a></li>
                <li><a href="#desserts" class="nav-link">Desserts</a></li>
                <li><a href="#contact" class="nav-link">Réservation</a></li>
            </ul>
        </div>
    </nav>

    <!-- MAIN CONTENT -->
    <main class="main-content">
        <!-- SECTION ENTRÉES -->
        <section id="entrees" class="menu-section">
            <div class="section-header">
                <h2 class="section-title">🥗 Entrées</h2>
                <p class="section-subtitle">Des saveurs délicates pour bien commencer</p>
            </div>

            <div class="menu-grid">
                <!-- Item 1 -->
                <article class="menu-card">
                    <div class="card-header">
                        <h3 class="card-title">Bruschetta aux Tomates</h3>
                        <span class="card-price">12€</span>
                    </div>
                    <p class="card-description">Tomates fraîches, mozzarella, et basilic avec un filet de vinaigre balsamique.</p>
                    <div class="card-tags">
                        <span class="tag">Végétarien</span>
                        <span class="tag">Frais</span>
                    </div>
                </article>

                <!-- Item 2 -->
                <article class="menu-card">
                    <div class="card-header">
                        <h3 class="card-title">Soupe de Lentilles</h3>
                        <span class="card-price">8€</span>
                    </div>
                    <p class="card-description">Une soupe chaude parfumée au cumin et au citron, servie avec du pain grillé.</p>
                    <div class="card-tags">
                        <span class="tag">Végétarien</span>
                        <span class="tag">Réconfortant</span>
                    </div>
                </article>

                <!-- Item 3 -->
                <article class="menu-card">
                    <div class="card-header">
                        <h3 class="card-title">Salade César</h3>
                        <span class="card-price">11€</span>
                    </div>
                    <p class="card-description">Laitue croquante, sauce César crémeuse, croutons et poulet grillé.</p>
                    <div class="card-tags">
                        <span class="tag">Poulet</span>
                        <span class="tag">Léger</span>
                    </div>
                </article>
            </div>
        </section>

        <!-- SECTION PLATS PRINCIPAUX -->
        <section id="plats" class="menu-section">
            <div class="section-header">
                <h2 class="section-title">🍖 Plats Principaux</h2>
                <p class="section-subtitle">Nos spécialités culinaires</p>
            </div>

            <div class="menu-grid">
                <!-- Item 1 -->
                <article class="menu-card">
                    <div class="card-header">
                        <h3 class="card-title">Saumon Grillé</h3>
                        <span class="card-price">24€</span>
                    </div>
                    <p class="card-description">Pavé de saumon assaisonné et grillé à la perfection, servi avec une sauce au beurre citronné.</p>
                    <div class="card-tags">
                        <span class="tag">Poisson</span>
                        <span class="tag">Sauce citron</span>
                    </div>
                </article>

                <!-- Item 2 -->
                <article class="menu-card">
                    <div class="card-header">
                        <h3 class="card-title">Steak de Bœuf</h3>
                        <span class="card-price">28€</span>
                    </div>
                    <p class="card-description">Une pièce de bœuf tendre grillée, servie avec une purée de pommes de terre et sauce aux champignons.</p>
                    <div class="card-tags">
                        <span class="tag">Viande rouge</span>
                        <span class="tag">Sauce champignons</span>
                    </div>
                </article>

                <!-- Item 3 -->
                <article class="menu-card">
                    <div class="card-header">
                        <h3 class="card-title">Pâtes Alfredo</h3>
                        <span class="card-price">16€</span>
                    </div>
                    <p class="card-description">Fettuccine avec une sauce crémeuse au parmesan, ail et beurre.</p>
                    <div class="card-tags">
                        <span class="tag">Pâtes</span>
                        <span class="tag">Crémeux</span>
                    </div>
                </article>
            </div>
        </section>

        <!-- SECTION DESSERTS -->
        <section id="desserts" class="menu-section">
            <div class="section-header">
                <h2 class="section-title">🍰 Desserts</h2>
                <p class="section-subtitle">Succulentes finales gourmandes</p>
            </div>

            <div class="menu-grid">
                <!-- Item 1 -->
                <article class="menu-card">
                    <div class="card-header">
                        <h3 class="card-title">Fondue au Chocolat</h3>
                        <span class="card-price">10€</span>
                    </div>
                    <p class="card-description">Fruits frais et guimauves servis avec un chocolat chaud riche et fondant.</p>
                    <div class="card-tags">
                        <span class="tag">Chocolat</span>
                        <span class="tag">Fruits</span>
                    </div>
                </article>

                <!-- Item 2 -->
                <article class="menu-card">
                    <div class="card-header">
                        <h3 class="card-title">Cheesecake aux Fraises</h3>
                        <span class="card-price">9€</span>
                    </div>
                    <p class="card-description">Le cheesecake classique crémeux nappé d'un coulis de fraises fraîches.</p>
                    <div class="card-tags">
                        <span class="tag">Fromage</span>
                        <span class="tag">Fraises</span>
                    </div>
                </article>

                <!-- Item 3 -->
                <article class="menu-card">
                    <div class="card-header">
                        <h3 class="card-title">Tiramisu</h3>
                        <span class="card-price">8€</span>
                    </div>
                    <p class="card-description">Le célèbre dessert italien au café, biscuits boudoirs et crème mascarpone.</p>
                    <div class="card-tags">
                        <span class="tag">Café</span>
                        <span class="tag">Italien</span>
                    </div>
                </article>
            </div>
        </section>

        <!-- SECTION RÉSERVATION -->
        <section id="contact" class="reservation-section">
            <div class="reservation-content">
                <h2>📞 Réservez votre Table</h2>
                <p>Contactez-nous pour réserver et vivre une expérience gastronomique inoubliable</p>
                
                <div class="contact-info">
                    <div class="info-item">
                        <h4>Téléphone</h4>
                        <p><a href="tel:+33123456789">+33 1 23 45 67 89</a></p>
                    </div>
                    <div class="info-item">
                        <h4>Email</h4>
                        <p><a href="mailto:contact@menudélicieux.fr">contact@menudélicieux.fr</a></p>
                    </div>
                    <div class="info-item">
                        <h4>Horaires</h4>
                        <p>Lun-Dim: 11h30 - 23h00</p>
                    </div>
                </div>

                <a href="contact.html" class="btn-primary">Réserver Maintenant</a>
            </div>
        </section>
    </main>

    <!-- FOOTER -->
    <footer class="footer">
        <div class="footer-content">
            <div class="footer-section">
                <h4>À Propos</h4>
                <p>Menu Délicieux offre une cuisine française authentique avec des ingrédients de qualité supérieure.</p>
            </div>
            <div class="footer-section">
                <h4>Liens Rapides</h4>
                <ul>
                    <li><a href="#entrees">Entrées</a></li>
                    <li><a href="#plats">Plats Principaux</a></li>
                    <li><a href="#desserts">Desserts</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h4>Suivez-nous</h4>
                <ul>
                    <li><a href="#">Facebook</a></li>
                    <li><a href="#">Instagram</a></li>
                    <li><a href="#">Twitter</a></li>
                </ul>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2026 Menu Délicieux. Tous droits réservés.</p>
        </div>
    </footer>
</body>
</html>
