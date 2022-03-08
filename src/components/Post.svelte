<div class="posts">
	<section class="post">
		<div>
			<img src="code.jpg" alt="" />
		</div>
		<h3>Titulo</h3>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias culpa itaque repellat neque
			nemo, libero amet nisi sapiente suscipit. Voluptatem reprehenderit praesentium officiis
			recusandae provident laboriosam obcaecati adipisci doloremque deleniti.
		</p>
	</section>
	<section class="post">
		<div>
			<img src="javascript.jpg" alt="" />
		</div>
		<h3>Titulo</h3>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias culpa itaque repellat neque
			nemo, libero amet nisi sapiente suscipit. Voluptatem reprehenderit praesentium officiis
			recusandae provident laboriosam obcaecati adipisci doloremque deleniti.
		</p>
	</section>
	<section class="post">
		<div>
			<img src="ux.jpg" alt="" />
		</div>
		<h3>Titulo</h3>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias culpa itaque repellat neque
			nemo, libero amet nisi sapiente suscipit. Voluptatem reprehenderit praesentium officiis
			recusandae provident laboriosam obcaecati adipisci doloremque deleniti.
		</p>
	</section>
</div>

<style>
	h2 {
		font-size: 3.2rem;
		text-align: center;
	}
	h3 {
		text-align: center;
	}
	img {
		width: 100%;
	}

	.posts {
		margin-bottom: 2rem;
	}
	@media (min-width: 768px) {
		.posts {
			display: grid;
			grid-template-columns: repeat(3, 1fr);
			gap: 2rem;
			margin-bottom: 2rem;
		}
	}
</style>
