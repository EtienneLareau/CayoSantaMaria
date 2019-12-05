<style>
    section {
        position: relative;
        width: 100% ;
        height:800px;
         
    }

    label {
        margin: 0 0 60px;
        font-family: 'battlefin', sans-serif;
	    font-weight: 400;
        font-style: normal;
        font-size: 1.3rem ;
        line-height: 1.2;
        cursor: pointer ;
    }

    p {
        font-size: 1.3rem ;
        margin:0;
        text-align:center;
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
        margin: 200px auto;
        top: 50% ;
        left: 50% ;
        transform: translate(-50%, -50%) ;
    }
    input, input:focus {
        display: block;
        height: 30px ;
        width: 100% ;
        border: 1px solid #278e73;
        cursor: pointer ;
        margin-bottom: 32px;
        color: #278e73;
        text-align:center;
        font-size: 1.7rem;
        padding: 8px 0;
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
        position: relative;
        left:50%;
        transform: translate(-50%,0%);
        
    }

    button:focus, button:hover {
        background: #86fadb;
        color:#278e73;
        box-shadow:none;
        border-radius:50px;
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
        <h2 class="title">Vous voulez devenir un foileux ?</h2>
        <p class="para">Inscrivez-vous ci-dessous.<br>Un agent vous contactera dans les prochaines 24 heures.</p>
        <br><br>
        <form name="FoilContactForm" method="POST" Content-Type="application/x-www-form-urlencoded" netlify action="/about">
            <input type="hidden" name="form-name" value="FoilContactForm" />
            
            <label for="name"><p>Nom et prénom</p></label>
                <input type="text" id="name" name="clientNames" placeholder="" required >
            
            <label for="phone"><p>Numéro de téléphone</p></label>
                <input type="tel" id="phone" name="clientPhone" placeholder="" required >
            
            <label for="email"><p>Entrez votre adresse courriel</p></label>
                <input type="email" id="email" name="clientEmail"  required/>
            
            <button type="submit">INSCRIVEZ-VOUS</button>
        </form>
    </div>
</section>