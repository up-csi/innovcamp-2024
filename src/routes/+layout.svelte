<script lang="ts">
    import './app.css';
    import { AppBar } from '@skeletonlabs/skeleton';
    import FacebookLogo from "../lib/facebook-logo.svelte"
    import InstagramLogo from "../lib/instagram-logo.svelte"
    import TwitterLogo from "../lib/twitter-logo.svelte"
    import TiktokLogo from "../lib/tiktok-logo.svelte"
</script>

<slot />

<AppBar
    gridColumns="grid-cols-[auto_1fr_auto]"
    slotDefault="self-center justify-self-end text-center"
    slotTrail="place-content-end"
>
    <div slot="lead"><a href="/"><img src="box.svg" alt="Box Logo" class="size-16"></a></div>
    <div class="grid grid-cols-4 gap-8">
        <a class="anchor" href="/">About Event</a>
        <a class="anchor" href="/">Speakers</a>
        <a class="anchor" href="/">Schedule</a>
        <a class="anchor" href="/">About UP CSI</a>
    </div>
    <div slot="trail">
        <button type="button" class="variant-filled btn bg-black text-white">Register Here</button>
    </div>
</AppBar>

<AppBar
    gridColumns="grid-cols-3"
    slotDefault="self-center text-center"
    slotTrail="place-content-end"
    background="bg-[#323D42]"
    class="text-white"
>
    <div slot="lead" class="grid grid-cols-1 gap-4">
        <a class="anchor flex gap-2 items-center" href="https://www.facebook.com/upcsi/">
            <FacebookLogo class="size-8"></FacebookLogo>
            @upcsi
        </a>
        <a class="anchor flex gap-2 items-center" href="https://www.instagram.com/upcsicore/">
            <InstagramLogo class="size-8"></InstagramLogo>
            @upcsicore
        </a>
        <a class="anchor flex gap-2 items-center" href="https://twitter.com/officialupcsi/">
            <TwitterLogo class="size-8"></TwitterLogo>
            @officialupcsi
        </a>
        <a class="anchor flex gap-2 items-center" href="https://www.tiktok.com/@linotechtalk/"> 
            <TiktokLogo class="size-8"></TiktokLogo>
            @linotechtalk
        </a>
    </div>
    <div class="grid grid-cols-1 gap-4">
        <img src="UPCSI_Logo_White 1.svg" alt="UP CSI logo" class="justify-self-center size-32">
        <p class="font-bold">Learn. Create. Innovate.</p>
    </div>
    <div slot="trail" class="grid grid-cols-1 gap-8 text-right">
        <p>Alumni Engineers Centennial Hall, Velasquez Street, University of the Philippines Diliman, QC</p>
        <a class="anchor" href="https://up-csi.org/">https://up-csi.org/</a>
        <a class="anchor" href="mailto:lino@up-csi.org">lino@up-csi.org</a>
    </div>
</AppBar>