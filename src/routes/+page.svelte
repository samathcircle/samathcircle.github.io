<script lang="ts">
	import Page from '../lib/components/Page.svelte';
	const apply_link = 'https://forms.gle/MNBDNZHCxkmP9XRo8';
</script>

<meta
	name="description"
	content="The home page for the San Antonio Math Circle"
/>
<Page title="San Antonio Math Circle">
	<div slot="content">
		<h1 class="my-12 text-center text-5xl text-blue-500">
			San Antonio Math Circle
		</h1>
		<h2 class="my-4 text-3xl">Mission Statement</h2>
		<p>
			The mission of the San Antonio Math Circle is to identify and develop
			exceptional high school math students in San Antonio.
		</p>
		<h2 class="my-4 text-3xl">About the Circle</h2>
		<p>
			The Circle is a place for students interested in mathematics to interact
			with one another and to learn math, solve problems and participate in math
			competitions. We strive to engage and encourage all interested students to
			join this highly enriched community in which like-minded, interested
			students deepen their appreciation, understanding and enjoyment of
			Mathematics.
		</p>
		<h2 class="my-4 text-3xl">
			Interested in joining? <a
				target="_blank"
				class="text-blue-500 underline"
				href={apply_link}>Apply at no cost today!</a
			>
		</h2>
		<p>
			Or, contact us at <a
				class="text-blue-500 underline"
				href="mailto:sanantoniomathcircle@gmail.com"
				>sanantoniomathcircle@gmail.com.</a
			>
		</p>
	</div>
</Page>
