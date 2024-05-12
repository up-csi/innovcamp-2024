<script lang="ts">
    import './app.css';
    import { AppBar } from '@skeletonlabs/skeleton';
    import FacebookLogo from '../lib/facebook-logo.svelte';
    import InstagramLogo from '../lib/instagram-logo.svelte';
    import TiktokLogo from '../lib/tiktok-logo.svelte';
    import TwitterLogo from '../lib/twitter-logo.svelte';
</script>

<AppBar
    gridColumns="grid-cols-[auto_1fr_auto]"
    slotDefault="self-center justify-self-end text-center"
    slotTrail="place-content-end"
    background="bg-white/[0.8]"
    class="sticky top-0 z-[100] font-['Bebas_Neue'] text-xl drop-shadow-md"
>
    <div slot="lead"><a href="#top"><img src="box.svg" alt="Box Logo" class="size-12" /></a></div>
    <div class="grid grid-cols-4 gap-8">
        <a class="anchor" href="/">About Event</a>
        <a class="anchor" href="/">Speakers</a>
        <a class="anchor" href="#schedule">Schedule</a>
        <a class="anchor" href="/">About UP CSI</a>
    </div>
    <div slot="trail">
        <a href="https://forms.gle/NEBjJimhi5FFcRQs9" target="_blank"
            ><button
                type="button"
                class="variant-filled btn mx-4 rounded-lg bg-[#FF6534] text-xl text-white drop-shadow-sm"
                >Register Here</button
            ></a
        >
    </div>
</AppBar>

<slot />

<AppBar
    gridColumns="sm:grid-cols-3"
    slotDefault="self-center text-center"
    slotTrail="place-content-end"
    background="bg-[#323D42]"
    class="flex border-t-8 border-t-[#FF6534] text-white"
    border=""
>
    <div slot="lead" class="grid grid-cols-1 gap-4">
        <a class="anchor flex items-center gap-2" href="https://www.facebook.com/upcsi/" target="_blank">
            <FacebookLogo class="size-8"></FacebookLogo>
            @upcsi
        </a>
        <a class="anchor flex items-center gap-2" href="https://www.instagram.com/upcsicore/" target="_blank">
            <InstagramLogo class="size-8"></InstagramLogo>
            @upcsicore
        </a>
        <a class="anchor flex items-center gap-2" href="https://twitter.com/officialupcsi/" target="_blank">
            <TwitterLogo class="size-8"></TwitterLogo>
            @officialupcsi
        </a>
        <a class="anchor flex items-center gap-2" href="https://www.tiktok.com/@linotechtalk/" target="_blank">
            <TiktokLogo class="size-8"></TiktokLogo>
            @linotechtalk
        </a>
    </div>

    <div class="grid grid-cols-1 gap-4">
        <img src="UPCSI_Logo_White 1.svg" alt="UP CSI logo" class="size-32 justify-self-center" />
        <p class="font-bold">Learn. Create. Innovate.</p>
    </div>

    <div slot="trail" class="grid grid-cols-1 gap-4 text-right">
        <p>Alumni Engineers Centennial Hall, Velasquez Street, University of the Philippines Diliman, QC</p>
        <div><a class="anchor" href="https://up-csi.org/" target="_blank">https://up-csi.org/</a></div>
        <div><a class="anchor" href="mailto:lino@up-csi.org">lino@up-csi.org</a></div>
    </div>
</AppBar>

<slot />