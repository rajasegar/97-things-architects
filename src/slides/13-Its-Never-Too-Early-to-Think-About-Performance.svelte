<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 13. It's Never Too Early to Think About Performance"><div class="titlepage"><div><div><h1 class="title"><a id="it_apostrophy_s_never_too_early_to_think"/>Chapter 13. It's Never Too Early to Think About Performance</h1></div></div></div><div class="epigraph"><p>Dr. Rebecca Parsons is ThoughtWorks' chief technology officer. She
      has more than 20 years' application development experience, in
      industries ranging from telecommunications to emergent Internet
      services. Rebecca has published in both language and artificial
      intelligence publications, served on numerous program committees, and
      reviews for several journals. She has extensive experience leading in
      the creation of large-scale distributed object applications and the
      integration of disparate systems.</p><div class="attribution"><span>—<span class="attribution">Rebecca Parsons</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject13_d1e811"/><img alt="image with no caption" src="/images/id2698890/OEBPS/httpatomoreillycomsourceoreillyimages251916.png.jpg"/></div></div><p><span class="strong"><strong>BUSINESS USERS SPECIFY THEIR
    NEEDS</strong></span> primarily through functional requirements. The
    nonfunctional aspects of the systems, like performance, resiliency,
    up-time, support needs, and the like, are the purview of the architect.
    However, often the preliminary testing of nonfunctional requirements is
    left until very late in the development cycle, and is sometimes delegated
    completely to the operations team. This is a mistake that is made far too
    often.<a class="indexterm" id="IDX-CHP-13-0058"/></p><p>The reasons are varied. There is presumably no sense in making
    something fast and resilient if it doesn't actually perform the required
    function. The environments and tests themselves are complex. Perhaps the
    early versions of the production system will not be as heavily
    utilized.</p><p>However, if you aren't looking at performance until late in the
    project cycle, you have lost an incredible amount of information as to
    when performance changed. If performance is going to be an important
    architectural and design criterion, then performance testing should begin
    as soon as possible. If you are using an Agile methodology based on
    two-week iterations, I'd say performance testing should be included in the
    process no later than the third iteration.<a class="indexterm" id="IDX-CHP-13-0059"/></p><p>Why is this so important? The biggest reason is that at the very
    least you know the kinds of changes that made performance fall off a
    cliff. Instead of having to think about the entire architecture when you
    encounter performance problems, you can focus on the most recent changes.
    Doing performance testing early and often provides you with a narrow range
    of changes on which to focus.</p><p>In early testing, you may not even try to diagnose performance, but
    you do have a baseline of performance figures to work from. This trend
    data provides vital information in diagnosing the source of performance
    issues and resolving them.</p><p>This approach also allows for the architectural and design choices
    to be validated against the actual performance requirements. Particularly
    for systems with stringent requirements, early validation is crucial to
    delivering the system in a timely fashion.</p><p>Technical testing is also notoriously difficult to get going.
    Setting up appropriate environments, generating the proper data sets, and
    defining the necessary test cases all take a lot of time. By addressing
    performance testing early, you can establish your test environment
    incrementally, thereby avoiding much more expensive efforts once you
    discover performance issues.</p></div></p>
</Slide>
		<Slide>
				<h2>13. It's Never Too Early to Think About Performance</h2>
		</Slide>
</Slide>
