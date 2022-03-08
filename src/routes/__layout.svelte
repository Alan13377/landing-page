<script>
	import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<Header />
<body>
	<main>
		<slot><!-- optional fallback --></slot>
	</main>
	<Footer />
</body>
