<script lang="ts">
    import { AppBar } from '@skeletonlabs/skeleton';
</script>

<slot />

<AppBar
    gridColumns="grid-cols-[auto_1fr_auto]"
    slotDefault="self-center justify-self-end text-center"
    slotTrail="place-content-end"
>
    <div slot="lead">(CUBE)</div>
    <div class="grid grid-cols-4 gap-8">
        <a class="anchor" href="/">About Event</a>
        <a class="anchor" href="/">Speakers</a>
        <a class="anchor" href="/">Schedule</a>
        <a class="anchor" href="/">About UP CSI</a>
    </div>
    <div slot="trail">
        <button type="button" class="variant-filled btn bg-black text-white">Button</button>
    </div>
</AppBar>
