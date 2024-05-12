<script lang="ts">
    import About from '$lib/about-event.svelte';
    import Hero from '$lib/Hero.svelte';
    import Program from '$lib/program.svelte';
    import Speaker from '$lib/Speaker.svelte';
</script>

<div class="flex flex-col">
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
</div>
