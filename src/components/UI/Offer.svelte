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
        z-index:20;
        padding: 170px 0 50px;
    }

     .first-art {
        text-align: center ;
        margin: 0px auto;
    }
    p {
        /* font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; */
        font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
        font-size: 1.3rem ;
        text-align: center;
        background: rgba(255, 250, 234, 0.196);
        padding: 15px 10px;
        margin-bottom:-15px;
        line-height: 1.2;
        
    }

    h2 {
        /* font-family: 'feltro-texture-3', sans-serif; */
        font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
        font-size: 5.2vw;
        /* margin-left: -65px; */
        text-shadow: 2px 2px 5px rgba(204, 145, 34, 0.612);
    }

    .grid-logo {
        margin: 30px;
        margin-bottom: 100px;
        display: grid;
        grid-template-columns: 1fr ;
    }

    .grid-logo > div {
        padding: 0 40px;

    }

    img {
        color: blue;
        width:70px;
        text-align:center;
        position: relative;
        left:50%;
        transform: translate(-50%,0%);
    }

    .sec-art {
        max-width: 95%;
        margin: 0 auto 50px ;
    }

    h3 {
        text-align: center;
        font-size: 2.2vw;
        margin: 15px 0;
        line-height:1;
        font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
        /* font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; */
    }

    

    .bottom-bump {
        height: 70px;
    }

    .button-prix {
        position: relative;
    }

    .prix {
        position: absolute;
        width:100%;
        padding: 20px 0;
        z-index:20;
        background: rgb(216, 112, 147) ;
        color: white ; 
        font-size: 40px;
        opacity: 1;
        margin-top: 20px;
        cursor: pointer;
        transition: all 0.3s ease ;
    }

    .prix:hover,
    .prix:focus {                               
        opacity: 0;
        
    }

    .prix-hide {
        position: absolute;
        text-align: center;
        width:100%;
        padding: 20px 0;
        z-index:10;
        background: rgb(112, 216, 209);
        color: black ; 
        font-size: 30px;
        margin-top:20px;
        font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
        
    }
    a {
        cursor: pointer;
        text-decoration: none ;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }

    .register {
        display: block;
        max-width: 500px;
        position: relative;
        text-align: center;
        left: 50%;
        top: 0;
        transform: translate(-50%,-50%);
        font-size: 2vw;
        padding: 40px 80px;
        background: palevioletred ;
        color: white ;
        border-radius: 2px;
        /* font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; */
        font-family: 'battlefin', sans-serif;
        font-style: normal;
        font-weight: 700 ;
        transition: all 0.4s ease-out;
        cursor: pointer;
    }

    .register:hover {
        background: rgb(112, 216, 209) ;
    }

    .mega {
        
        width: 100%;
    }

     @media only screen and (min-width:750px){
        .grid-logo { grid-template-columns: 1fr 1fr 1fr; }
     }

    @media only screen and (max-width:749px){
        .back {
        position: relative;
        z-index:20;
        padding: 170px 0 20px; }
    
    .sec-art { max-width: 100%;
                   margin: 0 auto 50px ; }
    
    .grid-logo > div { padding: 0 0px; }

    img {
        margin-top:140px;
    }


         }
         
    


</style>

<section>
    <div class="back">
        <article class="first-art">
            <h2>SUR LA PLAGE</h2>
            <h3>3 packages pour vous permettre d'en profiter au maximum !</h3>
        </article>
    </div>

    <div>
        <article class="sec-art">
            <div class="grid-logo">
                <div>
                    <img class="col" src="gauge-dashboard-1.svg" alt="bin">
                    <h3>Package</h3>
                    <h3>CHUI PAS GAME !</h3>
                    <p>La possibilité d'utiliser le locker pour ranger son matériel de kitesurf 
                        à la fin de la journée et ainsi diminuer le taux d'humidité de sa chambre</p>
                    <p>Un service de décollage et d'attérissage de votre aile de kitesurf - fait par un kitelauncher niv.3</p>
                    <div class="button-prix">
                        <p class="prix">$45</p>
                        <a class="prix-hide" href="/about">WOW! Je m'inscris</a> 
                    </div>
                </div>

                <div>
                    <img src="binocular.svg" alt="bin">
                    <h3>Package</h3>
                    <h3>COURS DE FOIL</h3>
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
                <div>
                    <img src="beach-parasol-water-1.svg" alt="bin">
                    <h3>Package</h3>
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