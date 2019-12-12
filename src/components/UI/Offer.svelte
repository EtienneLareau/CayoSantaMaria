<script>
    function scrollDown() {
        document.querySelector('#Register').scrollIntoView({ 
        behavior: 'smooth' });
    }

    function choiceOne() {
        document.querySelector('#labalade').scrollIntoView({
            behavior: 'smooth'});
    }

    function choiceTwo() {
        document.querySelector('#lalecon').scrollIntoView({
            behavior: 'smooth'});
    }

    function choiceThree() {
        document.querySelector('#latotale').scrollIntoView({
            behavior: 'smooth'});
    }



    // all element in viewport
    function isElementInViewport(el) {
  var rect = el.getBoundingClientRect();
  return (
    rect.top >= 0 &&
    rect.left >= 0 &&
    rect.bottom <= (window.innerHeight || document. documentElement.clientHeight) &&
    rect.right <= (window.innerWidth || document. documentElement.clientWidth)
  );
}


function isAnyPartOfElementInViewport(el) {

    const rect = el.getBoundingClientRect();
    // DOMRect { x: 8, y: 8, width: 100, height: 100, top: 8, right: 108, bottom: 108, left: 8 }
    const windowHeight = (window.innerHeight || document.documentElement.clientHeight);
    const windowWidth = (window.innerWidth || document.documentElement.clientWidth);

    // http://stackoverflow.com/questions/325933/determine-whether-two-date-ranges-overlap
    const vertInView = (rect.top <= windowHeight) && ((rect.top + rect.height) >= 0);
    const horInView = (rect.left <= windowWidth) && ((rect.left + rect.width) >= 0);

    return (vertInView && horInView);
}

    // import Transition from '../../components/UI/Transition.svelte';

</script>

<style>

    section {
        position: relative;
        width:100%;
        z-index: 15;
        /* background-color: rgb(167, 233, 212); */
        background: #86fadb ;
        padding-bottom:60px;
        /* background-image: url('/images/decolle.jpeg');
        background-position: left center ;
        background-repeat: no-repeat ;
        background-size: cover ; */
    }

    .back {
        position: relative;
        z-index:10;
        padding: 50px 0 50px;
    }

    .first-art { text-align: center ;
                margin: 0px auto; }

    h2 { 
        font-weight: 900;
        font-style: normal;
         font-size: 3.2rem;
         padding: 0 0px;
         text-shadow: 1px 1px 3px rgb(18, 97, 74); }

    p { font-size: 1.7rem ;
        text-align: left;
        background: rgba(255, 250, 234, 0.196);
        padding: 10px 10px;
        margin-bottom:-15px;
        line-height: 1.2; }

    .med-font { font-size: 2.1rem;
                background: none;
                padding:0 10px 15px;
                text-align: center; }

    .grid-logo {
        margin: 0px;
        margin-bottom: 50px;
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
        font-family: 'feltro-texture-3', 'Gill Sans', sans-serif;
        font-size: 80px;
        padding:20px;
        color: #86fadb;
        /* background-color: rgb(18, 97, 74); */
        background: #ff22aa ;
        border-radius:100px;
        width:80px;
        margin: 0 auto 30px;
        box-shadow:2px 2px 10px rgba(128, 128, 128, 0.568);
    }

    h3 {
        text-align: center;
        font-size: 2.1rem;
        margin: 15px 0;
        line-height:1;
        font-family: bicyclette, sans-serif;
        font-weight: 400;
        font-style: normal;
    }

    .choices-line {
        margin:20px;
    }   
    
    button {
        display:none;
        color:#ff22aa;
        cursor: pointer;
        background: transparent;
        font-size: 1.1rem;
        text-shadow: 1px 1px 3px #86fadb;
        margin:10px;
        text-decoration: none;
        padding: 6px 14px;
        border: 2px solid #ff22aa;
        border-radius:25px;
        width:200px;
        margin: 20px auto;
        box-shadow: 1px 1px 2px rgba(0, 0, 0, 0.351);
        transition: all 0.3s ease-out;
    }

    button:hover {
        background: #a4ffe7;
         box-shadow: 1px 1px 2px rgba(0, 0, 0, 0.351);
         text-shadow: none;
    }

    .mega {
        text-decoration: none;
        padding: 0 10px;
        
    }

    .para-link { 
        font-family: bicyclette, sans-serif;
        font-weight: 400;
        font-style: normal;
        font-size: 1.5rem ;
        text-align: center;
        max-width:300px;
        margin: 0 auto 40px;
        border: 2px solid #ff22aa;
        background: #ff22aa;
        box-shadow: 2px 2px 5px black;
        color:white;
        border-radius:10px;
        padding: 20px 40px;
        transition: all 0.1s ease-in;
        cursor: pointer;
         }

    .para-link:hover {
        background: white;
        border: 2px solid #86fadb;
        box-shadow: none;
        color:#ff22aa;
    }

    .prix {
        color: #ff22aa;
        font-size:1.7rem;
        font-weight:400;
    }

    @media only screen and (max-width:1000px){
        .grid-logo > div {
        padding: 0 20px; }
    }

     @media only screen and (min-width:850px){
        .grid-logo { grid-template-columns: 1fr 1fr 1fr; }

        .choix {
            margin-bottom:60px;
        }
        p{ font-size:1.4rem; }
     }

    @media only screen and (max-width:725px){
        button {
        display:block;
        }

        .choix {
            margin-bottom:60px;
        }

        p{ font-size:1.4rem; }
    }

