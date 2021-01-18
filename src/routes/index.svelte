<script>
	import Counter from '$components/Counter.svelte';
</script>

<main>
	<h1>Hello world!</h1>

	<Counter/>
	<p>Visit the <a href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte apps.</p>
</main>

<style lang="postcss">
	main {
		@apply px-8 py-16 mx-auto max-w-5xl text-center;
	}

	* + * {
		@apply mb-0 mt-4;
	}

	p {
		@apply text-xl;
	}
</style>