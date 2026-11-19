<script>
    import { resolve } from '$app/paths';
    import godot_icon from '$lib/assets/godot-icon.svg';
</script>


<div>
    <a href={resolve("/")}><img src={godot_icon} alt="Twitch Logo" width="35" height="35"></a>

    <p><a href={resolve("/following")}>Following</a></p>

    <p><a href={resolve("/browse")}>Browse</a></p>

    <button>
        <svg width="24" height="24" viewBox="0 0 24 24" focusable="false" aria-hidden="true" role="presentation">
            <path d="M10 5a2 2 0 1 1 4 0 2 2 0 0 1-4 0Zm0 7a2 2 0 1 1 4 0 2 2 0 0 1-4 0Zm2 5a2 2 0 1 0 0 4 2 2 0 0 0 0-4Z"></path>
        </svg>
    </button>
</div>


<style>
    div {
        display: flex;
        align-items: center;
        column-gap: 15px;
    }
</style>