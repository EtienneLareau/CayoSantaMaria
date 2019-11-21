<script>
    let logo = 'images/LogoKitecamps.png';
</script>

<style>
     section {position: relative;}

    .container {
        width:100%;
        height:100vh;
        background: url('/images/cayoCov.jpeg') right center no-repeat;
        background-size: cover ;
    }

    .banner {
        position: relative ;
        top: 60% ;
        left: 50% ;
        transform: translate(-50%, 0);
        z-index: 15;
        text-align: center ;
        color: rgb(255, 255, 255);
        text-transform: uppercase ;  
    }

    /* img {
        width: 19%;
        margin-bottom: 1rem;
    } */
    h1, p {
        /* font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; */
        font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
    }

    h1 {
        font-size: 5vw;
    }

    p {
        font-size: 3vw;
        line-height: 0.4;
    }

    .fallback {
        position: absolute;
        top:0;
        left:0;
        bottom:0;
        right:0;
        z-index: 100;
    }
    
    a {
        padding: 20px 40px;
        font-size: 1.9rem ;
        background: rgb(255, 74, 104);
        text-decoration: none ;
        font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
        border-radius: 100px;
        margin-top: 25px;
        top: 30px;
        cursor: pointer;
        transition: all 0.3s ease ;
    }

    a:hover {
        background: rgb(255, 128, 149) ;
    }
</style>

<section>
    <div class="container">
        <div class="banner">
            <!-- <img src="{logo}" alt="logo"> -->
            <h1>Foil Kitecamp</h1>
            <p>Du <span style="font-size:1.7em">11</span> janvier au <span style="font-size:1.7em">17</span> janvier 2020</p>
            <!-- <a href="/">Leçons de FoilKite</a>
            <a href="/">Inscrivez-vous</a>  -->
        </div>
    </div>
</section>