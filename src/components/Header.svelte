<script>
	import Navbar from './Navbar.svelte';
</script>

<header class="Header">
	<div class="contenedor">
		<div class="navegacion">
			<div>
				<h2>Landing Page</h2>
			</div>
			<Navbar />
		</div>
	</div>
	<div class="contenedor">
		<div class="header-titulo">
			<h1>Pagina Principal</h1>
		</div>
	</div>
</header>

<style>
	.Header {
		background-image: url(code.jpg);
		background-size: cover;
		height: 45rem;
		background-position: center center;
		background-repeat: no-repeat;
		background-attachment: fixed;
		margin-bottom: 3rem;
	}

	.header-titulo {
		color: aliceblue;
		text-align: center;
		margin-top: 10rem;
		padding: 0;
	}
	.contenedor {
		max-width: 1200px;
		margin: 0 auto;
	}

	.navegacion {
		padding: 40px;
		text-align: center;
	}
	@media (min-width: 768px) {
		.navegacion {
			display: flex;
			justify-content: space-between;
			align-items: center;
		}
	}
</style>
