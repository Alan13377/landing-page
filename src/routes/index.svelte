<script>
	import Post from '../components/Post.svelte';
	import Contacto from '../components/Contacto.svelte';
</script>

<svelte:head>
	<title>Inicio</title>
</svelte:head>
<main class="contenedor">
	<h1>Ultimos Post</h1>
	<Post />
</main>
<section class="banner">
	<div class="banner-contenido">
		<h2>Suscribete</h2>
		<p>Consulta nuestros post</p>
		<div class="enlace-post">
			<a href="/blog" class="btn">Ver Posts</a>
		</div>
	</div>
	<img src="codigo.jpg" alt="" />
</section>
<section>
	<Contacto />
</section>

<style>
	h1 {
		text-align: center;
		margin-bottom: 2rem;
	}
	img {
		max-width: 100%;
	}
	.contenedor {
		max-width: 1200px;
		margin: 0 auto;
	}
	.banner {
		font-size: 40px;
		background-color: #213e8c;
	}
	.banner-contenido {
		font-size: 30px;
		color: #fff;
		text-align: center;
		padding: 50px;
	}
	@media (min-width: 768px) {
		.banner {
			background-color: #213e8c;
			display: grid;
			grid-template-columns: 1fr 2fr;
			justify-content: center;
			align-items: center;
		}
		.banner-contenido {
			text-align: center;
		}
	}

	.btn {
		background-color: #c84869;
		padding: 15px 25px;
		font-size: 20px;
		text-transform: uppercase;
		text-decoration: none;
		color: white;
		text-align: center;
	}

	.btn:hover {
		cursor: pointer;
		background-color: #870026;
	}
	.enlace-post {
		margin-top: 30px;
		margin-bottom: 30px;
	}
</style>
