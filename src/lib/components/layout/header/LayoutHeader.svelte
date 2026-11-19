<script>
	import LayoutHeaderRightContent from './right_content/LayoutHeaderRightContent.svelte';
	import LayoutHeaderLeftContent from "./left_content/LayoutHeaderLeftContent.svelte";
	import LayoutHeaderSearch from "./search/LayoutHeaderSearch.svelte";

    
</script>


<header>
    <nav>
        <LayoutHeaderLeftContent/>

        <LayoutHeaderSearch/>

        <LayoutHeaderRightContent/>
    </nav>
</header>


<style>
    header {
        flex: none;
    }

    nav {
        display: flex;
        align-items: center;
        justify-content: space-between;

        padding: 10px;
    }
</style>