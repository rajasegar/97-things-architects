<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 58. Prepare to Pick Two"><div class="titlepage"><div><div><h1 class="title"><a id="prepare_to_pick_two"/>Chapter 58. Prepare to Pick Two</h1></div></div></div><div class="epigraph"><p>Bill de hÓra is chief architect with NewBay Software, where he
      works on large scale web and mobile systems. He is co-editor of the Atom
      Publishing Protocol and previously served on the W3C RDF Working Group.
      He is a recognized expert on REST style and message-passing
      architectures and protocol design.<a class="indexterm" id="IDX-CHP-58-0272"/></p><div class="attribution"><span>—<span class="attribution">Bill de hÓra</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject58_d1e3356"/><img alt="image with no caption" src="/images/id2716845/OEBPS/httpatomoreillycomsourceoreillyimages251964.png.jpg"/></div></div><p><span class="strong"><strong>SOMETIMES ACCEPTING A CONSTRAINT</strong></span>
    or giving up on a property can lead to a better architecture, one that is
    easier and less expensive to build and run. Like buses, desirable
    properties tend to come in threes, and trying to define and build a system
    that supports all three can result in a system that does nothing
    especially well.</p><p>A famous example is Brewer's conjecture, also known as Consistency,
    Availability, and Partitioning (CAP), which states that there are three
    properties that are commonly desired in a distributed system—consistency,
    availability, and partition tolerance—and that it is impossible to achieve
    all three. Trying to have all three will drastically increase the
    engineering costs and typically increase complexity without actually
    achieving the desired effect or business goal. If your data must be
    available and distributed, achieving consistency becomes increasingly
    expensive and eventually impossible. Likewise, if the system must be
    distributed and consistent, ensuring consistency will lead at first to
    latency and performance problems and eventually to unavailability since
    the system cannot be exposed as it tries to reaches agreement.<a class="indexterm" id="IDX-CHP-58-0273"/><a class="indexterm" id="IDX-CHP-58-0274"/></p><p>It's often the case that one or more properties are considered
    inviolate: data cannot be duplicated, all writes must be transactional,
    the system must be 100% available, calls must be asynchronous, there must
    be no single point of failure, everything must be extensible, and so on.
    Apart from being naïve, treating properties as religious artifacts will
    stop you from thinking about the problem at hand. We start to talk about
    architectural deviation instead of principled design and we confuse
    dogmatism with good governance. Instead we should ask, why must these
    properties hold? What benefit is to be had by doing so? When are these
    properties desirable? How can we break up the system to achieve a better
    result? Be ever the skeptic, because architectural dogma tends to
    undermine delivery. The inevitability of such tradeoffs is one of the most
    difficult things to accept in software development, not just as
    architects, but also as developers and stakeholders. But we should cherish
    them; it's far better than having limitless choice, and accepting
    tradeoffs often induces a creative and inventive result.</p></div></p>
</Slide>
		<Slide>
				<h2>58. Prepare to Pick Two</h2>
		</Slide>
</Slide>
