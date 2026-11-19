<script>
	import LayoutHeaderRightContentMoreLinksDropdown from './dropdowns/more_links/LayoutHeaderRightContentMoreLinksDropdown.svelte';
	import LayoutHeaderRightContentBuyTurboDropdown from './dropdowns/buy_turbo/LayoutHeaderRightContentBuyTurboDropdown.svelte';
	import LayoutHeaderRightContentStreamerShoutsDropdown from './dropdowns/streamer_shouts/LayoutHeaderRightContentStreamerShoutsDropdown.svelte';
	import LayoutHeaderRightContentWhispersDropdown from './dropdowns/whispers/LayoutHeaderRightContentWhispersDropdown.svelte';
	import LayoutHeaderRightContentNotificationsDropdown from './dropdowns/notifications/LayoutHeaderRightContentNotificationsDropdown.svelte';
	import LayoutHeaderRightContentAmazonLunaDropdown from './dropdowns/amazon_luna/LayoutHeaderRightContentAmazonLunaDropdown.svelte';

</script>


<div>
    <LayoutHeaderRightContentAmazonLunaDropdown/>

    <LayoutHeaderRightContentNotificationsDropdown/>

    <LayoutHeaderRightContentWhispersDropdown/>

    <LayoutHeaderRightContentStreamerShoutsDropdown/>

    <LayoutHeaderRightContentBuyTurboDropdown/>

    <LayoutHeaderRightContentMoreLinksDropdown/>
</div>


<style>
    div {
        display: flex;
        align-items: center;
        column-gap: 10px;
    }
</style>