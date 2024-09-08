<script>
	import Header from '$lib/components/elements/header/header.svelte';
	import '../app.css';
</script>

<main>
	<Header />
	<slot></slot>
</main>

<style>
	main {
		display: flex;
		flex-direction: column;

		@apply min-h-screen;

		background-color: var(--background);
		color: var(--foreground);
	}
</style>
