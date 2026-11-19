<script lang="ts">
	import LayoutLeftNavigation from './../lib/components/layout/left_navigation/LayoutLeftNavigation.svelte';
	import LayoutHeader from './../lib/components/layout/header/LayoutHeader.svelte';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>


<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>


<div id="layout">
	<LayoutHeader/>

	<div id="layout-left-navigation-and-current-page">
		<LayoutLeftNavigation/>

		{@render children()}
	</div>
</div>


<style>
	:global(html, body) {
		height: 100%;
	}

	:global(body) {
		margin: 0;
	}

	:global(img, svg, path) {
		display: block;
	}

	:global(h1, h2, h3, h4) {
		margin: 0;
	}

	:global(p) {
		margin: 0;
	}

	:global(ol, ul, menu) {
		margin: 0;
		padding: 0;
		list-style: none;
	}

	#layout {
		display: flex;
		flex-direction: column;
		height: 100%;
		min-height: 0;
	}

	#layout-left-navigation-and-current-page {
		display: flex;
		height: 100%;
		min-height: 0;
	}
</style>