<script>
	import StreamerViewPageHeaderBottomRightContent from './right/StreamerViewPageHeaderBottomRightContent.svelte';
	import StreamerViewPageHeaderBottomLeftContent from './left/StreamerViewPageHeaderBottomLeftContent.svelte';
	
</script>


<div id="streamer-view-page-header-bottom-content">
    <StreamerViewPageHeaderBottomLeftContent/>

    <StreamerViewPageHeaderBottomRightContent/>
</div>


<style>
    #streamer-view-page-header-bottom-content {
        display: flex;
        justify-content: space-between;
    }
</style>