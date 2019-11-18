<script>
    let logo = 'images/LogoKitecamps.png';
</script>

<style>

    .container {
        width:100%;
        height:95vh;
        background: url('/images/beach.jpeg') right center no-repeat;
        background-size: cover ;
    }

    section {
        position: relative;
    }

    .resp-container {
        position: relative;
        overflow: hidden;
        padding-top: 56.25%; /* This is 9th / 16th */
    }

    .resp-iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border: 0;
        transform: scale(1.2);
    }

    .banner {
        position: absolute ;
        left:50% ;
        bottom:5%;
        transform: translate(-50%, -50%);
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
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }

    h1 {
        font-size: 4vw;
    }

    p {
        font-size: 2vw;
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
        position: relative;
        padding: 20px 40px;
        font-size: 1.2rem ;
        background: rgb(255, 74, 104);
        text-decoration: none ;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        border-radius: 100px;
        margin: 25px;
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
        <!-- <iframe title="Kitesurfer foiling in Cuba" class="resp-iframe"
                src="{clip}" 
                frameborder="0" 
                allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture">
        </iframe> -->
        <!-- <img src="./images/ikocov.jpeg" alt="cover"> -->
    </div>
    <!-- <div class="fallback"></div> -->
    <div class="banner">
        <!-- <img src="{logo}" alt="logo"> -->
        <h1>Foil Kitecamp</h1>
        <p>Du 11 janvier au 17 janvier 2020</p>
        <a href="/">Leçons de FoilKite</a>
        <a href="/">Inscrivez-vous</a>
        
    </div>
</section>