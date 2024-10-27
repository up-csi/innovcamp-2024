<script lang="ts">
    import Audience1 from '$lib/assets/event-photos/ic2024-photo-04.webp?enhanced';
    import Audience2 from '$lib/assets/event-photos/ic2024-photo-06.webp?enhanced';
    import Audience3 from '$lib/assets/event-photos/ic2024-photo-07.webp?enhanced';
    import Audience4 from '$lib/assets/event-photos/ic2024-photo-08.webp?enhanced';
    import Certificates from '$lib/assets/event-photos/ic2024-photo-10.webp?enhanced';
    import Hosts from '$lib/assets/event-photos/ic2024-photo-02.webp?enhanced';
    import Innov1 from '$lib/assets/event-photos/ic2024-photo-05.webp?enhanced';
    import Innov2 from '$lib/assets/event-photos/ic2024-photo-11.webp?enhanced';
    import QnA from '$lib/assets/event-photos/ic2024-photo-09.webp?enhanced';
    import Slides from '$lib/assets/event-photos/ic2024-photo-03.webp?enhanced';
    import Speaker1 from '$lib/assets/event-photos/ic2024-photo-00.webp?enhanced';
    import Speaker2 from '$lib/assets/event-photos/ic2024-photo-01.webp?enhanced';
</script>

<div class="grid grid-flow-row justify-items-center gap-4 border-t-8 border-t-[#FF6534] bg-[#323D42] p-8">
    <h1 class="font-['Bebas_Neue'] text-5xl text-white [text-shadow:1.5px_1.5px_0_rgba(255,101,52,255)] lg:text-6xl">
        GALLERY
    </h1>
    <div class="grid grid-flow-row grid-cols-2 gap-2 md:grid-cols-4">
        <div class="transition hover:scale-110">
            <enhanced:img
                src={Speaker1}
                alt="InnovCamp 2024 speaker and UP CSI Director for Engineering, Basti Ortiz, delivering a presentation"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
        <div class="transition hover:scale-110">
            <enhanced:img
                src={Speaker2}
                alt="InnovCamp 2024 speaker and UP CSI Director for Engineering, Basti Ortiz"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
        <div class="transition hover:scale-110">
            <enhanced:img
                src={Hosts}
                alt="The hosts of InnovCamp 2024"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
        <div class="transition hover:scale-110">
            <enhanced:img
                src={Slides}
                alt="The InnovCamp 2024 Svelte Surge cover image projected on a screen"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
        <div class="transition hover:scale-110">
            <enhanced:img
                src={Audience1}
                alt="InnovCamp 2024 audience members"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
        <div class="transition hover:scale-110">
            <enhanced:img
                src={Innov1}
                alt="The members of the Innovation committee, responsible for organizing the event"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
        <div class="transition hover:scale-110">
            <enhanced:img
                src={Audience2}
                alt="InnovCamp 2024 audience members"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
        <div class="transition hover:scale-110">
            <enhanced:img
                src={Audience3}
                alt="InnovCamp 2024 audience members"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
        <div class="transition hover:scale-110">
            <enhanced:img
                src={Audience4}
                alt="InnovCamp 2024 audience members, as seen from the back of the room"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
        <div class="transition hover:scale-110">
            <enhanced:img
                src={QnA}
                alt="The speaker and hosts conducting the question and answer segment of InnovCamp 2024"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
        <div class="transition hover:scale-110">
            <enhanced:img
                src={Certificates}
                alt="Speaker Basti Ortiz receives a certificate from UP CSI's president and vice president for Innovation"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
        <div class="transition hover:scale-110">
            <enhanced:img
                src={Innov2}
                alt="UP CSI's vice president for Innovation, Hans Lorico, delivering a thank you speech"
                class="rounded-xl hover:shadow-lg hover:shadow-gray-900"
            />
        </div>
    </div>
</div>
