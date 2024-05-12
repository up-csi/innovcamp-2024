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
    class="sm:text-md sticky top-0 z-[100] font-['Bebas_Neue'] text-sm drop-shadow-md md:text-lg"
>
    <div slot="lead" class="">
        <a href="#top">
            <img src="box.svg" alt="Box Logo" class="size-12" />
        </a>
    </div>
    <div class="hidden grid-cols-4 gap-8 sm:grid">
        <a class="anchor no-underline hover:underline" href="#about">About Event</a>
        <a class="anchor no-underline hover:underline" href="#speakers">Speakers</a>
        <a class="anchor no-underline hover:underline" href="#schedule">Schedule</a>
        <a class="anchor no-underline hover:underline" href="#about-csi">About UP CSI</a>
    </div>
    <div slot="trail">
        <a href="https://forms.gle/NEBjJimhi5FFcRQs9" target="_blank"
            ><button
                type="button"
                class="variant-filled btn ml-4 rounded-lg bg-[#FF6534] text-xl text-white drop-shadow-sm"
                >Register Here</button
            ></a
        >
    </div>
</AppBar>

<slot />

<div
    class="grid grid-cols-1 justify-items-center gap-6 border-t-8 border-t-[#FF6534] bg-[#323D42] p-4 text-white sm:grid-cols-3 sm:justify-items-stretch sm:gap-0"
>
    <div class="order-1 grid grid-cols-1 gap-4 self-center text-center">
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

    <div class="order-0 grid grid-cols-1 gap-4 self-center text-center sm:order-2">
        <img src="UPCSI_Logo_White 1.svg" alt="UP CSI logo" class="size-32 justify-self-center" />
        <p class="font-bold">Learn. Create. Innovate.</p>
    </div>

    <div class="order-3 grid grid-cols-1 place-content-end gap-4 self-center text-center sm:text-right">
        <div><a class="anchor" href="https://up-csi.org/" target="_blank">https://up-csi.org/</a></div>
        <div><a class="anchor" href="mailto:lino@up-csi.org">lino@up-csi.org</a></div>
        <p>Alumni Engineers Centennial Hall, Velasquez Street, University of the Philippines Diliman, QC</p>
    </div>
</div>
