<script>
    import { Avatar } from '@skeletonlabs/skeleton';
    import GithubIcon from './github-logo.svelte';
    import LinkedinIcon from './linkedin-logo.svelte';
</script>

<div class="grid justify-items-center border-t-8 border-t-[#FF6534] bg-[#323D42] px-8">
    <h1 class="h1 h-fit pb-6 pt-8 align-middle font-['Bebas_Neue'] text-5xl text-white lg:text-6xl">
        MEET THE SPEAKERS
    </h1>
    <div class="grid md:grid-cols-2">
        <div
            class="speaker flex cursor-pointer flex-col items-center gap-7 px-12 shadow-none transition duration-500 hover:scale-105 hover:cursor-default hover:shadow-xl hover:shadow-gray-900"
        >
            <!-- TODO: Change Speaker's Avatar -->
            <Avatar
                class="w-16 justify-self-center md:w-48 lg:w-72"
                src="https://images.unsplash.com/photo-1617296538902-887900d9b592?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzExMDB8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop"
                width="w-32"
                rounded="rounded-full"
            />

            <div class="flex flex-col items-center gap-2 text-center font-['Bebas_Neue'] text-2xl">
                <h2>Sebasitan Luis Ortiz</h2>
                <h3 class="text-wrap text-[#FF6534]">UP CSI Director for Engineering</h3>
                <hr class="w-48" />
            </div>

            <div>
                <ul class="list-disc">
                    <li>NDSL Researcher under Dr. Wilson M. Tan (uses Svelte for CS 199)</li>
                    <li>
                        Trusted Author at DEV <a
                            href="https://dev.to/somedood"
                            target="_blank"
                            class="text-[#FF6534] hover:underline">@somedood</a
                        >
                        <ul class="ml-8 list-disc">
                            <li>19,000+ Followers</li>
                            <li>636,000+ Total Post Views from around the world</li>
                        </ul>
                    </li>
                    <li>
                        Open-source Contributor <a
                            href="https://github.com/BastiDood"
                            target="_blank"
                            class="text-[#FF6534] hover:underline">@BastiDood</a
                        >
                    </li>
                    <li>Also known as a legend of the #acad-inquiries</li>
                </ul>
            </div>

            <div class="mt-auto grid h-10 w-20 grid-cols-2 place-content-center items-end gap-4">
                <!-- TODO: Change Speaker's Links -->
                <a href="/" target="_blank"> <LinkedinIcon /> </a>
                <a href="https://github.com/BastiDood" target="_blank"> <GithubIcon /> </a>
            </div>
        </div>

        <!-- TODO: Add Speaker 2 -->
        <div
            class="speaker flex cursor-pointer flex-col items-center gap-7 px-12 shadow-none transition duration-500 hover:scale-105 hover:cursor-default hover:shadow-xl hover:shadow-gray-900"
        >
            <!-- TODO: Change Speaker's Avatar -->
            <Avatar
                class="w-16 justify-self-center md:w-48 lg:w-72"
                src="https://images.unsplash.com/photo-1617296538902-887900d9b592?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzExMDB8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop"
                width="w-32"
                rounded="rounded-full"
            />

            <!-- TODO: Add Speaker's Basic Info -->
            <div class="flex flex-col items-center gap-2 text-center font-['Bebas_Neue'] text-2xl">
                <h2>Speaker #2</h2>
                <h3 class="text-wrap text-[#FF6534]">Title/Position</h3>
                <hr class="w-48" />
            </div>

            <!-- TODO: Add Speaker's Description -->
            <div>
                <ul class="list-disc">
                    <li>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ante ante, ornare vitae
                        eleifend vel, suscipit eget nunc.
                    </li>
                    <li>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ante ante, ornare vitae
                        eleifend vel, suscipit eget nunc.
                    </li>
                    <li>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ante ante, ornare vitae
                        eleifend vel, suscipit eget nunc.
                    </li>
                    <li>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ante ante, ornare vitae
                        eleifend vel, suscipit eget nunc.
                    </li>
                </ul>
            </div>

            <div class="mt-auto grid h-10 w-20 grid-cols-2 place-content-center items-end gap-4">
                <!-- TODO: Change Speaker's Links -->
                <a href="/" target="_blank"> <LinkedinIcon /> </a>
                <a href="/" target="_blank"> <GithubIcon /> </a>
            </div>
        </div>
    </div>
</div>

<style>
    .speaker {
        margin: 5%;
        border-radius: 25px;
        padding: 5% 10%;
        background-color: #d9d9d9;
    }

    h1 {
        text-shadow: 1.5px 1.5px 0px #ff6534;
    }
</style>
