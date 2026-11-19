


<div>
    <button popovertarget="layout-header-right-content-amazon-luna-dropdown-content">
        <svg width="24" height="24" viewBox="0 0 24 24" focusable="false" aria-hidden="true" role="presentation">
            <path d="M19.8 14.4c-.24-.12-.48-.24-.6-.24h-.12c-.36-.12-1.92-.72-2.76-2.28l-1.56-2.64c-.6-1.08-.48-3-.48-3.6v-.48c0-1.56-1.2-2.76-2.76-2.76-1.56 0-2.76 1.2-2.76 2.76v.48c0 .48.12 2.4-.48 3.48L6 12.96l-.24.36v.12c-.24.36-.6.96-.96 1.44s-.84.84-1.32 1.2c0 0-.12 0-.12.12-.24.12-.48.36-.72.72-.48.96-.24 2.16.72 2.64.48.24 1.08.36 1.56.12.84-.24 1.8-.6 2.28-.72.72-.12 1.92-.12 2.64-.12h.72c3.48 0 5.16 1.44 5.16 1.44.12.12.24.24.48.36 1.68.96 3.96.36 4.92-1.32.96-1.8.36-3.96-1.32-4.92Zm-4.08 1.8c-.36.6-.84.96-1.68.96-.84.12-1.08.12-2.52.12-1.56 0-1.8 0-2.52-.12-.84-.12-1.32-.36-1.68-.96-.36-.6-.36-1.32 0-1.92.36-.6.48-1.2 1.2-2.16.6-1.08.84-1.44 1.44-2.28.36-.96.84-1.08 1.56-1.08.72 0 1.2.24 1.68.96.6.72.72.96 1.32 2.16.72 1.2.84 1.56 1.2 2.28.48.72.36 1.44 0 2.04Z"></path>
        </svg>
    </button>

    <dialog id="layout-header-right-content-amazon-luna-dropdown-content" popover>
        <article>
            <h2>Amazon Luna Dropdown Content</h2>
        </article>
    </dialog>
</div>


<style>
    button {
        anchor-name: --layout-header-right-content-amazon-luna-dropdown-toggle;
    }

    dialog {
        position-anchor: --layout-header-right-content-amazon-luna-dropdown-toggle;
        position: fixed;
        inset: unset;
        top: anchor(bottom);
        right: anchor(right);

        padding: 50px;
        border-color: black;
        border-width: 2px;
    }
</style>