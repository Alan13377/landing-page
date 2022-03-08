<script>
	import Post from '../components/Post.svelte';
</script>

<svelte:head>
	<title>Blog</title>
</svelte:head>
<main class="container">
	<Post />
	<Post />
	<Post />
</main>

<style>
	.container {
		max-width: 1200px;
		margin: 0 auto;
	}
</style>
