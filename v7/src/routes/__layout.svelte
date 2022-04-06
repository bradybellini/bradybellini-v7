<script>
	import '../styles/app.css';

	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<div class="bg-b-black border-b-white border text-center my-8 drop-shadow-lg mx-2 px-4">
	<header>
		<Header />
	</header>

	<main>
		<div class="mx-2 font-mono text-sm">
			<div class="text-b-white my-8">
				<slot />
			</div>
		</div>
	</main>

	<footer>
		<Footer />
	</footer>
</div>
