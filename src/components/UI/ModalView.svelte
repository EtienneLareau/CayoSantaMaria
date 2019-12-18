<script>
	import { fade, fly } from 'svelte/transition';
	
    export let visible = false;
	
	function fuck() {
		visible = false;
	}
    
    
    
</script>

<style>
	.modal {
		background: rgba(0, 0, 0, 0.687);
		width: 100%;
		height: 100vh;
		position: fixed;
		z-index: 1000;
		top:0;
		left:0;
		right:0;
		bottom:0;
	}

	.modal-container {
		max-width:500px;
		height:auto;
		padding: 40px 25px;
		background: whitesmoke;
		position: fixed;
		z-index: 1200;
		top:100px;
		left:50%;
		border-radius: 20px;
		transform: translate(-50%,0%);
		box-shadow:10px 10px 15px #86fadb;
	}

	.close-btn {
		color: #ff22aa;
		font-weight:900;
		font-size:2.1rem;
		position:absolute;
		top:10px;
		right:10px;
		border:none;
		background: whitesmoke;
	}

	.numbers-title {
        font-family: 'feltro-texture-3', sans-serif;
        font-size: 70px;
		text-align: center;
        padding:20px;
        color: #86fadb;
        /* background-color: rgb(18, 97, 74); */
        background: #ff22aa ;
        border-radius:100px;
        width:80px;
        margin: 0 auto 30px;
        box-shadow:5px 5px 10px rgba(128, 128, 128, 0.858);
    }

	input[type=checkbox] {
		display:none;
	}

	h2 {
		font-size:3.2rem;
		font-weight:700;
	}

	p {
		font-size:1.4rem;
		font-weight: 300;
	}

	.back-modal {
		position: relative;
	}

</style>

<button >
    <label>
        <input id="checked" type="checkbox" bind:value={visible} >
            <h3 class="numbers-title">1</h3>
    </label>
</button>
	
    <div class="back-modal">
		<div on:click={fuck} class="modal" in:fade="{{ x: 100, duration: 550, delay:1000 }}" 
						   out:fade="{{ y:-800, duration: 250, }}"></div>
			<div class="modal-container">
				<button class="close-btn" on:click={fuck}>X</button>
				<h2>VOUS ÊTES INSCRIT !!!</h2>
				<p>Good Job!!</p>
				<p>Vous recevrez un appel sous peu</p>
				<p>**Note : Compte tenu du nombre élevé d'inscription, un délai de 48h peu être requis avant de recevoir un appel d'un mdemebre de notre service à la clientèle.</p>
				
			</div>


	</div>