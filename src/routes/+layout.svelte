<script lang="ts">
	import "../app.css";
	let { children } = $props();
</script>

<svelte:head>
	<title>Solid Matrix</title>
</svelte:head>

{@render children()}
