<script lang="ts">
	import "../app.css";

	let { children } = $props();
</script>

<svelte:head>
  <title>ChatJippity Admin</title>
</svelte:head>

{@render children()}
