<script lang="ts">
    import TeamCard from '$lib/components/TeamCard.svelte';
    import Page from '../../lib/components/Page.svelte';
</script>

<Page>
    <div slot="content">
        <h1 class="my-12 text-center text-5xl text-blue-500">Team Officials</h1>
        <TeamCard
            first="William"
            last="Liu"
            desc="William is a sophomore at Reagan High School. In his free time, he likes to play violin, participate in math contests, and code."
            role="Co-founder, Webmaster"
            img="william.png"
        />
    </div>
</Page>
