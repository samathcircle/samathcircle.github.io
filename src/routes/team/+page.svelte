<script lang="ts">
  import { base } from '$app/paths';
    import TeamCard from '$lib/components/TeamCard.svelte';
  import Navbar from "../../lib/components/Navbar.svelte";
  import Page from "../../lib/components/Page.svelte";
  const apply_link = "https://forms.gle/MNBDNZHCxkmP9XRo8";
</script>
<meta name='description' content='The SA Math Circle leadership team'/>
<Page title="SA Math Circle Team">
  <div slot="nav">
    <Navbar {base}/>
  </div>
  <div slot="content">
    <h1 class="text-5xl text-center my-12 text-blue-500">Team Officials</h1>
    <TeamCard first="William" last="Liu" desc="William is a sophomore at Reagan High School. In his free time, he likes to play violin, participate in math contests, and code."
      role="Co-founder, Webmaster" img="william.png" />
  </div>
</Page>