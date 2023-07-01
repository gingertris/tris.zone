
<script lang="ts">
	import { transition_in } from "svelte/internal";
    import "../app.sass"
</script>

<svelte:head>
    <title>tris.zone</title>
    <a rel="me" href="https://introvert.country/@tris"></a>
</svelte:head>

<div id="header">
    <p><a href="/" class="text-pink">tris.zone</a></p>
</div>

<hr />

<slot />
