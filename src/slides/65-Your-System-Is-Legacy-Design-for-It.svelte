<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 65. Your System Is Legacy; Design for It"><div class="titlepage"><div><div><h1 class="title"><a id="your_system_is_legacy_semicolon_design"/>Chapter 65. Your System Is Legacy; Design for It</h1></div></div></div><div class="epigraph"><p>Dave Anderson is a principal software engineer at Belfast software
      company Liberty IT, which supplies IT solutions for Fortune 100 company
      Liberty Mutual. Dave has more than 10 years' experience in the software
      industry with many leading-edge IT companies across several different
      industries and countries.</p><div class="attribution"><span>—<span class="attribution">Dave Anderson</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject65_d1e3600"/><img alt="image with no caption" src="/images/id2717727/OEBPS/httpatomoreillycomsourceoreillyimages251974.png.jpg"/></div></div><p><span class="strong"><strong>EVEN IF YOUR SYSTEM IS BLEEDING
    EDGE</strong></span> and developed in the latest technology, it will be legacy
    to the next guy. Deal with it! The nature of software today means things
    go out of date fast. If you expect your system to go into production and
    survive, even for a few months, then you need to accept that maintenance
    developers will need to fix things up. This means several things:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>Clarity: It should be obvious what role components and classes
        perform.</p></li><li class="listitem"><p>Testability: Is your system easy to verify?</p></li><li class="listitem"><p>Correctness: Do things work as designed or as they should?
        Eliminate quick and nasty fixes.</p></li><li class="listitem"><p>Traceability: Can Ernie the Emergency Bug Fixer—who has never
        seen the code before—jump into production, diagnose a fault, and put
        in a fix? Or does he need an eight-week handover?</p></li></ul></div><p>Try to think of a different team opening up the codebase and working
    out what's happening. This is fundamental for great architecture. It
    doesn't have to be oversimplified or documented to the hilt; a good design
    will document itself in many ways. The way a system behaves in production
    can also expose the design. For example, a sprawling architecture with
    ugly dependencies will often behave like a caged animal in production.
    Spare a thought for (usually more junior) developers who may have to debug
    defects.</p><p>Legacy tends to be a bad word in software circles, but in reality,
    all software systems should endure the tag. It is not a bad thing, as it
    may indicate that your system is durable, meets expectations, and has
    business value. Any software system that has never been called legacy has
    probably been canned before launch—which is not the sign of a successful
    architecture.</p></div></p>
</Slide>
		<Slide>
				<h2>65. Your System Is Legacy; Design for It</h2>
		</Slide>
</Slide>
