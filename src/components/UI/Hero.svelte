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

        .container { background: url('/images/covFoilS2W.jpg') right top no-repeat;
                     background-size: cover; } 
    }

    .dark {
        width:100%;
        height:100%;
        top:0;
        left:0;
        background: rgba(0, 0, 0, 0.112);
        /* background: #86fadbe9; */
    }

    img {
        width:200px;
        margin-bottom:10px;
    }

    @keyframes rotating
	{
	from
		{
		transform: rotate(0deg);
		-o-transform: rotate(0deg);
		-ms-transform: rotate(0deg);
		-moz-transform: rotate(0deg);
		-webkit-transform: rotate(0deg);
		}
	to
		{
		transform: rotate(360deg);
		-o-transform: rotate(360deg);
		-ms-transform: rotate(360deg);
		-moz-transform: rotate(360deg);
		-webkit-transform: rotate(360deg);
		}
	}
@-webkit-keyframes rotating
	{
	from
		{
		transform: rotate(0deg);
		-webkit-transform: rotate(0deg);
		}
	to
		{
		transform: rotate(360deg);
		-webkit-transform: rotate(360deg);
		}
	}
.rotating
	{
	-webkit-animation: rotating 6s linear infinite;
	-moz-animation: rotating 6s linear infinite;
	-ms-animation: rotating 6s linear infinite;
	-o-animation: rotating 6s linear infinite;
	animation: rotating 6s linear infinite;
	}

    img {
        width:200px;
        position:absolute;
        right:10px;
        bottom:10px;
    }
    .mid-text {
        position:absolute;
        right:57px;
        bottom:50px;
        text-align: center;
        color:white;
        font-size:1.7rem;
        text-shadow: none;
    }
</style>


<section>
    <div class="container">
        <div class="dark"></div>
        <div class="banner">
            <h2>Foil Kitecamp</h2>
            <!-- <p>Du <span style="font-size:1.5em">11</span> au <span style="font-size:1.5em">17</span> janvier 2020</p> -->
        </div>
            <p class="mid-text">Prochain<br>voyage</p>
          <img class="rotating" src="/images/Circle_dates3.png" alt="Les dates du voyage dédié Foil">
    </div>
</section>