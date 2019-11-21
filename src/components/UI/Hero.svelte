<script>
    let logo = 'images/LogoOnly.png';
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
        position: absolute ;
        top: 50% ;
        left: 50% ;
        transform: translate(-50%, -50%);
        z-index: 15;
        text-align: center ;
        color: rgb(255, 255, 255);
        text-transform: uppercase ;
        padding:0;
        margin:0;
    }


    img {
        opacity:0;
         width: 120px;
        margin-bottom: 1rem;
         transition: all 1s ;
    }
    
    h1, p {
        /* font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; */
        font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
    }

    h1 {
        font-size: 5vw;
        padding:0;
        margin:0;
    }

    p {
        font-size: 3vw;
        line-height: 0.4;
    }

     @media only screen and (max-width:700px){
        img {
        width: 120px;
        margin-bottom: 1rem;
        opacity:1;
        }
        h1 {
            font-size:4.1rem;
        }
        p {
            font-size:1.9rem;
            line-height:1.3;
        }
    }
</style>

<section>
    <div class="container">
        <div class="banner">
            <img src="{logo}" alt="logo">
            <h1>Foil Kitecamp</h1>
            <p>Du <span style="font-size:1.7em">11</span> janvier au <span style="font-size:1.7em">17</span> janvier 2020</p>
            <!-- <a href="/">Leçons de FoilKite</a>
            <a href="/">Inscrivez-vous</a>  -->
        </div>
    </div>
</section>