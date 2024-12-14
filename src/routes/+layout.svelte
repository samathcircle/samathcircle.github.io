<script>
    import '../app.css';
    import Navbar from '../lib/components/Navbar.svelte';
</script>

<svelte:head>
    <title>San Antonio Math Circle</title>
    <meta
        name="description"
        content="The website of the San Antonio Math Circle"
    />
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png" />
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png" />
    <link rel="icon" type="image/png" sizes="48x48" href="/favicon-48x48.png" />
    <link
        rel="icon"
        type="image/png"
        sizes="192x192"
        href="/favicon-192x192.png"
    />
</svelte:head>
<div class="min-h-full bg-white">
    <Navbar/>
    <slot></slot>
</div>
