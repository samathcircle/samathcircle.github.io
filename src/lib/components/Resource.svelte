<script>
    export let name, link, desc;
</script>

<div class="my-4 w-full">
    <h2 class="py-2 text-xl">
        {name}
        <a
            href={link}
            target="_blank"
            class="break-words text-sm text-blue-600 underline">{link}</a
        >
    </h2>
    <p class="mb-2">{desc}</p>
</div>
