<script>
    import test_video from '$lib/assets/test_video.mp4';
    import StreamerViewPageHeader from '$lib/components/streamer_view_page/header/StreamerViewPageHeader.svelte';
</script>


<main>
    <video src={test_video} autoplay loop controls></video>

    <StreamerViewPageHeader/>
</main>


<style>
    main {
        overflow: auto;

        flex: auto;
        width: 100%;
    }

    video {
        width: 100%;
    }
</style>