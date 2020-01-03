    <script>
        import Rotate from '../../components/UI/Rotate.svelte';
    </script>
    
<style>

     .beach {
        background-color: #f5fefb;
        margin-top:-42px;
        padding-bottom:20px;
        position: relative;
        z-index: 11;
        width:100% ;
    }

    .cover {
        position: relative;
        z-index:11;
        width:100% ;
        height: 100% ;
        /* background: #06855de4; */
    }

    article {
        max-width: 820px;
        width: 80%;
        margin: 40px auto 0;
        padding: 80px 0 0; }

    h2 { 
         font-weight: 700;
         font-style: normal;
         font-size: 5.3vw ;
         padding: 1em 20px 0;
         margin:0;
         text-shadow: 1px 1px 3px #86fadb }

    p { 
        font-style: normal;
        font-size: 1.7rem ;
        padding: 1.5em 20px 0; }


    @media only screen and (max-width:725px) {
        
        article {
            width:100%;
            padding:30px 0px 40px;
        }
        
        h2 {
            font-size: 2.7rem;
            padding-bottom:0px;
        }

        p {
            font-size: 1.4rem;
            line-height:1.3;
            padding: 0.8em 25px 0;
        }
    }
</style>

   
    <div class="beach">
        <div class="cover">
        <article>
            <Rotate />
            <!-- <h2>Valentin Club Perla Blanca</h2> -->
            <h2>Bienvenue au premier voyage dédié au kitefoil</h2>
                <p>En collaboration avec l’hôtel <span style="font-family: 'feltro-texture-3', sans-serif;text-shadow:1px 1px 2px #86fadb ">Valentin Perla Blanca</span>, nous vous proposons divers 
                forfaits élaborés spécifiquement pour vous. 
                Ce voyage dédié KiteFoil s'adresse aux pratiquants de tous les niveaux, du débutant à l'expert.
                <br><br>
                Nos instructeurs fort qualifiés en la matière faciliteront 
                grandement votre apprentissage. Vous bénéficierez du meilleur équipement 
                disponible sur le marché ainsi que des dernières innovations techniques en matière 
                d'enseignement comme des radios intégrées (2ways) à votre casque permettant un échange 
                continu avec votre instructeur. 
                <br><br>
                Vous aurez aussi l'occasion d'essayer différents produits de kitefoil 
                facilitant ainsi votre premier achat.</p>
        </article>
        </div>
    </div>
