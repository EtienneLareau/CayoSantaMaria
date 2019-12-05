<style>
    section {
        position: relative;
        width: 100% ;
        height:700px;
         
    }

    label {
        margin: 0 0 60px;
        font-family: 'battlefin', sans-serif;
	    font-weight: 400;
        font-style: normal;
        font-size: 1.3rem ;
        line-height: 1.7;
        cursor: pointer ;
    }

    p {
        font-size: 1.3rem ;
        line-height: 1.9;
    }

    h2 {
        font-size: 3.2rem;
        line-height: 1;
    }

    h2, p {
        text-align: center ;
    }

    .block {
        position: absolute ;
        max-width: 800px;
        margin: 0 auto;
        top: 50% ;
        left: 50% ;
        transform: translate(-50%, -50%) ;
    }
    input {
        display: block;
        height: 30px ;
        width: 75% ;
        border: 1px solid #278e73;
        cursor: pointer ;
        margin-bottom: 22px;
        color: red;
        font-size: 1.1rem;
        padding: 8px 10px;
    }

    button {
        background: #278e73;
        color:white;
        padding: 20px 40px;
        border:none;
        font-size:1.5rem;
        box-shadow: 1px 1px 3px rgba(128, 128, 128, 0.425);
        transition: all 0.25s ease-out;
        cursor: pointer;
        border-radius:2px;
        
    }

    button:focus, button:hover {
        background: #86fadb;
        color:#278e73;
        box-shadow:none;
        border-radius:0px 50px 50px 0px;
    }

    @media only screen and (max-width:725px) {
        .block {
        position: relative ;
        max-width: 100%;
        margin: 40px 20px 40px;
    }

        h2 {
            font-size:1.9rem;
            padding-right:20px;
            text-align:left;
        }
        p {
            text-align: left;
            padding-right:20px;
        }
    }
    
</style>

<section>
    <div class="block">
        <h2 class="title">Vous ne voulez manquez aucun voyage ?</h2>
        <p class="para">Inscrivez-vous à notre infolettre pour ne rien manqué</p>
        
        <form name="FoilContactForm" method="POST" Content-Type="application/x-www-form-urlencoded" netlify action="/about">
            <input type="hidden" name="form-name" value="FoilContactForm" />
            <label for="name">Nom et prénom</label>
                <input type="text" id="name" name="clientNames" placeholder="" required >
            
            <label for="email">Entrez votre adresse courriel</label>
                <input type="email" id="email" name="clientEmail"  required/>
            
            <button type="submit">INSCRIVEZ-VOUS</button>
        </form>
    </div>
</section>