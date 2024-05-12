<script>
    import { Avatar } from '@skeletonlabs/skeleton';
    import GithubIcon from './github-logo.svelte';
    import LinkedinIcon from './linkedin-logo.svelte';
</script>

<div class="grid justify-items-center px-8 bg-[#323D42]">
    <h1 class="pb-6 pt-24 h1 h-fit align-middle font-['Bebas_Neue'] text-white ">MEET THE SPEAKERS</h1>
    <div class="grid md:grid-cols-2">

        <div class="speaker flex px-12 items-center flex-col gap-7 shadow-none transition duration-500 cursor-pointer hover:shadow-xl hover:shadow-gray-900 hover:scale-105 hover:cursor-default">
            <!-- TODO: Change Speaker's Avatar -->
            <Avatar class="w-16 md:w-48 lg:w-72 justify-self-center" src="https://images.unsplash.com/photo-1617296538902-887900d9b592?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzExMDB8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop" width="w-32" rounded="rounded-full" />

            <div class="flex flex-col gap-2 items-center text-center font-['Bebas_Neue'] text-2xl">
                <h2>Sebasitan Luis Ortiz</h2>
                <h3 class="text-wrap text-[#FF6534]">UP CSI Director for Engineering</h3>
                <hr class="w-48">
            </div>

            <div>
                <ul class="list-disc">
                    <li>NDSL Researcher under Dr. Wilson M. Tan (uses Svelte for CS 199)</li>
                    <li>
                        Trusted Author at DEV <a href="https://dev.to/dashboard" target="_blank" class="text-[#FF6534] hover:underline">@somedood</a>
                        <ul class="list-disc ml-8">
                            <li>19,000+ Followers</li>
                            <li>636,000+ Total Post Views from around the world</li>
                        </ul>
                    </li>
                    <li>Open-source Contributor <a href="https://github.com/BastiDood" target="_blank" class="text-[#FF6534] hover:underline">@BastiDood</a></li>
                    <li>Also known as a legend of the #acad-inquiries</li>
                </ul>
            </div>

            <div class="mt-auto items-end grid grid-cols-2 gap-4 place-content-center h-10 w-20">
                    <!-- TODO: Change Speaker's Links -->
                    <a href="/" target="_blank"> <LinkedinIcon/> </a>
                    <a href="https://github.com/BastiDood" target="_blank"> <GithubIcon/> </a>
            </div>

        </div>

        <!-- TODO: Add Speaker 2 -->
        <div class="speaker flex px-12 items-center flex-col gap-7 shadow-none transition duration-500 cursor-pointer hover:shadow-xl hover:shadow-gray-900 hover:scale-105 hover:cursor-default">

            <!-- TODO: Change Speaker's Avatar -->
            <Avatar class="w-16 md:w-48 lg:w-72 justify-self-center" src="https://images.unsplash.com/photo-1617296538902-887900d9b592?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzExMDB8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop" width="w-32" rounded="rounded-full" />

            <!-- TODO: Add Speaker's Basic Info -->
            <div class="flex flex-col gap-2 items-center text-center font-['Bebas_Neue'] text-2xl">
                <h2>Speaker #2</h2>
                <h3 class="text-wrap text-[#FF6534]">Title/Position</h3>
                <hr class="w-48">
            </div>

            <!-- TODO: Add Speaker's Description -->
            <div>
                <ul class="list-disc">
                    <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ante ante, ornare vitae eleifend vel, suscipit eget nunc.</li>
                    <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ante ante, ornare vitae eleifend vel, suscipit eget nunc.</li>
                    <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ante ante, ornare vitae eleifend vel, suscipit eget nunc.</li>
                    <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ante ante, ornare vitae eleifend vel, suscipit eget nunc.</li>
                </ul>
            </div>

            <div class="mt-auto items-end grid grid-cols-2 gap-4 place-content-center h-10 w-20">
                    <!-- TODO: Change Speaker's Links -->
                    <a href="/" target="_blank"> <LinkedinIcon/> </a>
                    <a href="/" target="_blank"> <GithubIcon/> </a>
            </div>
        </div>
    </div>
</div>

<style>
    .speaker {
        margin: 5%;
        border-radius: 25px;
        padding: 5% 10%;
        background-color: #D9D9D9;
    }

    h1 {
        text-shadow: 1.5px 1.5px 0px #FF6534;
    }
</style>