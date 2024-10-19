<script>
  export let first, last, role, desc, img;
</script>

<section class="flex flex-col lg:flex-row items-center justify-around w-full p-4 font-mono">
  <div class="my-4 text-center rounded-xl shadow-md w-full border border-black lg:w-1/2">
    <h2 class='px-4 py-2 text-2xl lg:text-3xl rounded-t-xl'>{first} {last}</h2>
    <h2 class='px-4 py-2 text-xl lg:text-2xl'>{role}</h2>
    <div class="flex flex-row">
      <img class="h-20 mx-4 w-20" src={img} alt={first}!>
      <p class='m-4 text-lg lg:text-xl'>{desc}</p>
    </div>
  </div>
</section>