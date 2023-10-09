<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Oh my food</title>
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css"
        integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w=="
        crossorigin="anonymous" referrerpolicy="no-referrer">
    </head>
    <body>
        <div class="loader-contenaire">
            <div class="texte-loader loader">
                <p>Bienvenue</p>
                <p>sur</p>
                <h2>Oh My Food</h2>
            </div>
        </div>  
        
    <!--Logo-->
    <header> 
        <div class="centrer">
            <img class="logo" src="images/logo/ohmyfood.png" alt="Logo Oh my food">
        </div>
        <nav class="centrer fondgris">
        <h4><i class="fa-solid fa-location-dot espace" style="color: #353535;"></i>Paris,Belleville</h4>
        </nav>
    </header>
    <!--Titre,texte d'explicationc et boutton de recherche-->
        <section class="fondgris-clair centrer">
            <div><h1 class="titre ">Réserver le menu qui vous convient</h1></div>
            <h3 class="titre1">Découvrez des restaurants d'exeption , sélectionnés par nos soins</h3>
            <a href="#Restaurants" style="text-decoration:none">
                <div class="explorer">Explorer nos restaurants</div>
            </a>
        </section>
    
    <!--Etapes des choix-->
        <section>
            <h2 class="MEP">Fonctionnements</h2>
                <br>   
                <div class="horizontal MEP1">
                    <div class="fonctionnements1 ">
                       <p class="cercle">1</p>
                       <button class="fonctionnements">
                       <i class="fa-solid fa-mobile-screen espace" style="color: #7e7e7e;"></i>
                       Choisissez un restaurants
                       </button>
                    </div>
                    <br>
                    <div class="fonctionnements1">
                        <p class="cercle">2</p>
                        <button class="fonctionnements">
                        <i class="fa-solid fa-list-ul espace" style="color: #7e7e7e;"></i>
                        Composez votre menu
                        </button>
                    </div>
                    <br>
                    <div class="fonctionnements1">
                        <p class="cercle">3</p>
                        <button class="fonctionnements">
                        <i class="fa-solid fa-store espace" style="color: #9656dc;"></i>
                        Dégustez au restaurants
                        </button>
                    </div>
                </div>
            <br>
        </section>

    <!--Les restaurants et leur lieu-->
        <section class="fondgris-clair ">
            <h2 class="MEP">Restaurants</h2>
                <div class="restaurants contenaire" id="Restaurants">
                    <div class="imagesRestau">
                        <div class="nouveau1"><p class="nouveau">Nouveau</p></div>
                        <a href="La-palette-du-goût.html" style="text-decoration:none" class="lien-couleur animation-ouverture" > 
                            <img src="images/restaurants/jay-wennington-N_Y88TWmGwA-unsplash.jpg " alt="La palette du goût"><br><br>
                            <p class="p1">La palette du goût</p>
                            <p class="p2">Ménilmontant</p>
                        </a>
                            <p class="coeur">
                                <i class="fa-regular fa-heart  icoeur" style="color:#000000;"></i>
                                <i class="fa-solid fa-heart  icoeur icoeur2"></i>
                            </p>
                    </div>
                
                    <div class="imagesRestau">
                        <div class="nouveau1"><p class="nouveau">Nouveau</p></div>
                        <a href="La-note-enchantée.html" style="text-decoration:none" class="lien-couleur animation-ouverture">
                            <img src="images/restaurants/stil-u2Lp8tXIcjw-unsplash.jpg" alt="La note enchantée" ><br><br>
                            <p class="p1">La note enchantée</p>
                            <p class="p2">Charonne</p>
                        </a>    
                            <p class="coeur">
                                <i class="fa-regular fa-heart  icoeur" style="color: #000000;"></i>
                                <i class="fa-solid fa-heart  icoeur icoeur2" ></i>
                            </p>                                 
                    </div>

                    <div class="imagesRestau">
                        <a href="A-la-française.html" style="text-decoration:none" class="lien-couleur animation-ouverture">
                           <img src="images/restaurants/toa-heftiba-DQKerTsQwi0-unsplash.jpg" alt="A la française"><br><br>
                           <p class="p1">A la française</p>
                           <p class="p2">Cité rouge</p>
                        </a>   
                           <p class="coeur">
                               <i class="fa-regular fa-heart icoeur" style="color: #000000;"></i>
                               <i class="fa-solid fa-heart  icoeur icoeur2" ></i>
                            </p>
                    </div> 

                    <div class="imagesRestau">
                        <a href="Le-délice-des-sens.html" style="text-decoration:none" class="lien-couleur animation-ouverture">
                            <img src="images/restaurants/louis-hansel-shotsoflouis-qNBGVyOCY8Q-unsplash.jpg" alt="Le délice des sens"><br><br>
                            <p class="p1">Le délice des sens</p>
                            <p class="p2">Folie-Méricourt</p>
                        </a>    
                            <p class="coeur">
                                <i class="fa-regular fa-heart  icoeur" style="color: #000000;"></i>
                                <i class="fa-solid fa-heart  icoeur icoeur2"></i>
                            </p>  
                    </div>
                </div>
        </section>

    <!--Bannière fin de page-->
    <footer>
        <div class="footer">
            <img class="logo-blanc1" src="images/logo/ohmyfood-blanc.png" alt="logo-blanc">
            <br>
            <div class="espace">
                <i class="fa-solid fa-utensils espace" style="color: #fafafa;"></i>
                Proposer un restaurants
            </div>
            <br>
            <div class="espace1">
                <i class="fa-solid fa-handshake-angle espace" style="color: #fafafa;"></i>
                Devenir partenaire
            </div>
                <br>
            <div class="espace">
                Mentions légales
            </div>
            <br>
            <div class="espace1">
                Contact
            </div>
            <br>
            <img class="logo-blanc " src="images/logo/ohmyfood-blanc.png" alt="logo-blanc">
        </div>
    </footer>     
    </body>
</html>
