<script lang="ts">
    const tableArr = [
        { event: 'Ingress', time: '05:00 PM - 6:00 PM' },
        { event: 'Introduction', time: '06:00 PM - 06:30 PM' },
        { event: 'Workshop: Svelte Workshop', time: '06:30 PM - 08:30 PM' },
        { event: 'Closing', time: '08:30 PM - 09:00 PM' },
        { event: 'Egress', time: '09:00 PM' },
    ];
</script>

<div
    class="grid justify-items-center gap-0 border-t-8 border-t-[#FF6534] bg-[#323D42] py-8 text-center text-sm sm:text-base md:gap-4"
>
    <h1 class="h1 h-fit font-['Bebas_Neue'] text-5xl text-white lg:text-6xl">Innov Camp Program</h1>
    <div class="lg:w-7/12 my-4 grid w-11/12 rounded-3xl bg-[#D9D9D9] px-8 py-4 md:w-10/12 md:px-16 text-lg">
        {#each tableArr as row}
            <div class="my-4 flex justify-between inter">
                <strong><p class="text-left">{row.event}</p></strong>
                <strong><p class="text-right text-[#FF6534]">{row.time}</p></strong>
            </div>
        {/each}
    </div>
</div>

<style>
    h1 {
        text-shadow: 1.5px 1.5px 0px #ff6534;
    }
</style>