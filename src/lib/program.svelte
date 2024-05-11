<script lang="ts">
    const tableArr = [
        { event: 'Doors Open', time: '05:30 PM' },
        { event: 'Introduction: <Speaker>', time: '06:00 PM - 06:15 PM' },
        { event: 'Workshop 1: <Title>', time: '06:15 - 07:15 PM' },
        { event: 'Company Talk 1: <Title>', time: '07:15 - 07:30 PM' },
        { event: 'Workshop 2: <Title>', time: '07:30 - 08:30 PM' },
        { event: 'Company Talk 2: <Title>', time: '08:30 - 08:45 PM' },
        { event: 'Closing: <Speaker>', time: '08:45 PM - 09:00 PM' },
        { event: 'End of Program', time: '09:00 PM' },
    ];
</script>

<div class="grid justify-items-center gap-4 bg-[#323D42] py-12 text-center">
    <h1 class="h1 h-fit text-white">Innov Camp Program</h1>
    <div class="my-2 grid w-8/12 rounded-lg bg-[#D9D9D9] px-16 py-4">
        {#each tableArr as row}
            <div class="my-4 flex justify-between gap-32">
                <p class="text-left">{row.event}</p>
                <strong><p class="text-right text-[#FF6534]">{row.time}</p></strong>
            </div>
        {/each}
    </div>
</div>
