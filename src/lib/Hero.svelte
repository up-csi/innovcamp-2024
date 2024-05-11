<script lang="ts">
    import CSI from '$lib/assets/CSILogo.png';
    import CSWEEK from '$lib/assets/CSWeekLogo.png';
    import DCS from '$lib/assets/DCSLogo.png';
    import PARSER from '$lib/assets/PARSERLogo.png';
    import bg_src from '$lib/assets/ic-svelte-bg.jpg';
    import logo_ic from '$lib/assets/main-logo-ic.png';
</script>

<div class="relative bg-cover bg-center" style="background-image: url({bg_src})">
    <div class="flex h-auto flex-col items-center justify-center gap-10">
        <div class="grid-flow-cols grid auto-cols-min grid-cols-5 gap-2 py-10 md:gap-4">
            <!-- CSI LOGO -->
            <div class="col-span-1 flex items-center justify-center">
                <a href="https://up-csi.org/">
                    <img alt="CSI_logo" src={CSI} class="h-auto max-h-16" />
                </a>
            </div>

            <!-- PARSER LOGO -->
            <div class="col-span-1 flex items-center justify-center">
                <a href="https://www.facebook.com/upparser/">
                    <img alt="PARSER_logo" src={PARSER} class="h-auto max-h-12" />
                </a>
            </div>

            <!-- CSWEEK LOGO -->
            <div class="col-span-2 flex items-center justify-center">
                <a href="https://www.facebook.com/up.cs.week">
                    <img alt="CSWEEK_logo" src={CSWEEK} class="h-auto max-h-8" />
                </a>
            </div>

            <!-- DCS LOGO -->
            <div class="col-span-1 flex items-center justify-center">
                <a href="https://dcs.upd.edu.ph/">
                    <img alt="DCS_logo" src={DCS} class="h-auto max-h-12" />
                </a>
            </div>
        </div>

        <!-- SVELTE SURGE LOGO -->
        <div class="py-10 grid justify-items-center">
            <img alt="svelte_surge_logo" src={logo_ic} class="h-44 w-max sm:h-60 md:h-96" />
        </div>

        <!-- SCHED, AECH VENUE DETAILS -->
        <div class="py-10">
            <p
                class="sm:text-md font-regular text-center font-['Bebas_Neue'] text-xs tracking-[.30em] text-white md:text-xl"
            >
                MAY 15, 2024<br />
                6:00 PM - 9:00 PM<br />
                Accenture Room<br />
                ALUMNI ENGINEERS’ CENTENNIAL HALL
            </p>
        </div>
    </div>
</div>
