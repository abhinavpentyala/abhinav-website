<script>
	let name = "Abhinav Pentyala"
</script>

<main>
	<div class="header">
		<h1>
			{name}
		</h1>
		<p>7th Grade Student | Learning CS</p>
		<div class = "icons">
		<a href="https://github.com/abhinavpentyala"
			><i class="fa fa-github fa-3x" aria-hidden="true" />
		</a>
		<a href="mailto:abhinav.pentyala@gmail.com"
			><i class="fa fa-envelope fa-3x" aria-hidden="true" />
		</a></div>
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		background-color: #232425;
	}

	h1 {
		color: #a9a9b3;
		font-size: 5em;
		font-weight: 100;
		text-align: center;
		margin: 1rem;
		font-family: "Roboto", sans-serif;
	}

	.header {
		height: 100vh;
		margin-top: 20vh;
	}

	p {
		display: block;
		font-size: xx-large;
		color: #a9a9b3;
		font-weight: 500;
		font-family: "Montserrat", sans-serif;
	}

	i {
		color: #a9a9b3;
		size: 1000em;
	}
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
	}
	.flex-container2 {
		display:flex;
		justify-content:center;
		margin-top:1px;
	} 
	.icons {
		display:grid;
		grid-row-gap:100px;
		grid-template-columns: 100px 100px;
		margin: 0 auto;
		width:300px;

		
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}

	}
</style>
