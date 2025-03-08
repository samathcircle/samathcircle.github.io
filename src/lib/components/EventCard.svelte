<script>
    export let name, date, desc;
</script>

<section
    class="flex w-full flex-col items-center justify-around p-4 lg:flex-row"
>
    <div
        class="my-4 w-full rounded-xl border border-black text-center shadow-md lg:w-1/2"
    >
        <h2 class="rounded-t-xl px-4 py-2 text-2xl lg:text-3xl">{name}</h2>
        <h2 class="px-4 py-2 text-xl lg:text-2xl">{date}</h2>
        <p class="m-4 text-lg lg:text-2xl">{desc}</p>
    </div>
</section>
