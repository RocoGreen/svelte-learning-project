


<div>
    <button popovertarget="layout-header-right-content-buy-turbo-dropdown-content">
        <svg width="24" height="24" viewBox="0 0 24 24" aria-hidden="true">
            <path d="m13 8-5.349 3.12a.5.5 0 0 0-.048.832L9 13l-1 3 5.35-3.12a.5.5 0 0 0 .047-.832L12 11l1-3Z"></path>
            <path fill-rule="evenodd" d="M2 19V5h17v3h3v8h-3v3H2ZM17 7v3h3v4h-3v3H4V7h13Z" clip-rule="evenodd"></path>
        </svg>

        <span>Try One-Month Ad-Free</span>
    </button>

    <dialog id="layout-header-right-content-buy-turbo-dropdown-content" popover>
        <article>
            <h2>Buy Turbo Dropdown Content</h2>
        </article>
    </dialog>
</div>


<style>
    button {
        anchor-name: --layout-header-right-content-buy-turbo-dropdown-toggle;

        display: flex;
        align-items: center;
        column-gap: 5px;

        padding: 5px;
    }

    dialog {
        position-anchor: --layout-header-right-content-buy-turbo-dropdown-toggle;
        position: fixed;
        inset: unset;
        top: anchor(bottom);
        right: anchor(right);

        padding: 50px;
        border-color: black;
        border-width: 2px;
    }
</style>