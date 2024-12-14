<script>
    import '../app.css';
    import Navbar from '../lib/components/Navbar.svelte';
    import { base } from '$app/paths';
</script>

<svelte:head>
    <title>San Antonio Math Circle</title>
    <meta
        name="description"
        content="The website of the San Antonio Math Circle"
    />
</svelte:head>
<div class="min-h-full bg-white">
    <Navbar {base} />
    <slot></slot>
</div>
