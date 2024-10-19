<script lang="ts">
  import { base } from '$app/paths';
    import Resource from '$lib/components/Resource.svelte';
  import Navbar from "../../lib/components/Navbar.svelte";
  import Page from "../../lib/components/Page.svelte";
  const apply_link = "https://forms.gle/MNBDNZHCxkmP9XRo8";
</script>
<meta name='description' content='Recommended math resources'/>
<Page title="Circle Resources">
  <div slot="nav">
    <Navbar {base}/>
  </div>
  <div slot="content">
    <h1 class="text-5xl text-center my-12 text-blue-500">Resources</h1>
    <p>Some helpful links to assist your math journey.</p>
    <h2 class="text-3xl my-4">General Resources</h2>
    <Resource name="Art of Problem Solving" link="https://www.artofproblemsolving.com" 
      desc="Art of Problem Solving is a wonderful online mathematics resource, which includes online math classes, a variety of resouces, books, videos, contests, and a thriving community. 
      It caters to all ages, from elementary to advanced high school." />
    <Resource name="AMCTrivial" link="https://amctrivial.com/"
      desc="AMCTrivial is a site for unlimited problem practice and other learning features, based on the vast database of the Art of Problem Solving Wiki." />
    <Resource name="Summer Programs" link="https://artofproblemsolving.com/wiki/index.php/Mathematics_summer_program" 
      desc="There are many mathematics summer programs around the country. Many advanced students attend and enjoy them. Linked above is a list." />
    <!-- <h2 class="text-3xl my-4">Contests</h2>
    <Resource name="American Mathematics Competitions (AMC)" link="https://maa.org/student-programs/amc/" 
      desc="Organized by the MAA, the AMC 10 and AMC 12 competitions are the first round of competitions that eventually culminate in selection for the USA team for the International Math Olympiad. 
      They are appropriate for any high school students who are interested in problem solving. They are offered twice (about a week apart) each November. S
      tudents who do well on the AMC 10 or AMC 12 are invited to the AIME (American Invitational Math Exam). 
      From these first two rounds, a small number of students are selected to participate in the USA Math Olympiad or USA Junior Math Olympiad, which is a proof-based competition." />
    <Resource name="Purple Comet" link="https://purplecomet.org/" 
      desc="Held once per year, the Purple Comet is a team-based competition. Students work together to solve 30 problems in 90 minutes (or as many as they can). There is no fee for this competition." />
    <Resource name="Rocket City Math League" link="https://www.grissommath.org/rcml" 
      desc="The RCML runs contests at 5 levels depending on students’ current math course and background. The contests are free to participate in and consist of 3 rounds of individual competition and one round of team competition." /> -->
  </div>
</Page>