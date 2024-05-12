<script lang="ts">
    import Box from './box.svelte';
    import SvelteIcon from './svelte-icon.svelte';
</script>

<div class="bg-[#323d42]">
    <div class="flex justify-center pt-8">
        <div class="h-100 w-100 mr-5 justify-self-center">
            <Box height="100px" width="100px" />
        </div>
        <h1 class="max-w-1/4 place-content-center text-center font-['Bebas_Neue'] text-8xl text-white">
            Innov Camp 2024
        </h1>
    </div>

    <div class="mx-20 mt-12 grid grid-cols-5 items-center justify-center gap-x-10">
        <div class="col-span-3 grid">
            <p class="mb-12 px-8 py-4 text-center text-3xl text-white">
                This year's InnovCamp coincides with the esteemed Department of Computer Science CS Week, primed to
                ignite the spirit of innovation and technological prowess. Geared towards those with a keen interest in
                Web Development, this event offers an immersive experience tailored to inspire, educate, and propel
                participants toward pioneering endeavors in the digital realm.
            </p>
            <img src="/ic-grp-pic.PNG" alt="Innov Camp 2023 Group Pic" class="h-4/5 w-max justify-self-center" />
        </div>

        <div class="col-span-2 mx-8 mb-10 rounded-[25px] bg-[#d9d9d9] p-12">
            <div class="col-span-2 mb-8 flex flex-wrap justify-center">
                <h2 class="w-1/2 place-content-center text-center font-['Bebas_Neue'] text-5xl text-[#FF6534]">
                    What is Svelte?
                </h2>
                <div class="align-center ml-6 place-self-center">
                    <SvelteIcon height="90px" width="90px" />
                </div>
            </div>

            <p class="col-span-2 row-span-1 mx-10 mb-5 text-center text-2xl">
                More and more companies and websites are adopting a fresher new framework: Svelte!
            </p>
            <p class="col-span-2 row-span-2 mx-8 text-center text-2xl">
                Svelte offers a simple, modular approach to front-end development, with quick performance, a
                runtime-less concept, a component-based model that allows rapid testing, and bandwidth efficiency true
                to its name.
            </p>
        </div>
    </div>
</div>
