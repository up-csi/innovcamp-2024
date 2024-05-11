<script lang="ts">
    import Hero from '$lib/Hero.svelte';
    import Program from "$lib/program.svelte"
</script>

<div class="flex flex-col">
    <div class="h-height">
        <Hero />
    </div>

    <div class="h-10/12">
        <Program />
    </div>
</div>