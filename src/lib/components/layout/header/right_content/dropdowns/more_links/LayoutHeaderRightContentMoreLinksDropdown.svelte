<script>
	import godot_icon from '$lib/assets/godot-icon.svg';
</script>


<div>
    <button popovertarget="layout-header-right-content-more-links-dropdown-content">
        <img src={godot_icon} alt="User Avatar" width="50" height="50"/>
    </button>

    <dialog id="layout-header-right-content-more-links-dropdown-content" popover>
        <article>
            <h2>More Links Dropdown Content</h2>
        </article>
    </dialog>
</div>


<style>
    button {
        anchor-name: --layout-header-right-content-more-links-dropdown-toggle;
    }

    img {
        border-radius: 100px;
    }

    dialog {
        position-anchor: --layout-header-right-content-more-links-dropdown-toggle;
        position: fixed;
        inset: unset;
        top: anchor(bottom);
        right: anchor(right);

        padding: 50px;
        border-color: black;
        border-width: 2px;
    }
</style>