<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 97. Great Software Is Not Built, It Is Grown"><div class="titlepage"><div><div><h1 class="title"><a id="great_software_is_not_built_comma_it"/>Chapter 97. Great Software Is Not Built, It Is Grown</h1></div></div></div><div class="epigraph"><p>Bill de hÓra is chief architect with NewBay Software, where he
      works on large scale web and mobile systems. He is co-editor of the Atom
      Publishing Protocol and previously served on the W3C RDF Working Group.
      He is a recognized expert on REST style and message-passing
      architectures and protocol design.<a class="indexterm" id="IDX-CHP-97-0331"/></p><div class="attribution"><span>—<span class="attribution">Bill de hÓra</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject97_d1e4966"/><img alt="image with no caption" src="/images/id2716845/OEBPS/httpatomoreillycomsourceoreillyimages251964.png.jpg"/></div></div><p><span class="strong"><strong>AS AN ARCHITECT</strong></span>, you are tasked
    with providing the initial structure and arrangement of software systems
    that will grow and change over time, will have to be reworked, and will
    have to talk to other systems—and almost always in ways you and your
    stakeholders did not foresee. Even though we are called
    <span class="emphasis"><em>architects</em></span>, and we borrow many metaphors from
    building and engineering, great software is not built, it is grown.</p><p>The single biggest predictor of software failure is size; on
    reflection there's almost no benefit to be had from starting with a large
    system design. Yet at some point we will all be tempted to do exactly
    that. As well as being prone to incidental complexity and inertia,
    designing large systems upfront means larger projects, which are more
    likely to fail, more likely to be untestable, more likely to be fragile,
    more likely to have unneeded and unused parts, more likely to be
    expensive, and more likely to have a negative political
    dimension.<a class="indexterm" id="IDX-CHP-97-0332"/></p><p>Therefore resist trying to design a large complete system to "meet
    or exceed" the known requirements and desired properties, no matter how
    tempting that might be. Have a grand vision, but not a grand design. Let
    you and your system learn to adapt as the situation and requirements
    inevitably change.</p><p>How to do this? The best way to ensure that a software system can
    evolve and adapt is to evolve and adapt it from the very outset. Inducing
    a system to evolve means starting with a small running system, a working
    subset of the intended architecture—the simplest thing that could possibly
    work. This nascent system will have many desirable properties and can
    teach us much about the architecture that a large system, or worse, a
    collection of architectural documents, never can. You are more likely to
    have been involved in its implementation. Its lack of surface area will be
    easier to test and therefore less prone to coupling. It will require a
    smaller team, which will reduce the cost of coordinating the project. Its
    properties will be easier to observe. It will be easier to deploy. It will
    teach you and your team at the earliest possible moment what does and does
    not work. It will tell you where the system will not evolve easily, where
    it is likely to crystallize, where it is fragile. Where it might break.
    Perhaps most important, it will be comprehensible and tangible to its
    stakeholders from the beginning, allowing them to grow into the overall
    design as well.</p><p>Design the smallest system you can, help deliver it, and let it
    evolve toward the grand vision. Although this might feel like giving up
    control, or even shirking your responsibilities, ultimately your
    stakeholders will thank you for it. Do not confuse an evolutionary
    approach with throwing requirements out, the dreaded phasing, or building
    one to throw away.</p></div></p>
</Slide>
		<Slide>
				<h2>97. Great Software Is Not Built, It Is Grown</h2>
		</Slide>
</Slide>
