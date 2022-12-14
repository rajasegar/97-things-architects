<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 56. Don't Stretch the Architecture Metaphors"><div class="titlepage"><div><div><h1 class="title"><a id="don_apostrophy_t_stretch_the_architect"/>Chapter 56. Don't Stretch the Architecture Metaphors</h1></div></div></div><div class="epigraph"><p>David Ing is a software architect/technologist living and working
      in Vancouver, British Columbia. Originally from the U.K., he moved
      across to get away from the rain, although now feels tricked by
      dishonest tourist literature.</p><p>As fashion dictates, he now works at Web 2.0 company Taglocity,
      where he splits his time trying to make email systems "less awful" and
      figure out what Web 2.0 actually means.</p><div class="attribution"><span>—<span class="attribution">David Ing</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject56_d1e3229"/><img alt="image with no caption" src="/images/id2716538/OEBPS/httpatomoreillycomsourceoreillyimages251960.png.jpg"/></div></div><p><span class="strong"><strong>ARCHITECTS LIKE TO DEAL WITH
    METAPHORS</strong></span>. They provide nice concrete handles on subjects that
    are often abstract, complex, and moving targets. Whether it is
    communicating with the rest of the team or talking through the
    architecture with the end user, it is so tempting to find something
    tangible or physical to use as a metaphor for what you are trying to
    build.</p><p>This usually starts well, in that a common language can evolve where
    people start to feel that things are moving in the right direction. The
    metaphor develops and grows over time until it takes on a life of its own.
    People feel good about the metaphor—we're making progress!</p><p>What usually happens is that the metaphor for the architecture now
    becomes dangerous. Here's how it can turn on its architect
    creators:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>The business domain customer starts to like your metaphor more
        that your proposed system, in that the happiest possible
        interpretation is now shared by all concerned and no real constraints
        are uncovered.</p></li></ul></div><p>Example: "We're building a transport system like a ship travelling
    between a series of docks."</p><p>You think container ships crossing the Pacific. I was actually
    thinking a rowing boat in a swimming pool, with possibly one oar.</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>The development team starts to think that the metaphor is more
        important than the actual business problem. You start to justify odd
        decisions because of a fondness for the metaphor.</p></li></ul></div><p>Example: "We said it's like a filing cabinet, so of course we have
    to show it to the user alphabetically. I know it's a filing cabinet with
    six dimensions and of infinite length and with a clock built in to it, but
    we've done the icon now—so it has to be a filing cabinet...".</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>The delivered system contains relics of names from old, broken
        metaphors long gone—archaeological testimonials to concepts long
        refactored and dug over.</p></li></ul></div><p>Example: "Why does the Billing Factory object create a Port channel
    for the Rowing boat system? Surely it should return a Pomegranate view for
    the Hub Bus? What do you mean you're new here?"</p><p>So remember, don't fall in love with your system metaphor—only use
    it for exploratory communication purposes, and don't let it turn on
    you.</p></div></p>
</Slide>
		<Slide>
				<h2>56. Don't Stretch the Architecture Metaphors</h2>
		</Slide>
</Slide>
