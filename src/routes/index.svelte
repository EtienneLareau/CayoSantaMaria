<script>
	import Hero from '../components/UI/Hero.svelte';
	import Intro from '../components/UI/Intro.svelte';
	import Offer from '../components/UI/Offer.svelte';
	import Ready from '../components/UI/Ready.svelte';
	import Services from '../components/UI/Services.svelte';
	
	
</script>

<style>

	section {
		
		background-image: url('../images/cuba-cov.jpeg');
		background-position: center ;
		background-repeat: no-repeat ;
		background-size: cover ;
		width: 100% ;
		height: 100vh ;
		margin: 0 ;
		padding: 0 ;
	}

	.title {
		position: absolute;
		top: 50% ;
		left: 50% ;
		transform: translate(-50%, -50%);
		z-index: 10 ;
		color: rgb(255, 89, 89) ;
		text-shadow: 10px 10px 4px black ;
		text-align: center ;
		
		
	}

	* {
		font-family: 'feltro-texture-3', sans-serif;
		font-weight: 400;
		font-style: normal;
		}

	h1 {
		font-size: 300px ;
	}
	h2, p {
		font-size: 150px ;
		color: rgb(179, 0, 255) ;
		text-shadow: 5px 5px 3px black ;
	}
</style>

<svelte:head>
	<title>Foil Cayo Santa Maria</title>
</svelte:head>

<!-- <section>
	<div class="title">
		<h1>Foil Kite Camp</h1>
		<h2>Venez parfaire votre technique de kitefoil</h2>
		<p>Du 11 janvier au 17 janvier 2020</p>
	</div>
</section> -->


<!-- Mega banniere avec menu et choix d'info boutons -->
<Hero /> 

<!-- premier text qui explique le voyage -->
<Intro />

<!-- offee de servcies des cours Multi logo -->
<Offer />

 <!-- le mega texte de ben -->
<Services />
<!-- video -->
<Ready />

