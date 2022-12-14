<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 38. Skyscrapers Aren't Scalable"><div class="titlepage"><div><div><h1 class="title"><a id="skyscrapers_aren_apostrophy_t_scalable"/>Chapter 38. Skyscrapers Aren't Scalable</h1></div></div></div><div class="epigraph"><p>Michael Nygard wrote Release It! Design and Deploy
      Production-Ready Software (Pragmatic Bookshelf), which won a Jolt
      Productivity award in 2008. His other writings can be found at <a class="ulink" href="http://www.michaelnygard.com/blog">http://www.michaelnygard.com/blog</a>.<a class="indexterm" id="IDX-CHP-38-0228"/></p><div class="attribution"><span>—<span class="attribution">Michael Nygard</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject38_d1e2303"/><img alt="image with no caption" src="/images/id2698225/OEBPS/httpatomoreillycomsourceoreillyimages251910.png.jpg"/></div></div><p><span class="strong"><strong>WE OFTEN HEAR SOFTWARE ENGINEERING
    COMPARED</strong></span> to building skyscrapers, dams, or roads. It's true in
    some important aspects.</p><p>The hardest part of civil engineering isn't designing a building
    that will stand up once it is finished, but figuring out the construction
    process. The construction process has to go from a bare site to a finished
    building. In the interim, every worker must be able to apply his trade,
    and the unfinished structure has to stand up the whole time. We can take a
    lesson from that when it comes to deploying large integrated systems.
    ("Integrated" includes virtually every enterprise and web application!)
    Traditional "big bang" deployments are like stacking up a pile of beams
    and girders, throwing them into the air, and expecting them to stick
    together in the shape of a building.<a class="indexterm" id="IDX-CHP-38-0229"/></p><p>Instead, we should plan to deploy one component at a time. Whether
    this is a replacement or a greenfield project, this has two large
    benefits.</p><p>First, when we deploy software, we are exposing ourselves to the
    accumulated technical risk embodied in the code. By deploying one
    component at a time, we spread technical risk out over a longer period of
    time. Every component has its own chance to fail in production, letting us
    harden each one independently.</p><p>The second large benefit is that it forces us to create well-defined
    interfaces between components. Deploying a single component of a new
    system often means reverse-integrating it with the old system. Therefore,
    by the time deployment is complete, each component has worked with two
    different systems: the original and the replacement. Nothing is reusable
    until it has been reused, so piecewise deployment automatically means
    greater reusability. In practice, it also leads to better coherence and
    looser coupling.</p><p>Conversely, there are some important ways that civil engineering
    analogies mislead us. In particular, the concreteness of the real world
    pushes us toward a waterfall process. After all, nobody starts building a
    skyscraper without knowing where it's going or how tall it should be.
    Adding floors to an existing building is costly, disruptive, and risky, so
    we try to avoid it. Once designed, the skyscraper isn't supposed to change
    its location or height. Skyscrapers aren't scalable.</p><p>We cannot easily add lanes to roads, but we've learned how to easily
    add features to software. This isn't a defect of our software processes,
    but a virtue of the medium in which we work. It's OK to release an
    application that only does a few things, as long as users value those
    things enough to pay for them. In fact, the earlier you release your
    application, the greater the net present value of the whole thing will
    be.</p><p>"Early release" may appear to compete with "incremental deployment,"
    but they can actually work together quite well. Early release of
    individual components means that each one can iterate independently. In
    fact, it will force you to work out thorny issues like continuous
    availability during deployments and protocol versioning.</p><p>It's rare to find a technique that simultaneously provides higher
    commercial value and better architectural qualities, but early deployment
    of individual components offers both.</p></div></p>
</Slide>
		<Slide>
				<h2>38. Skyscrapers Aren't Scalable</h2>
		</Slide>
</Slide>
