<script>
	export let segment;
	let logo = 'images/supatitle.png';

	// function readMenu() {
	// 	var el = document.getElementById('open');
	// 	if (el.className === 'openMenu'){
	// 		el.className = ' ';
	// 	} else {
	// 		el.className = 'openMenu';
	// 	}
	// }
	// console.log(readMenu);

	/// Function for opening and closing the menu bar ///
	function openNav() {
  		document.getElementById("Nav").style.width="100%";
		document.getElementById("Nav").style.opacity="1";
		document.getElementById("Nav").style.display="inherit";
		 

	}
	function closeNav() {
  		document.getElementById("Nav").style.width="0%";
		  document.getElementById("Nav").style.opacity="0";
		  document.getElementById("Nav").style.display="none";
		  
	}


	/// Function for sub menu and rotating arrow Simon ///
function openSubSim() {
	document.getElementById("openSubSim").style.height="210px";
	document.getElementById("arrowChirSim").style.color="#f49a6d";
	
	var el = document.getElementById("arrowChirSim");
  	el.classList.remove("rotatingArrowTop");

	var element, name, arr;
	element = document.getElementById("arrowChirSim");
	name = "rotatingArrow";
	arr = element.className.split(" ");
	if (arr.indexOf(name) == -1) {
	  element.className += " " + name;
	}
}

function openTopSim() {
	document.getElementById("openSubSim").style.height="0px";
	document.getElementById("arrowChirSim").style.color="#18385f";
	
	var el = document.getElementById("arrowChirSim");
  	el.classList.remove("rotatingArrow");

	var element, name, arr;
	element = document.getElementById("arrowChirSim");
	name = "rotatingArrowTop";
	arr = element.className.split(" ");
	if (arr.indexOf(name) == -1) {
	  element.className += " " + name;
	}
}
///////////////////////////////////////////////////////

</script>

<style>
	
	/* clearfix */
	ul::after {
		content: '';
		display: block;
		clear: both;
	}
/* 
	.selected {
		position: relative;
		display: inline-block;
	}

	.selected::after {
		position: absolute;
		content: '';
		width: calc(100% - 2em);
		
		
		height: 5px;
		background-color: rgb(255, 74, 104);
		display: block;
		bottom: -1px;
	} */

	a { text-decoration: none;
		transition: color 0.2s ease ;
		margin-left:-70px;
		color:rgb(28, 28, 28);
		font-size:7vw;
		font-family: 'battlefin', sans-serif;
        font-weight: 700;
		font-style: normal; }

	@media only screen and (orientation:landscape) {
		a {
			font-size:2rem;
		}
	}

	a:hover {
		color:pink;
	}

	.ul-center {
		
		top:50%;
		position: relative;
		transform: translate(0,-50%);
		list-style-type: none;
	}

	.vert { list-style-type: none;
			margin: 0 0 30px 0;
			text-align: center; }


	.menu {
		position: relative;
		float: right;
		z-index:2010;
		padding:30px;
		cursor: pointer;
	}

	.bars { width:2em;
			height:2px;
			margin-bottom:6px;
			background: #86fadb;
			box-shadow: 1px 1px 1px rgba(18, 97, 75, 0.493) }
	
	#Nav {  position: fixed;
			display:none;
			margin:0;
			padding:0;
			z-index: 2200;
			top:0;
			left:0;
			width:0%;
			height:100%;
			background: #86fadb;
			opacity:1;
			transition: all 0.15s ease-out, width 0s; }

	.close-Btn {
		position: absolute;
		right:0;
		top:0;
		z-index: 5500;
		color:rgb(134, 126, 126);
		background: #86fadb;
		font-size: 3em;
		padding:18px 30px;
		text-align:right;
		font-family: 'battlefin', sans-serif;
        font-weight: 700;
		font-style: normal;
		text-decoration: none;
	}
	img {
		position: absolute;
		width:150px;
		top:24px;
		left:30px;
		z-index: 7000;
	}
</style>

<!-- hamburger menu -->
<div class="menu" on:click={openNav}>
	<div class="bars"></div>
	<div class="bars"></div>
	<div class="bars"></div>
	<div class="bars"></div>
</div>
 <!-- ************* -->

<img src="/images/supatitle.png" alt="Logo KiteTrips.ca">
<div id="Nav">
	<!-- <img src="/images/supatitle.png" alt="Logo KiteTrips.ca"> -->
	<ul class="ul-center">	
		<li class="vert"><a class='{segment === undefined ? "selected" : ""}' href='.' on:click={closeNav}>Accueil</a></li>
		<li class="vert"><a class='{segment === "about" ? "selected" : ""}' href='about' on:click={closeNav}>Services</a></li>
		
		<!-- for the blog link, we're using rel=prefetch so that Sapper prefetches
		     the blog data when we hover over the link or tap it on a touchscreen -->
		<li class="vert"><a rel=prefetch class='{segment === "blog" ? "selected" : ""}' href='blog' on:click={closeNav}>Cours</a></li>
		<li class="vert"><a class='{segment === "contact" ? "selected" : ""}' href='contact' on:click={closeNav}>Contactez-nous</a></li>
	</ul>
	<a href="javascript:void(0)" class="close-Btn" on:click={closeNav}>X</a>
</div>