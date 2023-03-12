<script>
    import { width , height} from "../_game/game";
	import App from "../_game/App.svelte";
    

</script>
<svelte:window 
bind:innerWidth={$width} 
bind:innerHeight={$height} 

/>

<App></App>