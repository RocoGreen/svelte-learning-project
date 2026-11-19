<script>
	import LayoutLeftNavigationStreamerCard from './streamer_card/LayoutLeftNavigationStreamerCard.svelte';

</script>


<ul>
    {#each {length : 5}}
        <LayoutLeftNavigationStreamerCard/>
    {/each}
</ul>


<style>
    ul {
        display: flex;
        flex-direction: column;
        row-gap: 5px;
    }
</style>