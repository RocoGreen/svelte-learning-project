<script>
	import LayoutLeftNavigationStreamerViewersAlsoWatchSection from './streamer_viewers_also_watch/LayoutLeftNavigationStreamerViewersAlsoWatchSection.svelte';
	import LayoutLeftNavigationLiveChannelsSection from './live_channels_section/LayoutLeftNavigationLiveChannelsSection.svelte';
	import LayoutLeftNavigationFollowedChannelsSection from './followed_channels_section/LayoutLeftNavigationFollowedChannelsSection.svelte';

</script>


<aside>
    <nav>
        <h2>For You</h2>

        <div id="layout-left-navigation-sections-container">
            <LayoutLeftNavigationFollowedChannelsSection/>

            <LayoutLeftNavigationLiveChannelsSection/>

            <LayoutLeftNavigationStreamerViewersAlsoWatchSection/>
        </div>
    </nav>
</aside>


<style>
    aside {
        flex: none;
        overflow: scroll;

        width: 250px;
        background-color: #efeff1;
    }

    nav {
        padding: 10px;
    }

    h2 {
        margin-bottom: 25px;
    }

    #layout-left-navigation-sections-container {
        display: flex;
        flex-direction: column;
        row-gap: 25px;
    }
</style>