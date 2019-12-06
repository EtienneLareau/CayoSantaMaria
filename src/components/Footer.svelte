<style>
    footer {
    background-color: #f3fffc;
    width:100%;
    padding: 30px;
    top:0;
}
    .gid {
        width:90%;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-gap:2em;
        margin: 0 auto;
    }

    .gid-cont {
        background: palevioletred;
        height:300px;
    }

    .gid-cont > h2,p {
        margin: 20px 0 0 20px;
    }


    .back {
        max-width:900px;
        margin:0 auto;
        padding: 40px;
    }

    .grido {
        display:grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-gap: 10px;
    }

    h2 {
        margin:0 0 30px 0;
        color: black;
        text-align: center;
    }

    img {
        height:50px;
        margin:0 auto;
    }

    .year-banner {
        width:100%;
        height:40px;
        background: black;
         display: flex;
        align-items: center;
        justify-content: center;
    }

    small {
        color:#86fadb;
        font-family: 'battlefin', sans-serif;
         font-weight: 400;
         font-style: normal;
         letter-spacing: 1.2px;
    }

    @media only screen and (max-width:800px) {
        .grido {
            grid-template-columns: 1fr;
            grid-gap: 0px;
        }
        img {
            margin:15px auto;
        }
        .back {
            padding:0px;
        }
        footer {
            padding: 90px 0px 50px;
            margin-top:-60px;
        }
    }
</style>

<footer>

    <div class="back">
        <h2>Voyage en collaboration avec:</h2>
        <div class="grido">
            <img src="/images/Logo_PulsionVoyageS.png" alt="Pulsion Voyages">
            <img src="/images/Duotone.png" alt="Duotone Kiteboarding">
            <img src="/images/Logo_30.png" alt="Boutique 30 Noeuds">

        </div>
    </div>
</footer>
<div class="year-banner">
     <small>copyright 2019 - Bientôt 2020</small>
</div>



<!-- <footer>
    <div class="foo">
        <div class="gid">
        <div class="gid-cont">
            <h2>Menu</h2>
            <p class="menu-link">Le voyage</p>
            <p class="menu-link">Les cours</p>
            <p class="menu-link">Le Spot</p>
            <p class="menu-link">Les avantages</p>
            <p class="menu-link">Je m'inscris</p>
        </div>
        <div class="gid-cont"></div>
        <div class="gid-cont"></div>
        
        </div>
    
    
    </div>
</footer> -->