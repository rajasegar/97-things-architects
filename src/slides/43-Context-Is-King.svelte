<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 43. Context Is King"><div class="titlepage"><div><div><h1 class="title"><a id="context_is_king"/>Chapter 43. Context Is King</h1></div></div></div><div class="epigraph"><p>Edward Garson has been passionate about technology since learning
      to program in Logo on the Apple II. He currently works as a software
      architect in the Center for Agile Practices at Zuhlke Engineering, a
      leading Swiss-based technology firm.<a class="indexterm" id="IDX-CHP-43-0251"/></p><div class="attribution"><span>—<span class="attribution">Edward Garson</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject43_d1e2644"/><img alt="image with no caption" src="/images/id2713913/OEBPS/httpatomoreillycomsourceoreillyimages251942.png.jpg"/></div></div><p><span class="strong"><strong>I FEEL THERE IS A CERTAIN IRONY</strong></span>
    in trying to impart something about architectural ideals, when the very
    premise I wish to begin with is that effectively there are no ideals. If
    this is indeed the case, then surely there is nothing to write; I am a
    contradiction and by doing this I run the risk of the universe imploding
    or something like that.</p><p>But alas, <span class="emphasis"><em>ceci n'est pas une pipe</em></span>.</p><p>One of the most valuable lessons that I have learned as a software
    architect is that context is king, and simplicity its humble servant. What
    this means in practical terms is that context is the only force that
    trumps simplicity when you're making architectural decisions.<a class="indexterm" id="IDX-CHP-43-0252"/><a class="indexterm" id="IDX-CHP-43-0253"/></p><p>When I say <span class="emphasis"><em>context</em></span>, I refer not only to
    high-level, immediate forces such as key business drivers, but also to
    elements in the periphery, such as emerging technologies and thought
    leadership on diverse topics. Indeed, good architects keep track of
    several fast-moving targets.</p><p>What constitutes good architecture? It is the product of decisions
    made within a context usually tainted with multiple competing priorities.
    Those competing priorities mean that sometimes the most important
    decisions are not about what you put in, but rather what you omit. The
    currency of good architecture is simply astute decision-making (while the
    products are all only about communicating your intent).</p><p>Historically, there have been some fascinating examples of the
    influence that context can have on architecture. A favorite example
    involves the database selected to support an ambitious new software system
    for a modern battlefield tank.<sup>[<a class="footnote" href="#ftn.CHP-43-FN-1" id="CHP-43-FN-1">6</a>]</sup> (Deciding what database to use is not usually
    architecturally significant; this example merely serves to illustrate a
    point.)</p><p>When it came time to choose the database, the team assessed many. It
    found that while the tank was moving quickly over undulating terrain while
    tracking a target, the majority of the databases were capable of
    supporting the maximal throughput required of the navigation and targeting
    systems. But the team was taken by surprise when it discovered that firing
    the main gun on the tank caused such a strong electromagnetic pulse that
    it totally crashed the onboard systems and of course the database along
    with it! On a modern battlefield, a tank without its software running is
    quite literally in the dark. In this context, recovery time was the
    overwhelming factor in the choice of database, and no database did that
    better at the time than InterBase,<sup>[<a class="footnote" href="#ftn.CHP-43-FN-2" id="CHP-43-FN-2">7</a>]</sup> and that is why it was chosen for the M1 Abrams tank.</p><p>So, while newsgroups rage with the flames of technology debates of X
    versus Y, it is idle amusement. The reason these debates rage is often not
    because of huge disparities in their technical merits, but rather because
    there are more subtle differences between them, and what features
    individuals value more than others when there is no guiding context to act
    as a trump card.</p><p>Your team should be free of ideals, reflect on context in the first
    instance, and reach for the simplest solutions from there.</p><div class="footnotes"><br/><hr/><div class="footnote"><p><sup>[<a class="para" href="#CHP-43-FN-1" id="ftn.CHP-43-FN-1">6</a>] </sup>A tank, despite its extremely dubious purpose, is still an
        engineering marvel.</p></div><div class="footnote"><p><sup>[<a class="para" href="#CHP-43-FN-2" id="ftn.CHP-43-FN-2">7</a>] </sup>Interestingly, InterBase had an architecture that caused
        disk-writes to leave the database in an always-consistent state. This
        is one reason that contributes to its ability to recover from hard
        failures so quickly.</p></div></div></div></p>
</Slide>
		<Slide>
				<h2>43. Context Is King</h2>
		</Slide>
</Slide>
