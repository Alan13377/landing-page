<main class="contenedor">
	<h3>Sobre Nosotros</h3>
	<div class="about">
		<div class="sobre-nosotros__imagen">
			<img
				src="https://res.cloudinary.com/daadki0ie/image/upload/v1641425505/Code-min_betbxc.jpg"
				alt="Sobre-Nosotros"
			/>
		</div>
		<div class="sobre-nosotros__texto">
			<p>
				Lorem ipsum dolor sit amet, consectetur adipisicing elit. Incidunt veniam accusantium modi
				aut iusto nihil provident quas exercitationem ex adipisci? Similique numquam saepe
				dignissimos sequi nobis modi consequuntur voluptate! Cupiditate!
			</p>
			<p>
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis quod rem aperiam
				repellat, doloremque non. Ratione explicabo veniam odit quam. Eligendi beatae at sequi ab
				accusamus dicta, delectus incidunt! A.
			</p>
		</div>
	</div>
</main>

<style>
	img {
		width: 100%;
		height: auto;
	}
	.contenedor {
		max-width: 1200px;
		margin: 0 auto;
	}
	h3 {
		font-size: 30px;
		text-align: center;
		margin-bottom: 2rem;
	}
	@media (min-width: 768px) {
		.about {
			display: grid;
			grid-template-columns: repeat(2, 1fr);
			gap: 2rem;
		}
	}
	.titulo {
		margin-top: 5rem;
	}
</style>
