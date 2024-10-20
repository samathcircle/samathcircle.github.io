<script>
  export let title;
</script>
<title>{title}</title>
<body class="bg-white w-screen font-sans text-black">
  <slot name="nav"></slot>
  <main class="mx-2 lg:w-1/2 lg:m-auto"> 
    <slot name="content"></slot>
  </main>
  <!-- <div class="h-[50vh] lg:h-[90vh]"></div> -->
  <div class="h-full pb-8"></div>
  <footer class="text-center">Contribute to this website at <a class="underline text-blue-500" target="_blank" rel="noopener noreferrer"  href="https://github.com/samathcircle/samathcircle.github.io">its GitHub.</a></footer>
</body>