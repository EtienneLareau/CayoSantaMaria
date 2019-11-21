<script>
	export let segment;
	let logo = 'images/supatitle.png';
</script>

<style>
	nav {
		font-weight: 300;
		padding: 0 1em;
		position: relative;
		z-index: 1000;
	}
	@media only screen and (max-width:1025px){
		ul{display:none;}
	}


	img {
        width: 200px;
        margin: 3rem;
		float: left;
		opacity:1;
		transition: all 1s;
    }
	@media only screen and (max-width:700px){
		img {
			opacity:0;
			
			}
	}

	ul {
		position: absolute;
		margin: 0;
		left:240px;
		padding: 0;
		margin-left:40px;
		/* background: palegoldenrod; */
	}

	/* clearfix */
	ul::after {
		content: '';
		display: block;
		clear: both;
	}

	li {
		display: block;
		float: left;
		margin-top:27px;
		color: white ;
		 /* font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; */
		font-family: 'battlefin', sans-serif;
        font-weight: 400;
        font-style: normal;
		 font-size: 1.5em;
		 letter-spacing: 1.3px;
		 text-shadow: 1px 1px 3px grey ;
		 
	}

	.selected {
		position: relative;
		display: inline-block;
	}

	.selected::after {
		position: absolute;
		content: '';
		width: calc(100% - 2em);
		
		/* transform: translate(50%,0); */
		height: 5px;
		background-color: rgb(255, 74, 104);
		display: block;
		bottom: -1px;
	}

	a {
		text-decoration: none;
		padding: 1em 0.8em;
		display: block;
		transition: all 0.2s ease ;
	}

	a:hover {
		color: rgb(255, 177, 190);
	}

	.bump {
		margin-left:2em;
	}
</style>

<nav>
	<img src="{logo}" alt="logo">
	<ul>	
		<li class="bump"><a class='{segment === undefined ? "selected" : ""}' href='.'>Accueil</a></li>
		<li><a class='{segment === "about" ? "selected" : ""}' href='about'>Services</a></li>
		
		<!-- for the blog link, we're using rel=prefetch so that Sapper prefetches
		     the blog data when we hover over the link or tap it on a touchscreen -->
		<li><a rel=prefetch class='{segment === "blog" ? "selected" : ""}' href='blog'>Cours</a></li>
		<li><a class='{segment === "contact" ? "selected" : ""}' href='contact'>Contactez-nous</a></li>
	</ul>
</nav>