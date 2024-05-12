<script lang="ts">
    import Hero from '$lib/Hero.svelte';
    import Program from '$lib/program.svelte';
    import Speaker from '$lib/Speaker.svelte';
    import AboutCsi from '$lib/About-csi.svelte';
</script>

<div class="flex flex-col">
    <div class="">
        <Hero />
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
