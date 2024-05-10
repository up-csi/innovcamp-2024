<script lang="ts">
    import bg_src from "$lib/assets/ic-svelte-bg.jpg";
    import logo_ic from "$lib/assets/main-logo-ic.png"
    import cs_logos from "$lib/assets/ic-cs-Logos.png"
</script>


<div class="relative">
    <div class="h-screen flex items-center justify-center">
        <img alt="svelte_surge_logo" src={cs_logos} class="absolute h-8 sm:h-10 md:h-20 w-max top-10"/>
        <img alt="svelte_surge_logo" src={logo_ic} class="absolute h-44 sm:h-60 md:h-96 w-max"/>
        <p class="absolute bottom-20 text-center text-xs sm:text-md md:text-xl text-white font-['Bebas_Neue'] font-regular tracking-[.30em]">
            MAY 15, 2024<br>
            6:00 PM - 9:00 PM<br>
            Accenture Room<br>
            ALUMNI ENGINEERS’ CENTENNIAL HALL<br>
        </p>
        <img alt="svelte_surge_bg" src={bg_src} class="absolute object-cover h-screen w-full -z-20"/>
    </div>
    
    <div class="flex justify-center items-center h-full">
        <h1 class="text-4xl">Page</h1>
    </div>
</div>
