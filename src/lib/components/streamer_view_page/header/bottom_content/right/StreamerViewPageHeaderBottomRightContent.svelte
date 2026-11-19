<script>
	
</script>


<div id="streamer-view-page-header-bottom-right-content">
    <div id="streamer-view-page-header-stream-viewer-count-and-uptime">
        <div id="streamer-view-page-header-stream-viewer-count-with-icon">
            <svg width="24" height="24" viewBox="0 0 24 24" aria-hidden="true">
                <path fill-rule="evenodd" d="M6 8a6 6 0 1 1 7.025 5.913l.012.036A3 3 0 0 0 15.883 16H17a4 4 0 0 1 4 4v2h-2v-2a2 2 0 0 0-2-2h-1.117A5 5 0 0 1 12 16.15 5 5 0 0 1 8.117 18H7a2 2 0 0 0-2 2v2H3v-2a4 4 0 0 1 4-4h1.117a3 3 0 0 0 2.846-2.051l.012-.036A6.002 6.002 0 0 1 6 8Zm6 4a4 4 0 1 1 0-8 4 4 0 0 1 0 8Z" clip-rule="evenodd"></path>
            </svg>

            <span>000</span>
        </div>
        
        <p>
            <time>00:00:00</time>
        </p>
    </div>

    <menu id="streamer-view-page-header-secondary-user-actions">
        <button>
            <svg width="24" height="24" viewBox="0 0 24 24" focusable="false" aria-hidden="true" role="presentation">
                <path d="M13 6v10h-2V6L9.5 7.5 8 6l4-4 4 4-1.5 1.5L13 6Z"></path>
                <path d="M6 8h3v2H6v10h12V10h-3V8h3a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V10a2 2 0 0 1 2-2Z"></path>
            </svg>
        </button>

        <button>
            <svg width="24" height="24" viewBox="0 0 24 24" focusable="false" aria-hidden="true" role="presentation">
                <path d="M10 5a2 2 0 1 1 4 0 2 2 0 0 1-4 0Zm0 7a2 2 0 1 1 4 0 2 2 0 0 1-4 0Zm2 5a2 2 0 1 0 0 4 2 2 0 0 0 0-4Z"></path>
            </svg>
        </button>
    </menu>
    
</div>


<style>
    #streamer-view-page-header-bottom-right-content,
    #streamer-view-page-header-stream-viewer-count-and-uptime,
    #streamer-view-page-header-stream-viewer-count-with-icon,
    #streamer-view-page-header-secondary-user-actions {
        display: flex;
    }

    #streamer-view-page-header-stream-viewer-count-and-uptime,
    #streamer-view-page-header-stream-viewer-count-with-icon,
    #streamer-view-page-header-secondary-user-actions {
        align-items: center;
    }

    #streamer-view-page-header-bottom-right-content {
        flex-direction: column;
        column-gap: 10px;
    }

    #streamer-view-page-header-stream-viewer-count-and-uptime {
        column-gap: 5px;
    }

    #streamer-view-page-header-secondary-user-actions {
        align-self: flex-end;
        column-gap: 5px;
    }
</style>