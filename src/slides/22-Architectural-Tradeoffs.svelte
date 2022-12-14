<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 22. Architectural Tradeoffs"><div class="titlepage"><div><div><h1 class="title"><a id="architectural_tradeoffs"/>Chapter 22. Architectural Tradeoffs</h1></div></div></div><div class="epigraph"><p>Mark Richards is a director and senior solutions architect at
      Collaborative Consulting, LLC, where he is involved in the architecture
      and design of large-scale service-oriented architectures in J2EE and
      other technologies, primarily in the financial services industry. He has
      been involved in the software industry since 1984, and has significant
      experience in J2EE architecture and development, object-oriented design
      and development, and systems integration.<a class="indexterm" id="IDX-CHP-22-0093"/></p><div class="attribution"><span>—<span class="attribution">Mark Richards</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject22_d1e1217"/><img alt="image with no caption" src="/images/id2612931/OEBPS/httpatomoreillycomsourceoreillyimages251902.png.jpg"/></div></div><p><span class="strong"><strong>EVERY SOFTWARE ARCHITECT</strong></span> should
    know and understand that you can't have it all. It is virtually impossible
    to design an architecture that has high performance, high availability, a
    high level of security, and a high degree of abstraction all at the same
    time. There is a true story that software architects should know,
    understand, and be able to communicate to clients and colleagues. It is
    the story of a ship called the <span class="emphasis"><em>Vasa</em></span>.<a class="indexterm" id="IDX-CHP-22-0094"/></p><p>In the 1620s Sweden and Poland were at war. Wanting a quick end to
    this costly war, the king of Sweden commissioned the building of a ship
    called the <span class="emphasis"><em>Vasa</em></span>. Now, this was no ordinary ship. The
    requirements for this ship were unlike any other ship of that time; it was
    to be more than 200 feet long, carry 64 guns on two gun decks, and have
    the ability to transport 300 troops safely across the waters into Poland.
    Time was of the essence, and money was tight (sound familiar?). The ship
    architect had never designed such a ship before. Smaller, single-gun deck
    ships were his area of expertise. Nevertheless, the ship's architect
    extrapolated on his prior experience and set out designing and building
    the <span class="emphasis"><em>Vasa</em></span>. The ship was eventually built to
    specifications, and when the eventful day came for the launch, the ship
    proudly sailed into the harbor, fired its gun salute, and promptly sank to
    the bottom of the ocean.</p><p>The problem with the <span class="emphasis"><em>Vasa</em></span> was obvious; anyone
    who has ever seen the deck of a large fighting ship from the 1600s and
    1700s knows that the decks on those ships were crowded and unsafe,
    particularly in battle. Building a ship that was both a fighting ship and
    a transport ship was a costly mistake. The ship's architect, in an attempt
    to fulfill all of the king's wishes, created an unbalanced and unstable
    ship.</p><p>Software architects can learn a lot from this story and apply this
    unfortunate event to the design of software architecture. Trying to
    fulfill each and every requirement (as with the <span class="emphasis"><em>Vasa</em></span>)
    creates an unstable architecture that essentially accomplishes nothing
    well. A good example of a tradeoff is the requirement to make a
    service-oriented architecture (SOA) perform as well as a point-to-point
    solution. Doing so usually requires you to bypass the various levels of
    abstraction created by an SOA approach, thereby creating an architecture
    that looks something like what you would typically order at your local
    Italian restaurant. There are several tools available to architects to
    determine what the tradeoffs should be when designing an architecture. Two
    popular methods are the Architecture Tradeoff Analysis Method (ATAM) and
    the Cost Benefit Analysis Method (CBAM). You can learn more about ATAM and
    CBAM by visiting the Software Engineering Institute (SEI) websites at
    <a class="ulink" href="http://www.sei.cmu.edu/architecture/ata_method.html">http://www.sei.cmu.edu/architecture/ata_method.html</a>
    and <a class="ulink" href="http://www.sei.cmu.edu/architecture/cbam.html">http://www.sei.cmu.edu/architecture/cbam.html</a>,
    respectively.<a class="indexterm" id="IDX-CHP-22-0095"/><a class="indexterm" id="IDX-CHP-22-0096"/><a class="indexterm" id="IDX-CHP-22-0097"/></p></div></p>
</Slide>
		<Slide>
				<h2>22. Architectural Tradeoffs</h2>
		</Slide>
</Slide>
