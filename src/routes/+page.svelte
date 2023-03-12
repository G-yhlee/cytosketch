<script>
    import { innerWidth } from "../store/store";

</script>
<svelte:window bind:innerWidth={$innerWidth} />

<p>The window inner width is {$innerWidth}</p>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
