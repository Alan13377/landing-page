<script>
	import Navbar from './Navbar.svelte';
</script>

<footer class="footer">
	<div class="contenedor">
		<div class="navegacion">
			<div>
				<h2>Landing Page</h2>
			</div>
			<Navbar />
		</div>
		<div class="redes">
			<img src="facebook.png" alt="" />
			<img src="gorjeo.png" alt="" />
			<img src="whatsapp.png" alt="" />
		</div>
	</div>
</footer>

<style>
	img {
		width: 30px;
		height: 30px;
	}
	.footer {
		margin-top: 4rem;
		padding-bottom: 2rem;
		background-color: #213e8c;
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

	.redes {
		display: flex;
		justify-content: center;
		gap: 2rem;
	}
	@media (min-width: 992px) {
		.redes {
			display: flex;
			justify-content: flex-end;
			gap: 2rem;
		}
	}
</style>
