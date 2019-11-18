<script>
    let clip = '';
    let logo = 'images/LogoKitecamps.png';
</script>

<style>
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
        top :52%;
        transform: translate(-50%, -50%);
        z-index: 15;
        text-align: center ;
        color: rgb(255, 255, 255);
        text-transform: uppercase ;  
    }

    img {
        width: 16%;
        margin-bottom: 1rem;
    }
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

    .ready {
        position: relative;
        top:-200px;
    }

    .cov {
        position: absolute;
        left:0;
        top:0;
        z-index: 15;
        background: rgba(0, 0, 0, 0.132);
        width:100%;
        height:100%;
    }
</style>

<section class="ready">
    <div class="resp-container">
        <div class="cov"></div>
        <iframe class="resp-iframe"
                src="https://www.youtube.com/embed/N6RdFH_6a1Q?controls=0&amp;start=7&end=72;&loop=1&playlist=N6RdFH_6a1Q&autoplay=1&mute=1" 
                frameborder="0" 
                allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"></iframe>
    </div>
    <div class="fallback"></div>
</section>