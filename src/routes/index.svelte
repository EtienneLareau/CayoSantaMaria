<script>
	import Hero from '../components/UI/Hero.svelte';
	import Intro from '../components/UI/Intro.svelte';
	import Offer from '../components/UI/Offer.svelte';
	import Ready from '../components/UI/Ready.svelte';
	import Services from '../components/UI/Services.svelte';
	import Newsletter from '../components/UI/Newsletter.svelte';
	
</script>


<svelte:head>
	<title>Venez Foiler à Cayo Santa Maria</title>
</svelte:head>

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
<Newsletter />

