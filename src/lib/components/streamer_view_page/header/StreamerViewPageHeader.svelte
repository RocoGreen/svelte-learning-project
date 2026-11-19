<script>
	import StreamerViewPageHeaderBottomContent from './bottom_content/StreamerViewPageHeaderBottomContent.svelte';
	import StreamerViewPageHeaderTopContent from './top_content/StreamerViewPageHeaderTopContent.svelte';
    import godot_icon from '$lib/assets/godot-icon.svg';
	import { resolve } from '$app/paths';
</script>


<header>
    <a href={resolve("/streamer_view")}>
        <img src={godot_icon} alt="Streamer Avatar" width="50" height="50"/>
    </a>
    
    <div id="streamer-view-page-header-top-and-bottom-content">
        <StreamerViewPageHeaderTopContent/>

        <StreamerViewPageHeaderBottomContent/>
    </div>
</header>


<style>
    header {
        display: flex;
        padding: 5px;
        column-gap: 10px;
    }

    #streamer-view-page-header-top-and-bottom-content {
        flex: auto;
    }
</style>