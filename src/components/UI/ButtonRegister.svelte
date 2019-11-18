
<style>
    .button-prix {
        position: relative;
        width: 100%;
        height: 400px;
    }

    .prix {
        position: absolute;
        width:100%;
        padding: 20px 0;
        z-index:20;
        background: rgb(216, 112, 147) ;
        color: white ; 
        font-size: 40px;
        opacity: 1;
        margin-top: 0px;
        cursor: pointer;
        transition: opacity 0.3s ease ;
    }

    .prix:hover,
    .prix:focus {                               
        opacity: 0;
        display:none;
    }

    .prix-hide {
        position: absolute;
        text-align: center;
        width:100%;
        padding: 20px 0;
        z-index:10;
        background: rgb(112, 216, 209);
        color: black ; 
        font-size: 40px;
        
    }
    a {
        cursor: pointer;
        text-decoration: none ;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }

</style>

<div class="button-prix">
    <p class="prix">Chui Game!!!</p>
    <a class="prix-hide" href="/about">Je m'inscris pour vrai !</a> 
</div>