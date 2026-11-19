<script>
	import godot_icon from '$lib/assets/godot-icon.svg';
	import { resolve } from '$app/paths';
</script>


<a href={resolve("/streamer_view")}>
    <article class="layout-left-navigation-streamer-card">
        <img 
            class="layout-left-navigation-streamer-card-avatar" 
            src={godot_icon} 
            alt="Streamer Avatar" 
            width="35" 
            height="35"
        />

        <div class="layout-left-navigation-streamer-card-display-name-and-activity">
            <h4>Streamer Name</h4>
            <p>Streamer Activity</p>
        </div>

        <div class="layout-left-navigation-streamer-card-live-indicator-and-viewers-count">
            <div class="layout-left-navigation-streamer-card-live-indicator"></div>
            <p>000</p>
        </div>
    </article>
</a>


<style>
    .layout-left-navigation-streamer-card {
        display: flex;
        align-items: center;
    }

    .layout-left-navigation-streamer-card-avatar {
        margin-right: 5px;

        border-radius: 100px;
    }

    .layout-left-navigation-streamer-card-display-name-and-activity {
        margin-right: auto;
    }

    .layout-left-navigation-streamer-card-live-indicator-and-viewers-count {
        align-self: flex-start;

        display: flex;
        align-items: center;
        column-gap: 2px;
    }

    .layout-left-navigation-streamer-card-live-indicator {
        width: 10px;
        height: 10px;
        border-radius: 100px;
        background-color: red;
    }
</style>