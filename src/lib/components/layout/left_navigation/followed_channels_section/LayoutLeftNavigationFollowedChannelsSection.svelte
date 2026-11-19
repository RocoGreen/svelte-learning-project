<script>
	import LayoutLeftNavigationStreamerCards from './../streamer_cards/LayoutLeftNavigationStreamerCards.svelte';

</script>


<section>
    <button>
        <h3>Followed Channels</h3>
        
        <svg width="24" height="24" viewBox="0 0 24 24" role="img">
            <path d="M13 7 8 2 3 7l1.414 1.621L7 6v9h2V6l2.5 2.5L13 7Zm8 10-5 5-5-5 1.414-1.621L15 18V9h2v9l2.5-2.5L21 17Z"></path>
        </svg>
    </button>

    <LayoutLeftNavigationStreamerCards/>
</section>



<style>
    button {
        display: flex;
        align-items: center;
        width: 100%;

        margin-bottom: 10px;
    }

    h3 {
        margin-right: auto;
    }
</style>