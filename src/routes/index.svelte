<script>
	import Hero from '../components/UI/Hero.svelte';
	import Intro from '../components/UI/Intro.svelte';
	import Offer from '../components/UI/Offer.svelte';
	import Ready from '../components/UI/Ready.svelte';
	import Services from '../components/UI/Services.svelte';
	import Newsletter from '../components/UI/Newsletter.svelte';
	import KiteVideo from '../components/UI/KiteVideo.svelte';
	import SantaMaria from '../components/UI/SantaMaria.svelte';
	import Transition from '../components/UI/Transition.svelte';
	import Fullapp from '../components/UI/Fullapp.svelte';
</script>


<svelte:head>
	<title>Venez apprendre à "kitefoiler" à Cayo Santa Maria, Cuba.</title>
</svelte:head>


<!-- <Fullapp /> -->

<!-- Mega banniere avec menu et choix d'info boutons -->
<Hero /> 

<!-- premier text qui explique le voyage -->
<Intro /> 

<!-- First video - kiters - foilers -->
<KiteVideo /> 

<!-- offee de servcies des cours Multi logo -->
<Offer /> 

<!-- Santa Maria -->
<SantaMaria /> 

<!-- <Ready /> --> <!-- video -->

<!-- le mega texte de ben -->
<Services />  

<Newsletter />

