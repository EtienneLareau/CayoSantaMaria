<script>
    function scrollDown() {
        document.querySelector('#Register').scrollIntoView({ 
        behavior: 'smooth' });
    }
</script>

<style>
	
	.rolldown {
		position: relative;
		float: right;
		z-index:2010;
		padding:2px 20px;
		cursor: pointer;
		
	}

	p {
		color:white;
		border-radius: 2px;
		background: #ff22aa;
		box-shadow: 2px 2px 2px rgb(33, 33, 33),
					4px 4px 4px rgb(80, 80, 80);
		padding: 10px 30px;
		font-size:1.5rem;
		transition: all 0.25s ease;
		font-family: bicyclette, sans-serif;
		font-weight: 400;
		font-style: normal;
	}

	p:focus, p:hover {
		color:#ff22aa;
		background: #86fadb;
		box-shadow:none;
	}

	@media only screen and (max-width:725px){
		.regEx { display:none; }
	}

</style>

	<div class="rolldown" on:click={scrollDown}>
		<p class="regEx">Inscrivez-vous</p>
	</div>
 