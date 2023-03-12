<script>
    import { width , height} from "../game/game";
	import App from "../game/App.svelte";
    

</script>
<svelte:window 
bind:innerWidth={$width} 
bind:innerHeight={$height} 

/>

<App></App>