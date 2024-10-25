<script lang="ts">
    import About from '$lib/about-event.svelte';
    import AboutCsi from '$lib/About-csi.svelte';
    import Gallery from '$lib/Gallery.svelte';
    import Hero from '$lib/Hero.svelte';
    import Program from '$lib/program.svelte';
    import Speaker from '$lib/Speaker.svelte';
</script>

<div class="flex flex-col overflow-hidden">
    <div>
        <Hero />
    </div>

    <div id="about">
        <About />
    </div>

    <div id="schedule">
        <Program />
    </div>

    <div id="speakers">
        <Speaker />
    </div>

    <div id="gallery">
        <Gallery />
    </div>

    <div id="about-csi">
        <AboutCsi />
    </div>
</div>
