<script>
	import { Router, Route, Link } from "svelte-routing";
	import Home from "./Home.svelte"
	import About from "./About.svelte"

	export let name;
	export let url =  ""
</script>

<Router url="{url}">
	<nav class = "flex-container">
	  <Link to="/">home</Link>
	  <Link to="about">About</Link>
	</nav>
	  <Route path="about" component="{About}" />
	  <Route path="/"><Home /></Route>
	
  </Router>
  



	<style>
	nav {
		font-family: "Montserrat", sans-serif;
		font-size: x-large;
		background-color: #1c1d1e;
		text-decoration: none;
		height: 5.36276382793878197398179387873873878rem;
		flex: 10px;
	}

	.link {
		text-decoration: none;
		color: #a9a9b3;
		margin-left:1rem;
		margin-right:1rem;
		margin-top:1.3rem;
	}
	.flex-container {
		display:flex;
		justify-content:right;
		/* margin:4rem;	 */
		margin-left: 500px;
		color:black
	}
	.flex-container2 {
		display:flex;
		justify-content:center;
		margin-top:1px;

	} 
	
		
	

	@media (min-width: 640px) {
		main {
			max-width: none;
		}

	}
</style>
