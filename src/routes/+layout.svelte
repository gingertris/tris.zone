
<script lang="ts">
	import { transition_in } from "svelte/internal";
    import "../app.sass"
</script>

<svelte:head>
    <title>tris.zone</title>
</svelte:head>

<div id="header">
    <p><a href="/" class="text-pink">tris.zone</a></p>
</div>

<hr />

<slot />
