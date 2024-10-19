<script>
  export let title;
</script>
<title>{title}</title>
<body class="bg-white w-screen font-sans text-black">
  <slot name="nav"></slot>
  <main class="lg:w-1/2 m-auto"> 
    <slot name="content"></slot>
  </main>
  <div class="h-[50vh] lg:h-[90vh]"></div>
  <footer class="text-center">Contribute to this website at <a class="underline" target="_blank" rel="noopener noreferrer"  href="https://github.com/samathcircle/samathcircle.github.io">its GitHub.</a></footer>
</body>