</style>

<section>
    <!-- title -->
    <div class="back">
        <div class="first-art">
            <h2>SUR LA PLAGE</h2>
            <p class="med-font">3 façons d'en profiter</p>
            <div class="choices-line">
                <button on:click={choiceOne} >La Balade</button>
                <button on:click={choiceTwo} >La Leçon</button>
                <button on:click={choiceThree} >La Totale</button>
            </div> 
        </div>
    </div>
            <!-- <Transition /> -->
    <div>
        <article class="sec-art">
            <div class="grid-logo">
                <div id="labalade" class="choix">
                    <h3 class="numbers-title">1</h3>
                    <h3>LA BALADE</h3>
                    <p>La possibilité d'utiliser le locker pour ranger son matériel de kitesurf 
                        à la fin de la journée et ainsi diminuer le taux d'humidité de sa chambre</p>
                    <p>Un service de décollage et d'attérissage de votre aile de kitesurf - fait par un kitelauncher niv.3</p>
                    <div class="button-prix">
                        <p class="prix">Prix pour la semaine : $45</p>
                    </div>
                </div>
                <div id="lalecon" class="choix">
                     <h3 class="numbers-title">2</h3>
                    <!-- <img src="binocular.svg" alt="bin"> -->
                    <h3>LA LEÇON DE FOIL</h3>
                    <p>3h de leçons pour vous ammener de débutant à "foileux" (dire "foileux")</p>
                    <p>2h de navigation assisté pour vous permettre de progresser plus rapidement</p>
                    <p>La possibilité d'essayer des foilboards de différentes marques pour mieux orienter votre premier achat</p>
                    <p>La possibilité d'utiliser le locker pour ranger son matériel de kitesurf 
                       à la fin de la journée et ainsi diminuer le taux d'humidité de sa chambre</p>
                    <p>Un service de décollage et d'attérissage de votre aile de kitesurf - fait par un kitelauncher niv.3</p>
                    <div class="button-prix">
                        <p class="prix">Prix pour la semaine : $450</p>
                        
                    </div>
                </div>
                <div id="latotale" class="choix">
                     <h3 class="numbers-title">3</h3>
                    <!-- <img src="beach-parasol-water-1.svg" alt="bin"> -->
                    <h3>LA TOTALE</h3>
                    <p>Un ensemble complet de foilboard incluant la planche, le foil, le gilet d'impact et le casque de sécurité</p>
                    <p>3h de leçons pour vous ammener de débutant à "foileux" (dire "foileux")</p>
                    <p>2h de navigation assisté pour vous permettre de progresser plus rapidement</p>
                    <p>La possibilité d'essayer des foilboards de différentes marques pour mieux orienter votre premier achat</p>
                    <p>La possibilité d'utiliser le locker pour ranger son matériel de kitesurf 
                        à la fin de la journée et ainsi diminuer le taux d'humidité de sa chambre</p>
                    <p>Un service de décollage et d'attérissage de votre aile de kitesurf - fait par un kitelauncher niv.3</p>
                    <div class="button-prix">
                        <p class="prix">Prix pour la semaine : $850</p>
                    </div>
                </div>
            </div>
            <div on:click={scrollDown} class="mega">
                <p class="para-link">JE M'INSCRIS</p>
            </div>
        </article>
    </div>
</section>