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
    
    h2 {    font-family: gill-sans-nova-shadowed-outl, sans-serif;
            font-style: normal;
            text-shadow: 3px 3px 0px rgb(18, 97, 74),
                         6px 6px 0px orange,
                         9px 9px 0px yellow,
                         12px 12px 0px blueviolet,
                         15px 15px 0px rgb(18, 97, 74),
                         18px 18px 0px orange,
                         21px 21px 0px yellow,
                         24px 24px 0px blueviolet,
                         27px 27px 0px rgb(18, 97, 74),
                         30px 30px 0px orange,
                         33px 33px 0px yellow,
                         36px 36px 0px blueviolet,
                         39px 39px 0px rgb(18, 97, 74),
                         42px 42px 0px orange,
                         45px 45px 0px yellow,
                         48px 48px 0px blueviolet;
            transition: all 1s ease-out; }

    h2 {  font-size: 12vw;
          color:#86fadb;
          font-weight: 400;
          padding:0;
          margin:0 0 -10px;
          line-height:1.1; }

    h2:hover {
        color:white;
        text-shadow: 1px 1px 1px white;
    }

    .red {
        text-shadow: 1px 1px 0px red,
                     100px 100px 0px red;
    }


    @media only screen and (max-width:700px){
        
        h2 { font-size:15vw;
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

</style>

<Register />
<section>
    <div class="container">
        <div class="dark"></div>
        <div class="banner">
            <h2>Foil Kitecamp</h2>
            <h2 class="red">Foil Kitecamp</h2>
            <!-- <p>Du <span style="font-size:1.5em">11</span> au <span style="font-size:1.5em">17</span> janvier 2020</p> -->
        </div>
            <RotateWhite />
            <!-- <p class="mid-text">Prochain<br>voyage</p>
            <img class="rotating" src="/images/Circle_dates3.png" alt="Les dates du voyage dédié Foil"> -->
    </div>
</section>