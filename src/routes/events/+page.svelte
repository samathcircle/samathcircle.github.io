<script lang="ts">
    import EventCard from '../../lib/components/EventCard.svelte';
    import Page from '../../lib/components/Page.svelte';
</script>

<Page>
    <div slot="content">
        <h1 class="my-12 text-center text-5xl text-blue-500">Events</h1>
        <EventCard
            name="Stanford Math Tournament"
            date="April 13, 2025"
            desc="The Circle will be training for and competing in this competition."
        />
    </div>
</Page>
