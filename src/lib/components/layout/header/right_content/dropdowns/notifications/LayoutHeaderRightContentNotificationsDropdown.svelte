


<div>
    <button popovertarget="layout-header-right-content-notifications-dropdown-content">
        <svg width="24" height="24" viewBox="0 0 24 24" focusable="false" aria-hidden="true" role="presentation">
            <path fill-rule="evenodd" d="M5 3h14l3 6v12H2V9l3-6Zm-.264 5 1.5-3h11.528l1.5 3H15v3a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V8H4.736ZM4 10v9h16v-9h-3v1a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-1H4Z" clip-rule="evenodd"></path>
        </svg>
    </button>

    <dialog id="layout-header-right-content-notifications-dropdown-content" popover>
        <article>
            <h2>Notifications Dropdown Content</h2>
        </article>
    </dialog>
</div>


<style>
    button {
        anchor-name: --layout-header-right-content-notifications-dropdown-toggle;
    }

    dialog {
        position-anchor: --layout-header-right-content-notifications-dropdown-toggle;
        position: fixed;
        inset: unset;
        top: anchor(bottom);
        right: anchor(right);

        padding: 50px;
        border-color: black;
        border-width: 2px;
    }
</style>