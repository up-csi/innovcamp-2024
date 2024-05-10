<script lang="ts">
    import bg_src from "$lib/assets/ic-svelte-bg.jpg";
    import logo_ic from "$lib/assets/main-logo-ic.png"
</script>


<div class="relative">
    <div class="h-screen flex items-center justify-center">
        <img alt="svelte_surge_logo" src={logo_ic} class="absolute h-44 w-max"/>
    </div>
    <img alt="svelte_surge_bg" src={bg_src} class="object-cover h-screen w-full -z-20"/>
    <div class="flex justify-center items-center h-full">
        <h1 class="text-4xl">Page</h1>
    </div>
</div>
