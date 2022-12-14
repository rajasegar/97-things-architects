<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 84. Choose Frameworks That Play Well with Others"><div class="titlepage"><div><div><h1 class="title"><a id="choose_frameworks_that_play_well_with_ot"/>Chapter 84. Choose Frameworks That Play Well with Others</h1></div></div></div><div class="epigraph"><p>Eric Hawthorne has architected, designed, and developed
      object-oriented software and distributed systems professionally since
      1988, beginning and for 10 years at Macdonald Dettwiler, a Canadian
      systems-engineering company, where among other things, he had the
      opportunity to absorb some architectural technique from Philippe
      Kruchten.</p><div class="attribution"><span>—<span class="attribution">Eric Hawthorne</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject84_d1e4373"/><img alt="image with no caption" src="/images/id2727095/OEBPS/httpatomoreillycomsourceoreillyimages251998.png.jpg"/></div></div><p><span class="strong"><strong>WHEN CHOOSING SOFTWARE FRAMEWORKS</strong></span>
    as a basis of your system, you must consider not only the individual
    quality and features of each framework, but also how well the set of
    frameworks that make up your system will work together, and how easy it
    will be to adapt them to new software you may need to add as your system
    evolves. This means you must choose frameworks that do not overlap and
    that are humble, simple, and specialized.</p><p>It is best if each framework or third-party library addresses a
    separate logical domain or concern, and does not tread into the domain or
    concern of another framework you need to use.</p><p>Make sure you understand how the logical domains and concerns
    addressed by your candidate frameworks overlap. Draw a Venn diagram if you
    need to. Two data models that overlap substantially in domain, or two
    implementations that address very similar concerns but in slightly
    different ways, will cause unnecessary complexity: the slight differences
    in conceptualization or representation must be mapped or patched with
    kludgy glue code. Chances are, you'll end up not only with complex glue,
    but also with the lowest-common-denominator of the functionality or
    representative power of the two frameworks.</p><p>To minimize the chance that any given framework will overlap with
    another framework, choose frameworks that have a high utility-to-baggage
    ratio, in the context of your system requirements. Utility is the
    functionality or data representation that your project needs from the
    framework. Baggage is the framework's sweeping, all-encompassing,
    I'm-in-charge view of the world. Does it insist on mixing data
    representation and control? Does its data model or set of packages and
    classes extend well beyond what your system needs? Do you have to become a
    fundamentalist in the framework's religion, and limit your choices of
    other frameworks to those of the correct denomination? Does its excess
    complexity limit the kinds of things you can mix with it? If a framework
    comes with lots of baggage, then that it had also better be providing 75%
    of the functionality value in your project.</p><p>Your system should be comprised of mutually exclusive frameworks,
    each of which may be a master of its domain, but which is also simple,
    humble, and flexible.</p></div></p>
</Slide>
		<Slide>
				<h2>84. Choose Frameworks That Play Well with Others</h2>
		</Slide>
</Slide>
