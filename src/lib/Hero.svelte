<script lang="ts">
    import bg_src from "$lib/assets/ic-svelte-bg.jpg";
    import logo_ic from "$lib/assets/main-logo-ic.png"
    // import cs_logos from "$lib/assets/ic-cs-Logos.png"
    import CSI from '$lib/assets/CSILogo.png';
    import PARSER from '$lib/assets/PARSERLogo.png';
    import DCS from '$lib/assets/DCSLogo.png';
    import CSWEEK from '$lib/assets/CSWeekLogo.png';
</script>

<div class="relative bg-cover bg-center" style="background-image: url({bg_src})">
    <div class="h-auto flex flex-col items-center justify-center gap-10">
        <div class="py-10 grid grid-flow-cols grid-cols-4 auto-cols-min">
            <!-- <img alt="svelte_surge_logo" src={cs_logos} class="h-8 sm:h-10 md:h-20 w-max top-10"/> -->
            <div>
                <img alt="CSI_logo" src={CSI} class="h-16"/>
            </div>
            <div>
                <img alt="PARSER_logo" src={PARSER} class="h-12"/>
            </div>
            <div>
                <img alt="CSWEEK_logo" src={CSWEEK} class="h-8"/>
            </div>
            <div>
                <img alt="DCS_logo" src={DCS} class="h-12"/>
            </div>
        </div>
        <div class="py-10">
            <img alt="svelte_surge_logo" src={logo_ic} class="h-44 sm:h-60 md:h-96 w-max"/>
        </div>
        <div class="py-10">
            <p class="text-center text-xs sm:text-md md:text-xl text-white font-['Bebas_Neue'] font-regular tracking-[.30em]">
                MAY 15, 2024<br>
                6:00 PM - 9:00 PM<br>
                Accenture Room<br>
                ALUMNI ENGINEERS’ CENTENNIAL HALL
            </p>
        </div>
        <!-- <img alt="svelte_surge_bg" src={bg_src} class="absolute object-cover h-auto w-full -z-20"/> -->
    </div>
</div>
