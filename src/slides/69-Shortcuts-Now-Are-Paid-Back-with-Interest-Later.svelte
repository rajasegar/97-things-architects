<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 69. Shortcuts Now Are Paid Back with Interest Later"><div class="titlepage"><div><div><h1 class="title"><a id="shortcuts_now_are_paid_back_with_interes"/>Chapter 69. Shortcuts Now Are Paid Back with Interest Later</h1></div></div></div><div class="epigraph"><p>Scot Mcphee is an Australian software developer and architect with
      more than 15 years of experience coding and designing applications. Over
      the last eight years, he's worked mostly within the J2EE stack.</p><div class="attribution"><span>—<span class="attribution">Scot Mcphee</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject69_d1e3790"/><img alt="image with no caption" src="/images/id2718237/OEBPS/httpatomoreillycomsourceoreillyimages251980.png.jpg"/></div></div><p><span class="strong"><strong>IT'S IMPORTANT TO REMEMBER</strong></span> when
    architecting a system that maintenance will, in the long run, consume more
    resources than initial development of the project. Shortcuts taken during
    the initial development phase of a project can result in significant
    maintenance costs later.</p><p>For example, you may have been informed that unit tests don't
    deliver direct value, and so you tell your developers to skip the rigorous
    application of them. This makes the delivered system much more difficult
    to change in the future, and decreases confidence when making those
    changes. The system will require far more manual testing for a smaller set
    of changes, leading to brittleness and increased maintenance expenses as
    well as a design that's not as appropriate as a fully tested design (let
    alone a test-first design).</p><p>A serious architectural mistake is to adapt an existing system for a
    purpose that it is not fit for, on the basis that using an existing system
    somehow reduces costs. For example, you might find yourself utilizing BPEL
    architectural components coupled with database triggers to deliver an
    asynchronous messaging system. This might be done or insisted upon for
    reasons of convenience or because that is the architecture known to you or
    the client. But a messaging architecture should have been selected in the
    first instance after requirements made it clear, it was a necessary
    component. Poor decisions made at the inception of a project make it much
    more expensive to re-architect the system to meet new requirements.</p><p>In addition to avoiding shortcuts during the initial development
    phase, it's also important to correct poor design decisions as quickly as
    they are discovered. Poorly designed features can become the foundation
    for future features, making corrective action later even more
    costly.</p><p>For example, if you discover that inappropriate libraries were
    selected for some underlying functionality, they should be replaced as
    soon as possible. Otherwise, the effort to make them fit evolving
    requirements will result in additional layers of abstractions, each
    designed to hide the poor fit of the previous layer. You are building
    yourself a ball of tangled twine, tack, and sticky tape and with every
    layer you add, it is harder to unravel. This results in a system that is
    resistant to change.</p><p>As an architect, whenever you encounter an architectural problem or
    design flaw, insist that it be rectified now, when it is cheapest to fix.
    The longer you leave it to drag out, the higher the interest payment
    is.</p></div></p>
</Slide>
		<Slide>
				<h2>69. Shortcuts Now Are Paid Back with Interest Later</h2>
		</Slide>
</Slide>
