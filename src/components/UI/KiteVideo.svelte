<script>

</script>

<style>
    section {
        position: relative;
        max-width: 800px;
        margin: 100px auto 100px;
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
    }


    .fallback {
        position: absolute;
        top:0;
        left:0;
        bottom:0;
        right:0;
        z-index: 100;
    }

    .cov {
        position: absolute;
        left:0;
        top:0;
        z-index: 115;
        background: rgba(189, 189, 189, 0);
        width:100%;
        height:100%;
    }
</style>

<section>
    <div class="resp-container">
        <div class="cov"></div>
        <iframe title="video showing the beach of Cayo Santa Maria"
                class="resp-iframe"
                src="https://www.youtube.com/embed/Jd2KnrbSPT0?controls=0&amp;start=7&end=72;&loop=1&playlist=Jd2KnrbSPT0&autoplay=1&mute=1" 
                frameborder="0" 
                allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture">
        </iframe>
    </div>
    <!-- <div class="fallback"></div> -->
</section>