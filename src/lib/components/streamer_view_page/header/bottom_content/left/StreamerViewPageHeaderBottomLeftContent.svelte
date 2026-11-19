<script>
	import { resolve } from "$app/paths";

	
</script>


<div id="streamer-view-page-header-bottom-left-content">
    <p id="streamer-view-page-header-stream-description">
        Stream Description
    </p>

    <div id="streamer-view-page-header-stream-activity-name-and-tags">
        <p id="streamer-view-page-header-stream-activity-name">
            <a href={resolve("/streamer_view")}>Stream Activity Name</a>
        </p>

        <ul id="streamer-view-page-header-stream-tags">
            {#each { length : 5 }}
                <li>
                    <a href={resolve("/streamer_view")}>Stream Tag</a>
                </li>
            {/each}
        </ul>
    </div>
</div>


<style>
    #streamer-view-page-header-stream-activity-name-and-tags,
    #streamer-view-page-header-stream-tags {
        display: flex;
        align-items: center;
    }

    #streamer-view-page-header-stream-activity-name-and-tags {
        flex-wrap: wrap;
        column-gap: 10px;
    }

    #streamer-view-page-header-stream-tags {
        column-gap: 5px;
    }
</style>