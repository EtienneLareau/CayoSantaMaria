<script>
    let logo = 'images/LogoOnly.png';
</script>


<style>

     section { position: relative; }

    .container { width:100%;
                 height:100vh;
                 background: url('/images/covFoil.jpeg') right top no-repeat;
                 background-size: cover; }

    .banner { position: absolute ;
              top:50% ;
              left: 50% ;
              transform: translate(-50%, -50%);
              z-index: 15;
              text-align: center ;
              color: white;
              text-transform: uppercase ;
              width:95%; }
    
    h2, p { font-family: 'battlefin', sans-serif;
            font-weight: 400;
            font-style: normal;
            text-shadow: 1px 1px 10px rgb(18, 97, 74); }

    h2 {  font-size: 6vw;
          padding:0;
          margin:0 0 -10px;
          line-height:1.1; }

    p { font-size: 3vw;
        line-height: 0.4; }

    @media only screen and (max-width:700px){
        h2 { font-size:3.1rem;
             line-height:1.1 }

        p { font-size:1.3rem;
            line-height:1.3; }

        .container { background: url('/images/covFoilS2.jpg') right top no-repeat;
                     background-size: cover; } 
    }

    .dark {
        width:100%;
        height:100%;
        top:0;
        left:0;
        background: rgba(0, 0, 0, 0.112);
    }

    img {
        width:200px;
        margin-bottom:10px;
    }
</style>


<section>
    <div class="container">
        <div class="dark"></div>
        <div class="banner">
            <!-- <img src="{logo}" alt="logo"> -->
            <h2>Foil Kitecamp</h2>
            <p>Du <span style="font-size:1.5em">11</span> au <span style="font-size:1.5em">17</span> janvier 2020</p>
            <!-- <a href="/">Leçons de FoilKite</a>
            <a href="/">Inscrivez-vous</a>  -->
        </div>
    </div>
</section>