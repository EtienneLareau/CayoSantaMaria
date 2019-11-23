<script>
    
</script>

<style>

    section {
        position: relative;
        width:100%;
        /* background-color: rgb(167, 233, 212); */
        background: #86fadb ;
        /* background-image: url('/images/decolle.jpeg');
        background-position: left center ;
        background-repeat: no-repeat ;
        background-size: cover ; */
    }

    .back {
        position: relative;
        z-index:10;
        padding: 105px 0 50px;
    }

     .first-art { text-align: center ;
                  margin: 0px auto; }

    h2 { font-family: 'battlefin', sans-serif;
         font-weight: 400;
         font-style: normal;
         font-size: 3.2rem;
         padding: 0 0px;
         text-shadow: 1px 1px 3px rgb(18, 97, 74); }

    p { font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
        font-size: 1.3rem ;
        text-align: left;
        background: rgba(255, 250, 234, 0.196);
        padding: 15px 10px;
        margin-bottom:-15px;
        line-height: 1.2; }

    .med-font { font-size: 2.1rem;
                background: none;
                padding:0 10px 15px;
                text-align: center; }
    /* //// */

    .grid-logo {
        margin: 0px;
        margin-bottom: 100px;
        display: grid;
        grid-template-columns: 1fr ;
    }

    .grid-logo > div {
        padding: 0 40px;

    }

    .choix {
        margin: 0 0 40px;
    }

    .numbers-title {
        font-family: 'feltro-texture-3', sans-serif;
        font-size: 80px;
        padding:20px;
        color: #86fadb;
        /* background-color: rgb(18, 97, 74); */
        background: rgb(175, 39, 62) ;
        border-radius:100px;
        width:80px;
        margin: 0 auto 30px;
        box-shadow:2px 2px 10px rgba(128, 128, 128, 0.568);
    }




    img {
        width:70px;
        text-align:center;
        position: relative;
        left:50%;
        transform: translate(-50%,0%);
    }

    h3 {
        text-align: center;
        font-size: 2.1rem;
        margin: 15px 0;
        line-height:1;
        font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
    }

    @media only screen and (max-width:1000px){
        .grid-logo > div {
        padding: 0 20px;

    }
    }


     @media only screen and (min-width:850px){
        .grid-logo { grid-template-columns: 1fr 1fr 1fr; }
     }

         
    


</style>

<section>
    <!-- title -->
    <div class="back">
        <div class="first-art">
            <h2>SUR LA PLAGE</h2>
            <p class="med-font">3 façons d'en profiter</p>
        </div>
    </div>

    <div>
        <article class="sec-art">
            <div class="grid-logo">
                <div class="choix">
                    <h3 class="numbers-title">1</h3>
                    <!-- <img class="col" src="gauge-dashboard-1.svg" alt="bin"> -->
                    <h3>LA BALADE</h3>
                    <p>La possibilité d'utiliser le locker pour ranger son matériel de kitesurf 
                        à la fin de la journée et ainsi diminuer le taux d'humidité de sa chambre</p>
                    <p>Un service de décollage et d'attérissage de votre aile de kitesurf - fait par un kitelauncher niv.3</p>
                    <div class="button-prix">
                        <p class="prix">$45</p>
                        <a class="prix-hide" href="/about">WOW! Je m'inscris</a> 
                    </div>
                </div>

                <div class="choix">
                     <h3 class="numbers-title">2</h3>
                    <!-- <img src="binocular.svg" alt="bin"> -->
                    <h3>LA LEÇON DE FOIL</h3>
                    <p>3h de leçons pour vous ammener de débutant à "foileux" (dire "foileux")</p>
                    <p>La possibilité d'essayer des foilboards de différentes marques pour mieux orienter votre premier achat</p>
                    <p>2h de navigation assisté pour vous permettre de progresser plus rapidement</p>
                    <p>Un t-shirt qui dit "Moé J'Foil de même !"</p>
                    <p>La possibilité d'utiliser le locker pour ranger son matériel de kitesurf 
                       à la fin de la journée et ainsi diminuer le taux d'humidité de sa chambre</p>
                    <p>Un service de décollage et d'attérissage de votre aile de kitesurf - fait par un kitelauncher niv.3</p>
                    <div class="button-prix">
                        <p class="prix">$450</p>
                        <a class="prix-hide" href="/about">Malade!</a> 
                    </div>
                </div>
                <div class="choix">
                     <h3 class="numbers-title">3</h3>
                    <!-- <img src="beach-parasol-water-1.svg" alt="bin"> -->
                    <h3>LA TOTALE</h3>
                    <p>Un ensemble complet de foilboard incluant la planche, le foil, le gilet d'impact et le casque de sécurité</p>
                    <p>3h de leçons pour vous ammener de débutant à "foileux" (dire "foileux")</p>
                    <p>La possibilité d'essayer des foilboards de différentes marques pour mieux orienter votre premier achat</p>
                    <p>2h de navigation assisté pour vous permettre de progresser plus rapidement</p>
                    <p>Un t-shirt qui dit "Fuck le twin-tip - chui un foileux"</p>
                     <p>La possibilité d'utiliser le locker pour ranger son matériel de kitesurf 
                        à la fin de la journée et ainsi diminuer le taux d'humidité de sa chambre</p>
                    <p>Un service de décollage et d'attérissage de votre aile de kitesurf - fait par un kitelauncher niv.3</p>
                    <div class="button-prix">
                        <p class="prix">$850</p>
                        <a class="prix-hide" href="/about">C presque rien!!!</a> 
                    </div>
                    <div class="bottom-bump"></div>
                    <div class="bottom-bump"></div>
                    <div class="bottom-bump"></div>
                </div>
            </div>
        </article>
    </div>

    <div class="mega">
        <a class="register" href="/blog">JE M'INSCRIS</a>
    </div>
    
</section>