<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 50. Architects' Focus Is on the Boundaries and Interfaces"><div class="titlepage"><div><div><h1 class="title"><a id="architects_apostrophy_focus_is_on_the"/>Chapter 50. Architects' Focus Is on the Boundaries and Interfaces</h1></div></div></div><div class="epigraph"><p>Einar Landre is a practicing software professional with 25 years'
      experience as a developer, architect, manager, consultant, and
      author/presenter.<a class="indexterm" id="IDX-CHP-50-0261"/></p><p>Currently for StatoilHydro's Business Application Services, he
      engages in business-critical application development, architecture
      reviews, and software process improvement activities, specializing in
      SOA, domain-driven design, use of multi-agents and design of
      large-scale, networked, software-intensive systems.</p><div class="attribution"><span>—<span class="attribution">Einar Landre</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject50_d1e2977"/><img alt="image with no caption" src="/images/id2613143/OEBPS/httpatomoreillycomsourceoreillyimages251906.png.jpg"/></div></div><p><span class="strong"><strong>SINCE LORD NELSON DESTROYED</strong></span> the
    French and Spanish fleet at Trafalgar in 1805, "divide and conquer" has
    been the mantra for dealing with complex and difficult problems. A more
    familiar term with the same intent is <span class="emphasis"><em>separation of
    concern</em></span>. From separation of concern we get encapsulation, and
    from encapsulation we get boundaries and interfaces.<a class="indexterm" id="IDX-CHP-50-0262"/><a class="indexterm" id="IDX-CHP-50-0263"/></p><p>From an architect's point of view, the hard part is to find the
    natural places to locate boundaries and define the appropriate interfaces
    needed to build a working system. This is especially difficult in large
    enterprise systems, often characterized by few natural boundaries and
    intertangled domains. In this situation, old wisdom such as "Minimize
    coupling, maximize cohesion" and "Do not slice through regions where high
    rates of information exchange are required" provide some guidance, but
    they say nothing about how to communicate the problems and potential
    solutions to stakeholders in a easy way.</p><p>Here the concept of bounded contexts and context mapping, as
    described by Eric Evans in his book <span class="emphasis"><em>Domain-Driven
    Design</em></span> (Addison-Wesley Professional), comes to the rescue. A
    bounded context is an area where a model or concept is uniquely defined,
    and we represent it as a cloud or bubble with a descriptive name that
    defines its role and responsibility in the domain at hand. As an example,
    a shipping system might include contexts such as Cargo Operation, Cargo
    Scheduling, and Harbor Movement. In other domains, other names will be
    appropriate.</p><p>With the bounded contexts identified and drawn up on the whiteboard,
    it's time to start to draw the relationships between the contexts. These
    relationships might address organizational, functional, or technical
    dependencies. The result from this exercise is a context map, a collection
    of bounded contexts and the interfaces between them.</p><p>Such a context map provides architects with a powerful tool that
    allows them to focus on what belongs together and what should be kept
    apart, enabling them to divide and conquer wisely in a communicative way.
    The technique can easily be used to document and analyze the as-is
    situation, and from there guide redesign toward a better system
    characterized by low coupling, high cohesion, and well-defined
    interfaces.</p></div></p>
</Slide>
		<Slide>
				<h2>50. Architects' Focus Is on the Boundaries and Interfaces</h2>
		</Slide>
</Slide>
