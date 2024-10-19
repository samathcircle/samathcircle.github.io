<script lang="ts">
  import { base } from '$app/paths';
  import Navbar from "../../lib/components/Navbar.svelte";
  import EventCard from "../../lib/components/EventCard.svelte";
  import Page from "../../lib/components/Page.svelte";
  const apply_link = "https://forms.gle/MNBDNZHCxkmP9XRo8";
</script>
<meta name='description' content='The events page for the San Antonio Math Circle'/>
<Page title="Circle Events">
  <div slot="nav">
    <Navbar {base}/>
  </div>
  <div slot="content">
    <h1 class="text-5xl text-center my-12 text-blue-500">Events</h1>
    <p class="text-2xl">None planned yet - stay tuned!</p>
    <!-- <EventCard name="First Meeting" date="November 31" loc="school" desc="Be there!"/>  -->
  </div>
</Page>