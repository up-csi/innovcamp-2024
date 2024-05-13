<script>
    import { Avatar } from '@skeletonlabs/skeleton';
    import Basti from '$lib/assets/basti-ortiz.jpeg';
    import DevToLogo from './dev-to-logo.svelte';
    import GithubIcon from './github-logo.svelte';
    import Lightning from './lightning.svelte';
    import LinkedinIcon from './linkedin-logo.svelte';
</script>

<div
    class="grid justify-items-center gap-0 border-t-8 border-t-[#FF6534] bg-[#323D42] py-8 text-center text-sm sm:text-base md:gap-4"
>
    <h1 class="h1 h-fit text-center font-['Bebas_Neue'] text-5xl text-white lg:text-6xl">MEET THE SPEAKER</h1>

    <div
        class="speaker my-4 flex w-11/12 max-w-[60rem] cursor-pointer flex-col items-center gap-10 rounded-3xl bg-[#D9D9D9] p-10 shadow-none transition duration-500 hover:scale-105 hover:cursor-default hover:shadow-xl hover:shadow-gray-900 md:w-10/12 md:flex-row"
    >
        <div class="flex flex-auto flex-col items-center justify-center md:w-72">
            <Avatar class="mb-5 w-48 lg:w-64" src={Basti} width="w-32" rounded="rounded-full" />

            <div class="flex flex-col items-center gap-2 text-center font-['Bebas_Neue'] text-2xl">
                <h2>Sebastian Luis Ortiz</h2>
                <h3 class="text-wrap text-[#FF6534]">UP CSI Director for Engineering</h3>
                <hr class="w-48" />
            </div>
        </div>

        <div class="w-54 inter flex-auto text-left md:w-72">
            <ul class="list-disc">
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <Lightning />
                    <p>Full-stack web developer with 8 years of experience</p>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <Lightning />
                    <p>NDSL Researcher under Dr. Wilson M. Tan (uses Svelte for CS 199)</p>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <Lightning />
                    <p>Trusted Author at DEV</p>
                </li>
                <div class="flex items-center justify-center py-2 sm:gap-2">
                    <span class="variant-filled badge rounded-lg bg-[#FF6534] text-center"
                        >19,000+ <br /> Followers</span
                    >
                    <span class="variant-filled badge rounded-lg bg-[#FF6534] text-center"
                        >636,000+ <br /> Total post views worldwide</span
                    >
                </div>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <Lightning />
                    <p>
                        Open-source Contributor <a
                            href="https://github.com/BastiDood"
                            target="_blank"
                            class="text-[#FF6534] hover:underline">@BastiDood</a
                        >
                    </p>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <Lightning />
                    <p>Also known as a legend of the #acad-inquiries</p>
                </li>
            </ul>

            <div class="flex items-center justify-center">
                <div class="mt-auto grid h-10 w-20 grid-cols-3 place-content-center items-end gap-4">
                    <!-- TODO: Change Speaker's Links -->
                    <a href="/" target="_blank"><LinkedinIcon /></a>
                    <a href="https://github.com/BastiDood" target="_blank"> <GithubIcon /></a>
                    <a href="https://dev.to/somedood" target="_blank"><DevToLogo /></a>
                </div>
            </div>
        </div>
    </div>
</div>

<style>
    h1 {
        text-shadow: 1.5px 1.5px 0px #ff6534;
    }
</style>
