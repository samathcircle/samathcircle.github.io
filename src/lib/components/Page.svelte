<div class="bg-white font-sans text-black">
    <slot name="nav"></slot>
    <main class="m-auto px-2 2xl:w-2/3">
        <slot name="content"></slot>
    </main>
    <div class="h-full pb-16"></div>
    <footer class="text-center">
        Contribute to this website at <a
            class="text-blue-500 underline"
            target="_blank"
            rel="noopener noreferrer"
            href="https://github.com/samathcircle/samathcircle.github.io"
            >its GitHub.</a
        >
    </footer>
</div>
