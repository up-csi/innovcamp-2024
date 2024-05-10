<script lang="ts">
    import bg_src from "$lib/assets/ic-svelte-bg.jpg";
    import logo_ic from "$lib/assets/main-logo-ic.png"
    import CSI from '$lib/assets/CSILogo.png';
    import PARSER from '$lib/assets/PARSERLogo.png';
    import DCS from '$lib/assets/DCSLogo.png';
    import CSWEEK from '$lib/assets/CSWeekLogo.png';
</script>

<div class="relative bg-cover bg-center" style="background-image: url({bg_src})">
    <div class="h-auto flex flex-col items-center justify-center gap-10">
        <div class="py-10 grid grid-flow-cols grid-cols-5 auto-cols-min gap-2 md:gap-4">

            <!-- CSI LOGO -->
            <div class="col-span-1 flex items-center justify-center">
                <a href="https://up-csi.org/">
                    <img alt="CSI_logo" src={CSI} class="h-auto max-h-16"/>
                </a>
            </div>

            <!-- PARSER LOGO -->
            <div class="col-span-1 flex items-center justify-center">
                <a href="https://www.facebook.com/upparser/">
                    <img alt="PARSER_logo" src={PARSER} class="h-auto max-h-12"/>
                </a>
            </div>

            <!-- CSWEEK LOGO -->
            <div class="col-span-2 flex items-center justify-center">
                <a href="https://www.facebook.com/up.cs.week">
                    <img alt="CSWEEK_logo" src={CSWEEK} class="h-auto max-h-8"/>
                </a>
            </div>

            <!-- DCS LOGO -->
            <div class="col-span-1 flex items-center justify-center">
                <a href="https://dcs.upd.edu.ph/">
                    <img alt="DCS_logo" src={DCS} class="h-auto max-h-12"/>
                </a>
            </div>
        </div>

        <!-- SVELTE SURGE LOGO -->
        <div class="py-10">
            <img alt="svelte_surge_logo" src={logo_ic} class="h-44 sm:h-60 md:h-96 w-max"/>
        </div>

        <!-- SCHED, AECH VENUE DETAILS -->
        <div class="py-10">
            <p class="text-center text-xs sm:text-md md:text-xl text-white font-['Bebas_Neue'] font-regular tracking-[.30em]">
                MAY 15, 2024<br>
                6:00 PM - 9:00 PM<br>
                Accenture Room<br>
                ALUMNI ENGINEERS’ CENTENNIAL HALL
            </p>
        </div>
    </div>
</div>
