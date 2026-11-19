


<div>
    <button popovertarget="layout-header-right-content-streamer-shouts-dropdown-content">
        <svg width="24" height="24" viewBox="0 0 24 24" focusable="false" aria-hidden="true" role="presentation">
            <path fill-rule="evenodd" d="m13 17 9 5V2l-9 5H4a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h3v5h2v-5h4Zm7-11.601-6 3.333v6.536l6 3.333V5.399ZM4 9h8v6H4V9Z" clip-rule="evenodd"></path>
        </svg>
    </button>

    <dialog id="layout-header-right-content-streamer-shouts-dropdown-content" popover>
        <article>
            <h2>Streamer Shouts Dropdown Content</h2>
        </article>
    </dialog>
</div>


<style>
    button {
        anchor-name: --layout-header-right-content-streamer-shouts-dropdown-toggle;
    }

    dialog {
        position-anchor: --layout-header-right-content-streamer-shouts-dropdown-toggle;
        position: fixed;
        inset: unset;
        top: anchor(bottom);
        right: anchor(right);

        padding: 50px;
        border-color: black;
        border-width: 2px;
    }
</style>