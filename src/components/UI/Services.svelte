    
    
    

<style>
        .grid-block {
            display:grid;
            grid-template-columns: 1fr 1fr 1fr ;
            grid-gap:20px;
            padding:0px;
            max-width:90%;
            margin:0 auto;
        }

        p {
            font-family: bicyclette, sans-serif;
            font-weight: 300;
            font-style: normal;
            font-size: 1.4rem ;
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

        .grid-cont {
            padding: 15px 0;
            margin: 15px 15px 30px;
            text-align: left;
            background-color: #6afed7 ;
        }

    h2 {
         font-family: bicyclette, sans-serif;
        font-weight: 400;
        font-style: normal;
        font-size: 3.2vw;
        text-align: center;
        margin-bottom: 60px;
    }

    .grid-pack {
        margin-bottom:100px;
        width: 100%;
        
    }

    .green {
        position: relative;
        z-index: 15;
        width: 100%;
        background: #86fadb ;
        padding: 70px 0px 10px;
        margin-bottom:-60px;
    }

     @media only screen and (max-width:865px) {
        
        .green {
            padding: 40px 0px;
        }
        .grid-block {
            display:block;
            grid-template-columns: 1fr ;
            grid-gap:0;
            padding:0px;
            width:100%;
        }
        p {
           font-family: bicyclette, sans-serif;
            font-weight: 300;
            font-style: normal;
            padding: 0 1em;
            font-size:1.4rem;
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
        h2 {
            font-size: 2.1rem;
            padding: 0.6em 1em;
        }
        .grid-cont {
            padding: 15px 0;
            margin: 15px 0;
        }
    }
</style>


<div class="green">
    <h2 class="reserved">EN RÉSERVANT AVEC NOUS, vous bénéficierez :</h2>
    <div class="grid-pack">
        <div class="grid-block">
            <div class="grid-cont">
                <img data-src="shopping-bag-heart.png" class="lazyload" alt="">
                <p>D'une Suite Junior dans notre zone VIP KITE CAMPS en bordure de mer, vous permettant ainsi d'avoir un accès direct à la plage.</p>
            </div>
            <div class="grid-cont">
                <img data-src="love-boat.png" class="lazyload" alt="">
                <p>Vous pourrez sélectionner votre type de chambre - 2 lits doubles ou 1 lit king - et au rez-de-chaussée ou à l'étage.</p>
            </div>
            <div class="grid-cont">
                <img data-src="office-work-wireless.png" class="lazyload" alt="">
                <p>La sélection de votre siège dans l'avion est disponible au cout de 45$ (aller & retour)</p>
            </div>
        </div>
        
        <div class="grid-block">
            <div class="grid-cont">
                <img data-src="show-hat-magician-1.png" class="lazyload" alt="">
                <p>Un bagage suplémentaire de kitesurf de 20kg sans aucuns frais additionnel.</p>
            </div>
            <div class="grid-cont">
                <img data-src="whale-body.svg" class="lazyload" alt="">
                <p>Le Transfert aller-retour en autocar pour vous avec votre bagages de kite.</p>
            </div>
            <div class="grid-cont">
                <img data-src="nautic-sports-sailing-person.svg" class="lazyload" alt="">
                <p>Les Taxes de voyage, taxes d'aéroport, visa cubain, taxes canadienne, taxe du fond d'indemnisation (OPC) des voyageurs du Québec ainsi que les frais de services</p>
            </div>
        </div>
    </div>
</div>