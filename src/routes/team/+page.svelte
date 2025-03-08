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
            desc="William is a sophomore at Reagan High School and the captain of their UIL Mathematics team. He has qualified for the AIME twice, is in USACO Silver, and is also the webmaster of several other organizations. In his free time, he likes to play violin, build things with his Arduino, participate in math contests, and code."
            role="Co-founder, Webmaster"
            img="people/william.jpg"
        />
        <TeamCard
            first="Jiseop"
            last="Lee"
            desc="Jiseop is a sophomore at BASIS Shavano and the coach of the award-winning BASIS Mathcounts team. He has qualified for the AIME three times, earned Honor Roll on the AMC 10, and is in USACO Silver. He enjoys playing piano and coding."
            role="Co-founder"
        />
        <TeamCard
            first="Emily"
            last="Liu"
            desc="Emily is a sophomore at the Keystone School and the president of their math club. She is an AIME qualifier."
            role="Co-founder"
            img="people/emily.jpeg"
        ></TeamCard>
        <TeamCard
            first="Timothy"
            last="Ha"
            desc="Timothy is currently a high school freshman. He is in USACO Silver."
            role="Co-founder"
        ></TeamCard>
    </div>
</Page>
