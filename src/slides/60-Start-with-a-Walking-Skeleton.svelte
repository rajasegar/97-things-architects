<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 60. Start with a Walking Skeleton"><div class="titlepage"><div><div><h1 class="title"><a id="start_with_a_walking_skeleton"/>Chapter 60. Start with a Walking Skeleton</h1></div></div></div><div class="epigraph"><p>Clint Shank is a software developer, consultant, and mentor at
      Sphere of Influence, Inc., a software design and engineering services
      company for commercial and federal clients.</p><div class="attribution"><span>—<span class="attribution">Clint Shank</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject60_d1e3432"/><img alt="image with no caption" src="/images/id2717125/OEBPS/httpatomoreillycomsourceoreillyimages251968.png.jpg"/></div></div><p><span class="strong"><strong>ONE VERY USEFUL STRATEGY FOR
    IMPLEMENTING</strong></span>, verifying, and evolving an application
    architecture is to start with what Alistair Cockburn calls a
    <span class="emphasis"><em>walking skeleton</em></span>. A walking skeleton is a minimal,
    end-to-end implementation of the system that links together all the main
    architectural components. Starting small, with a working system exercising
    all the communication paths, gives you confidence that you are heading in
    the right direction.<a class="indexterm" id="IDX-CHP-60-0278"/></p><p>Once the skeleton is in place, it's time to put it on a workout
    program. Bulk it up with full body workouts. This means implement
    incrementally, adding end-to-end functionality. The goal is to keep the
    system running, all the while growing the skeleton.</p><p>Making changes to an architecture is harder and more expensive the
    longer it has been around and the bigger it gets. We want to find mistakes
    early. This approach gives us a short feedback cycle from which we can
    more quickly adapt and work iteratively as necessary to meet the
    business's prioritized list of runtime-discernable quality attributes.
    Assumptions about the architecture are validated earlier. The architecture
    is more easily evolved because problems are found at an earlier stage when
    less has been invested in its implementation.</p><p>The bigger the system, the more important it is to use this
    strategy. In a small application, one developer can implement a feature
    from top to bottom relatively quickly, but this becomes impractical with
    larger systems. It is quite common to have multiple developers on a single
    team or even on multiple, possibly distributed, teams involved in
    implementing end-to-end. Consequently, more coordination is necessary. And
    naturally, developers implement at a different pace. Some developers can
    accomplish a lot and in little time while others can spend a lot of time
    implementing very little. More difficult and time consuming efforts should
    be done earlier in the project.</p><p>Start with a walking skeleton, keep it running, and grow it
    incrementally.</p></div></p>
</Slide>
		<Slide>
				<h2>60. Start with a Walking Skeleton</h2>
		</Slide>
</Slide>
