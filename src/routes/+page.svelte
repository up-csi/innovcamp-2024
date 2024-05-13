<script lang="ts">
    import About from '$lib/about-event.svelte';
    import AboutCsi from '$lib/About-csi.svelte';
    import Hero from '$lib/Hero.svelte';
    import Program from '$lib/program.svelte';
    import Speaker from '$lib/Speaker.svelte';
</script>

<div class="flex flex-col overflow-hidden">
    <div class="">
        <Hero />
    </div>

    <div class="" id="about">
        <About />
    </div>

    <div class="" id="schedule">
        <Program />
    </div>

    <div class="" id="speakers">
        <Speaker />
    </div>

    <div class="" id="about-csi">
        <AboutCsi />
    </div>
</div>
