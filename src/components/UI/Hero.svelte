<script>
    let logo = 'images/LogoOnly.png';
    import RotateWhite from '../../components/UI/RotateWhite.svelte';
    import Register from '../../components/UI/Register.svelte';
</script>


<style>
    section { position: relative;
              z-index:13; }

    .container { width:100%;
                 height:100vh;
                 background: url('/images/covFoilS4.jpg') left top no-repeat;
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
    
    h2 {    
            font-style: normal;
            text-shadow: 4px 4px 8px rgb(18, 97, 74);
        }

    h2 {  font-size: 11vw;
          color:#86fadb;
          font-weight: 400;
          padding:0;
          margin:0 0 -10px;
          line-height:1.1; }


    @media only screen and (max-width:700px){
        
        h2 { font-size:11vw;
             line-height:1.1 }

        .container { background: url('/images/covFoilS4W.jpg') center top no-repeat;
                     background-size: cover; } 
    }
    /**/
    .dark {
        width:100%;
        height:100%;
        top:0;
        left:0;
        background: rgba(0, 0, 0, 0.112);
        /* background: #86fadbe9; */
    }

    @media only screen and (max-width: 850px) {
        .dark {
            background: rgba(0, 0, 0, 0.29);
        }
    }
</style>

<Register />
<section>
    <div class="container">
        <div class="dark"></div>
        <div class="banner">
            <h2>Foil<br>Kitecamp</h2>
            <!-- <p>Du <span style="font-size:1.5em">11</span> au <span style="font-size:1.5em">17</span> janvier 2020</p> -->
        </div>
            <RotateWhite />
            <!-- <p class="mid-text">Prochain<br>voyage</p>
            <img class="rotating" src="/images/Circle_dates3.png" alt="Les dates du voyage dédié Foil"> -->
    </div>
</section>