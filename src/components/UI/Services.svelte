    
    
    

<style>
    article {
        max-width: 800px;
        width: 80% ;
        margin: 40px auto 0;
        padding: 100px 0 0px;
        /* background: #70fad581 ; */
    }
    article > p {
        
        font-size:1.7rem !important;
    }


    p {
        /* font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; */
        font-size: 1.3rem ;
        font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
        padding: 5px;
    }

    h2 {
        font-family: 'feltro-texture-3', sans-serif;
        font-size: 4.2rem;
        margin-left: -65px;
        text-shadow: 2px 2px 5px rgba(204, 145, 34, 0.612);
    }

    img {
        width:80px;
        margin:20px 0 -10px;
        float:left;
        padding: 0px 15px;
    }

    .grid-block {
        max-width: 1100px;
        width: 80% ;
        position: relative;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-gap: 40px;
        margin: 0 auto;
    }

    @media only screen and (max-width:765px) {
        article {
            width:100%;
        }
        .grid-block {
            display:block;
            grid-template-columns: 1fr ;
            grid-gap:0;
            padding:0px;
            width:100%;
        }
        p {
            font-family: 'battlefin', sans-serif;
            font-weight: 400;
            font-style: normal;
            padding: 0 1em;
        }
        img {
            width:60px;
            margin:0;
            position: relative;
            left:50%;
            transform:translate(-50%,0%);
            float:none;
            padding: 0px 0px;
        }
        .reserved {
            font-size: 1.7rem !important;
            padding: 0.8em 1em;
        }
        .grid-cont {
            padding: 15px 0;
            margin: 15px 0;
        }
        h2 {
        font-family: 'feltro-texture-3', sans-serif;
        font-size: 3.2rem;
        padding: 0 20px 10px;
        text-align: center;
        text-shadow: 2px 2px 5px rgba(204, 145, 34, 0.612);
        }
    }

    @media only screen and (min-width:766px) and (max-width:1115px) {
         .grid-block {
            grid-gap:20px;
            padding:0px;
            width:100%;
        } 
        p {
            font-family: 'battlefin', sans-serif;
            font-weight: 400;
            font-style: normal;
            font-size: 1.3rem ;
            padding: 0 1em;
        }
        img {
            width:60px;
            margin:0;
            position: relative;
            left:50%;
            transform:translate(-50%,0%);
            float:none;
            padding: 0px 0px;
        }
        .reserved {
            font-size: 1.7rem !important;
            padding: 0.8em 1em;
        }
        .grid-cont {
            padding: 15px 0;
            margin: 15px 15px;
        }
        h2 {
        font-family: 'feltro-texture-3', sans-serif;
        font-size: 3.2rem;
        padding: 0 20px;
        margin-left:0;
        text-shadow: 2px 2px 5px rgba(204, 145, 34, 0.612);
        }
    }
    /* //////////////// */

    .grid-cont {
        /* background: rgba(152, 251, 152, 0.151); */
        text-align: left;
        /* background: rgb(181, 234, 217); */
        background-color: #6afed7 ;
        margin:0 0 30px;
    }

    /* .center {
        position: relative;
        left:50%;
        transform: translate(-50%,0%);
    } */

    .reserved {
        font-family: 'battlefin', sans-serif;
        font-weight: 900;
        font-style: normal;
        font-size: 2.5vw;
        text-align: center;
        margin-bottom: 80px;
    }

    .grid-pack {
        margin-bottom:100px;
        width: 100%;
        
    }

    .green {
        width: 100%;
        /* background: #a7e9d4; */
        background: #86fadb ;
        padding: 50px 0px;
    }

    .start {
        margin-top:-40px;
        background-image: url('/images/coursLight.jpeg');
        background-position: center;
        background-repeat: no-repeat ;
        background-size: cover;
    }

    .fade {
        position: relative;
        z-index: 100;
        background: rgba(255, 255, 255, 0.603);
        width:100%;
        height:100%;
        
    }
</style>

<div class="start">
    <div class="fade">
        <article>
            <p>La destination :</p>
            <h2>Cayo Santa Maria</h2>
            <p>Situé à une quinzaine de kilomètres de Cayo Guillermo, 
                Cayo Santa Maria vous offre les mêmes conditions de vent,
                 d'eau chaude turquoise et d'espace, le tout avec un fond 
                 marin en sable blanc sans roche.</p>
            <br>
            
            <p>Un terrain de jeu exceptionnel à découvrir pour tous les gouts
             possédant une immense zone de " flat water " à côté du parc 
             National pour nos débutants et au large de la barrière de 
             coraux, un terrain de Freestyle avec de la petite vague qui 
             vous permettra de pratiquer le kitesurf et le hydrofoil en 
             toute sécurité.</p>
            <br>
            
            <p> À deux pas de votre chambre la plage du Kite Camps Valentin 
             Club Perla Blanca est un endroit paradisiaque et unique, 
             qui en font l'un des meilleurs ‘’SPOTS’’ des Caraïbes.</p>
           
            <br><br>
            
        </article>
    </div>
</div>
<div class="green">
    <p class="reserved">
        EN RÉSERVANT AVEC NOUS, vous bénéficierez :
    </p>
    <div class="grid-pack">
        <div class="grid-block">
            <div class="grid-cont">
                <img src="shopping-bag-heart.png" alt="">
                <p>D'une Suite Junior dans notre zone VIP KITE CAMPS en bordure de mer, vous permettant ainsi d'avoir un accès direct à la plage.</p>
            </div>
            <div class="grid-cont">
                <img src="love-boat.png" alt="">
                <p>Vous pourrez sélectionner votre type de chambre - 2 lits doubles ou 1 lit king - et au rez-de-chaussée ou à l'étage.</p>
            </div>
            <div class="grid-cont">
                <img src="office-work-wireless.png" alt="">
                <p>La sélection de votre siège dans l'avion est disponible au cout de 45$ (aller & retour)</p>
            </div>
        </div>
        
        <div class="grid-block">
            <div class="grid-cont">
                <img src="show-hat-magician-1.png" alt="">
                <p>Un bagage suplémentaire de kitesurf de 20kg sans aucuns frais additionnel.</p>
            </div>
            <div class="grid-cont">
                <img src="whale-body.svg" alt="">
                <p>Le Transfert aller-retour en autocar pour vous avec votre bagages de kite.</p>
            </div>
            <div class="grid-cont">
                <img src="nautic-sports-sailing-person.svg" alt="">
                <p>Les Taxes de voyage, taxes d'aéroport, visa cubain, taxes canadienne, taxe du fond d'indemnisation (OPC) des voyageurs du Québec ainsi que les frais de services</p>
            </div>
        </div>
    </div>
</div>
<!-- <div class="backimage">
    <div class="grid-sec">
        <div class="right">
             <p>Venez profiter de la chaleur de Cuba et de son vent d’une stabilité légendaire. Destination prisée pour le kitesurf, Cayo Santa Maria vous permet d’apprendre et de progresser sous la supervision de nos conseillers et de nos instructeurs dans un cadre sécuritaire. Des kilomètres de « flat water » font de cette île l’endroit idéal pour commencer le sport ou pour progresser en freestyle. De plus, la plage de près de 200 pieds de largeur vous procure assez d'espace pour assembler vos ailes en toute quiétude.</p>
        </div>
        <div class="left">
           
        </div>
    </div>
</div> -->