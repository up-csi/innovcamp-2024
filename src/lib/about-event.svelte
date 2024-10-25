<script lang="ts">
    import Box from './box.svelte';
    import SvelteIcon from './svelte-icon.svelte';

    const box_size = '80px';

    const svelte_size = '70px';
</script>

<div class="w-full border-t-8 border-t-[#FF6534] bg-[#323d42] pb-1">
    <div class="flex justify-center pt-8">
        <div class="place-content-center justify-self-center">
            <Box height={box_size} width={box_size} />
        </div>
        <h1
            class="w-2/3 place-content-center text-center font-['Bebas_Neue'] text-5xl text-white md:ml-4 md:w-fit md:text-6xl lg:text-7xl 2xl:w-fit 2xl:text-8xl"
        >
            Innov Camp 2024
        </h1>
    </div>

    <div class="mt-4 grid-cols-5 items-center justify-center gap-x-10 lg:ml-10 lg:mt-8 lg:grid 2xl:mt-3">
        <div class="grid lg:col-span-3">
            <p
                class="inter text-m w-fit px-8 py-4 text-center text-white md:text-lg lg:ml-12 lg:w-5/6 lg:text-2xl 2xl:ml-0 2xl:mt-3 2xl:w-fit"
            >
                This year's InnovCamp coincides with the esteemed Department of Computer Science CS Week, primed to
                ignite the spirit of innovation and technological prowess. Geared towards those with a keen interest in
                Web Development, this event offers an immersive experience tailored to inspire, educate, and propel
                participants toward pioneering endeavors in the digital realm.
            </p>
            <img
                src="/ic-grp-pic.PNG"
                alt="Innov Camp 2023 Group Pic"
                class="mb-8 mt-4 w-80 justify-self-center md:w-3/4 lg:h-max lg:w-3/4 2xl:h-4/5"
            />
        </div>

        <div class="col-span-2 mx-8 mb-10 rounded-[25px] bg-[#d9d9d9] p-7 lg:mb-20 lg:ml-0 lg:mr-16 2xl:p-12">
            <div class="col-span-2 mb-4 flex flex-wrap justify-center 2xl:mb-8">
                <h2
                    class="w-1/2 place-content-center text-center font-['Bebas_Neue'] text-4xl text-[#FF6534] md:text-5xl 2xl:text-6xl"
                >
                    What is Svelte?
                </h2>
                <div class="align-center ml-3 place-self-center 2xl:ml-6">
                    <SvelteIcon height={svelte_size} width={svelte_size} />
                </div>
            </div>

            <p class="col-span-2 row-span-1 mx-2 mb-5 text-center text-sm md:text-lg 2xl:text-2xl">
                More and more companies and websites are adopting a fresher new framework: Svelte!
            </p>
            <p class="inter col-span-2 row-span-2 mx-2 text-center text-sm md:text-lg 2xl:text-2xl">
                Svelte offers a simple, modular approach to front-end development, with quick performance, a
                runtime-less concept, a component-based model that allows rapid testing, and bandwidth efficiency true
                to its name.
            </p>
        </div>
    </div>
</div>

<style>
    h1 {
        text-shadow: 1.5px 1.5px 0px #ff6534;
    }

    h2 {
        text-shadow: 1.5px 1.5px 0px #ffffff;
    }
</style>
