<script lang="ts">
    import CSI from '$lib/assets/csi-logo.webp';
    import CSWEEK from '$lib/assets/cs-week-logo.webp';
    import DCS from '$lib/assets/dcs-logo.webp';
    import PARSER from '$lib/assets/parser-logo.webp';
    import bg_src from '$lib/assets/ic-svelte-surge-cover.webp';
    import logo_ic from '$lib/assets/ic-main-logo.webp';
</script>

<div class="relative bg-cover bg-center" style="background-image: url({bg_src})">
    <div class="flex h-auto flex-col items-center justify-center gap-10">
        <div class="grid-flow-cols grid auto-cols-min grid-cols-5 gap-2 py-10 md:gap-4">
            <!-- CSI LOGO -->
            <div class="col-span-1 flex items-center justify-center">
                <a href="https://up-csi.org/" target="_blank">
                    <img alt="CSI_logo" src={CSI} class="h-auto max-h-16" />
                </a>
            </div>

            <!-- PARSER LOGO -->
            <div class="col-span-1 flex items-center justify-center">
                <a href="https://www.facebook.com/upparser/" target="_blank">
                    <img alt="PARSER_logo" src={PARSER} class="h-auto max-h-12" />
                </a>
            </div>

            <!-- CSWEEK LOGO -->
            <div class="col-span-2 flex items-center justify-center">
                <a href="https://www.facebook.com/up.cs.week" target="_blank">
                    <img alt="CSWEEK_logo" src={CSWEEK} class="h-auto max-h-8" />
                </a>
            </div>

            <!-- DCS LOGO -->
            <div class="col-span-1 flex items-center justify-center">
                <a href="https://dcs.upd.edu.ph/" target="_blank">
                    <img alt="DCS_logo" src={DCS} class="h-auto max-h-12" />
                </a>
            </div>
        </div>

        <!-- SVELTE SURGE LOGO -->
        <div class="flex justify-items-center py-10">
            <img alt="svelte_surge_logo" src={logo_ic} class="h-44 sm:h-60 md:h-96" />
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
