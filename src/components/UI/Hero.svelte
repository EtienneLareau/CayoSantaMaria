<script>
    let logo = 'images/LogoOnly.png';
</script>

<style>
     section {position: relative;}

    .container {
        width:100%;
        height:100vh;
        background: url('/images/covFoil.jpeg') right center no-repeat;
        background-size: cover ;
    }

    .banner {
        position: absolute ;
        bottom: 5% ;
        left: 50% ;
        transform: translate(-50%, 0%);
        z-index: 15;
        text-align: center ;
        color: #86fadb;
        text-transform: uppercase ;
        width:95%;
    }
    
    h2, p {
        /* font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; */
        font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
    }

    h2 {
        font-size: 5vw;
        padding:0;
        margin:0 0 -10px;
        line-height:1.1;
    }

    p {
        font-size: 3vw;
        line-height: 0.4;
    }

     @media only screen and (max-width:700px){
        h2 { font-size:3.1rem;
             line-height:1.1 }

        p { font-size:1.9rem;
            line-height:1.3; }

        .container { background: url('/images/covFoilS.jpg') right center no-repeat;
                     background-size: cover; } }

</style>

<section>
    <div class="container">
        <div class="banner">
            <!-- <img src="{logo}" alt="logo"> -->
            <h2>Foil Kitecamp</h2>
            <p>Du <span style="font-size:1.5em">11</span> janvier au <span style="font-size:1.5em">17</span> janvier 2020</p>
            <!-- <a href="/">Leçons de FoilKite</a>
            <a href="/">Inscrivez-vous</a>  -->
        </div>
    </div>
</section>