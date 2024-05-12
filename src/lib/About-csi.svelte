<script>
    import CSI from '$lib/assets/CSILogo.png';
    import Git_Workshop from '$lib/assets/git-workshop-pic.jpg'
</script>

<div class="flex flex-col gap-10 lg:grid lg:grid-rows-3 lg:grid-cols-3 bg-[#323D42] items-center px-8 py-24 md:px-24">
    <div class="flex lg:row-span-1 lg:col-span-2 gap-10 justify-self-center lg:justify-self-start">
        <a href="https://up-csi.org/" target="_blank">
            <img alt="CSI_logo" src={CSI} class="h-32 lg:h-48" />
        </a>
        <h1 class="text-5xl lg:text-8xl pt-4 font-['Bebas_Neue'] text-white">ABOUT THE <br> ORGANIZATION</h1>
    </div>

    <div class="lg:row-span-3 lg:col-span-1 justify-self-center px-10">
        <img alt="Git Workshop" src={Git_Workshop} class="rounded-2xl mx-10 max-w-sm"/>
    </div>

    <div class="flex flex-col gap-10 lg:row-span-2 lg:col-span-2 text-white text-md lg:text-xl lg:mx-12 lg:pb-20">
        <p>
            UP Center for Student Innovations (UP CSI) is a service-oriented organization aimed towards the enhancement of 
            student learning from the University of the Philippines Diliman, Department of Computer Science by working with 
            real-world projects.
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