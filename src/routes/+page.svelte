<script lang="ts">
  import { base } from '$app/paths';
  import Navbar from "../lib/components/Navbar.svelte";
  import Page from "../lib/components/Page.svelte";
  const apply_link = "https://forms.gle/MNBDNZHCxkmP9XRo8";
</script>
<meta name='description' content='The home page for the San Antonio Math Circle'/>
<Page title="San Antonio Math Circle">
  <div slot="nav">
    <Navbar {base}/>
  </div>
  <div slot="content">
    <h1 class="text-5xl text-center my-12 text-blue-500">San Antonio Math Circle</h1>
    <h2 class="text-3xl my-4">Mission Statement</h2>
    <p>The mission of the San Antonio Math Circle is to identify and develop exceptional high school math students in San Antonio.</p>
    <h2 class="text-3xl my-4">About the Circle</h2>
    <p>The Circle is a place for students interested in mathematics to interact with one another and to learn math, solve problems and participate in math competitions.
      We strive to engage and encourage all interested students to join this highly enriched community in which like-minded, interested students deepen their appreciation, understanding and enjoyment of Mathematics.</p>
    <h2 class="text-3xl my-4">Interested in joining? <a target="_blank" class="text-blue-500 underline" href={apply_link}>Apply at no cost today!</a></h2>
    <p>Or, contact us at <a class="underline text-blue-500" href="mailto:sanantoniomathcircle@gmail.com">sanantoniomathcircle@gmail.com.</a></p>
  </div>
</Page>