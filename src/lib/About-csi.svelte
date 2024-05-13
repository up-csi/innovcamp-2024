<script>
    import CSI from '$lib/assets/CSILogo.png';
    import Git_Workshop from '$lib/assets/git-workshop-pic.jpg';
</script>

<div
    class="flex flex-col items-center gap-10 border-t-8 border-t-[#FF6534] bg-[#323D42] px-8 pb-16 pt-8 md:px-24 lg:grid lg:grid-cols-3 lg:grid-rows-3"
>
    <div class="flex gap-10 justify-self-center lg:col-span-2 lg:row-span-1 lg:justify-self-start">
        <a href="https://up-csi.org/" target="_blank">
            <img alt="CSI_logo" src={CSI} class="h-24 sm:h-32 lg:h-48" />
        </a>
        <h1 class="h1 h-fit pt-4 font-['Bebas_Neue'] text-white sm:text-5xl lg:text-7xl">
            ABOUT THE <br /> ORGANIZATION
        </h1>
    </div>

    <div class="justify-self-center px-10 lg:col-span-1 lg:row-span-3">
        <img alt="Git Workshop" src={Git_Workshop} class="mx-10 w-64 max-w-sm rounded-2xl sm:w-max" />
    </div>

    <div class="text-md flex flex-col gap-10 text-white lg:col-span-2 lg:row-span-2 lg:mx-12 lg:pb-20 lg:text-xl">
        <p>
            UP Center for Student Innovations (UP CSI) is a service-oriented organization aimed towards the enhancement
            of student learning from the University of the Philippines Diliman, Department of Computer Science by
            working with real-world projects.
        </p>
        <p>
            Our mission is to provide Computer Science students with opportunities to improve their software engineering
            abilities and innovative thinking by working on real-world projects and clients.
        </p>
    </div>
</div>

<style>
    h1 {
        text-shadow: 1.5px 1.5px 0px #ff6534;
    }
</style>
