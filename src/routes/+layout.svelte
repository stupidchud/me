<script lang="ts">
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href="https://github.com/6ae95ca5f809.png" />
	<link rel="stylesheet" href="/css/page.css" />
	<link rel="stylesheet" href="/css/modal.css" />
</svelte:head>

{@render children()}
