<style>
    section {
        position: relative;
        width: 100% ;
        height: 500px ;
        background: #278e73 ; 
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
        border: none;
        cursor: pointer ;
        margin-bottom: 22px;
        color: red;
        font-size: 1.1rem;
        padding: 8px 10px;
    }

    

    
</style>

<section>
    <div class="block">
        <h2 class="title">Vous ne voulez manquez aucun voyage ?</h2>
        <p class="para">Inscrivez-vous à notre infolettre pour ne rien manqué</p>
        
        <form action="/" name="contactForm" method="POST" netlify>
            <label for="name">Nom et prénom</label>
                <input type="text" id="name" name="names" placeholder="" required >
            
            <label for="email">Entrez votre adresse courriel</label>
                <input type="email" id="email" name="email"  required/>
            
            <button type="submit">S'inscrire</button>
        </form>
    </div>
</section>