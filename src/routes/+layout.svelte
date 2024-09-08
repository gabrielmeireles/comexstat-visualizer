<script>
	import Header from '$lib/components/elements/header/header.svelte';
	import '../app.css';
</script>

<main class="flex h-screen w-screen flex-col">
	<Header />
	<article class="p-4">
		<slot></slot>
	</article>
</main>
