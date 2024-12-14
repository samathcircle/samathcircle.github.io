<script>
    export let base;
</script>

<div
    class="flex h-auto w-screen flex-col items-center justify-center bg-gray-600 p-4 text-center text-2xl text-white sm:flex-row"
>
    <div class="flex flex-col items-center sm:flex-row sm:space-x-8">
        <a class="cursor-pointer uppercase text-white" href="{base}/">Home</a>
        <a class="cursor-pointer uppercase text-white" href="{base}/resources"
            >Resources</a
        >
        <a class="cursor-pointer uppercase text-white" href="{base}/events"
            >Events</a
        >
        <a class="cursor-pointer uppercase text-white" href="{base}/team"
            >Team</a
        >
    </div>
</div>
