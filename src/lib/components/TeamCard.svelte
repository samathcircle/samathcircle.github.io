<script>
    export let first, last, role, desc, img = "";
</script>

<section
    class="flex w-full flex-col items-center justify-around p-4 lg:flex-row"
>
    <div
        class="my-4 w-full rounded-xl border border-black text-center shadow-md lg:w-1/2"
    >
        <h2 class="rounded-t-xl px-4 py-2 text-2xl lg:text-3xl">
            {first}
            {last}
        </h2>
        <h2 class="px-4 py-2 text-xl lg:text-2xl">{role}</h2>
        <div class="flex flex-row">
            <img class="mx-4 h-30" src={img} alt=" " />
            <p class="m-4 text-lg lg:text-xl">{desc}</p>
        </div>
    </div>
</section>
