<script lang="ts">
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href="/pfp.png" />
</svelte:head>

{@render children()}
