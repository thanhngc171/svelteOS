<script lang="ts">
	import '@mdi/font/css/materialdesignicons.min.css';
</script>

<main>
	<slot />
</main>

<style lang="scss">
	:global(html, body) {
		height: 100%;
		margin: 0;
		padding: 0;
	}

	:global(body) {
		font-family: var(--font-regular);
		font-size: var(--base-font-size);
		color: var(--text-color);
	}

	:global(.mdi) {
		font-size: var(--icon-font-size);
	}

	main {
		height: 100%;
	}
</style>
