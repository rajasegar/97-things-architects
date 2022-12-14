<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 67. Understand the Impact of Change"><div class="titlepage"><div><div><h1 class="title"><a id="understand_the_impact_of_change"/>Chapter 67. Understand the Impact of Change</h1></div></div></div><div class="epigraph"><p>Doug Crawford manages a team of middleware developers for a
      telecommunications company in South Africa. He spent the last 10 years
      fitting square pegs into round holes, and has been intimately involved
      on application integration projects in a range of industries:
      advertising, corporate banking, insurance, and education.</p><div class="attribution"><span>—<span class="attribution">Doug Crawford</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject67_d1e3682"/><img alt="image with no caption" src="/images/id2717953/OEBPS/httpatomoreillycomsourceoreillyimages251976.png.jpg"/></div></div><p><span class="strong"><strong>A GOOD ARCHITECT REDUCES COMPLEXITY TO A
    MINIMUM</strong></span> and can design a solution whose abstractions provide
    solid foundations to build upon, but are pragmatic enough to weather
    change.</p><p>The great architect understands the impact of change—not just in
    isolated software modules, but also between people and between
    systems.<a class="indexterm" id="IDX-CHP-67-0284"/></p><p>Change can manifest in a variety of forms:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>Functional requirements change</p></li><li class="listitem"><p>Scalability needs evolve</p></li><li class="listitem"><p>System interfaces are modified</p></li><li class="listitem"><p>People in the team come and go</p></li><li class="listitem"><p>And the list goes on...</p></li></ul></div><p>The breadth and complexity of change in a software project is
    impossible to fathom upfront, and it's a fruitless task trying to
    accommodate every potential bump before it happens. But the architect can
    play a crucial role in determining whether the bumps in the road make or
    break a project.</p><p>The architect's role is not necessarily to manage change, but rather
    to ensure that change is manageable.</p><p>Take, for example, a highly distributed solution that spans many
    applications and relies on a variety of middleware to glue the pieces
    together. A change in a business process can cause havoc if the set of
    dependencies is not correctly tracked or accurately represented in some
    visual model. The impact downstream is particularly significant if the
    change affects the data model or breaks existing interfaces, and the
    existing long-running, stateful transactions must successfully complete
    under the old version of the process.</p><p>This example may appear extreme, but highly integrated solutions are
    now mainstream. This is evident in the choice of integration standards,
    frameworks, and patterns available. Understanding the implications of
    change in these outlying systems is critical in ensuring a sustainable
    level of support to your customers.</p><p>Luckily, there are many tools and techniques to mitigate the impact
    of change:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>Make small, incremental changes</p></li><li class="listitem"><p>Build repeatable test cases and run them often</p></li><li class="listitem"><p>Make building test cases easier</p></li><li class="listitem"><p>Track dependencies</p></li><li class="listitem"><p>Act and react systematically</p></li><li class="listitem"><p>Automate repetitive tasks</p></li></ul></div><p>The architect must estimate the effect of change on various aspects
    of the project's scope, time, and budget, and be prepared to spend more
    time on those areas whose impact would be the greatest as a result of "a
    bump in the road." Measuring risk is a useful tool for knowing where your
    valuable time should be spent.</p><p>Reducing complexity is important, but reduced complexity does not
    equate to simplicity. The payoff for understanding the type and impact of
    change on your solutions is immeasurable in the medium- to
    long-term.</p></div></p>
</Slide>
		<Slide>
				<h2>67. Understand the Impact of Change</h2>
		</Slide>
</Slide>
