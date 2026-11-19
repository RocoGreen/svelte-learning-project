


<div>
    <button popovertarget="layout-header-right-content-whispers-dropdown-content">
        <svg width="24" height="24" viewBox="0 0 24 24" focusable="false" aria-hidden="true" role="presentation">
            <path fill-rule="evenodd" d="M9.828 17 12 19.172 14.172 17H19V5H5v12h4.828ZM12 22l-3-3H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2h-4l-3 3Z" clip-rule="evenodd"></path>
        </svg>
    </button>

    <dialog id="layout-header-right-content-whispers-dropdown-content" popover>
        <article>
            <h2>Whispers Dropdown Content</h2>
        </article>
    </dialog>
</div>


<style>
    button {
        anchor-name: --layout-header-right-content-whispers-dropdown-toggle;
    }

    dialog {
        position-anchor: --layout-header-right-content-whispers-dropdown-toggle;
        position: fixed;
        inset: unset;
        top: anchor(bottom);
        right: anchor(right);

        padding: 50px;
        border-color: black;
        border-width: 2px;
    }
</style>