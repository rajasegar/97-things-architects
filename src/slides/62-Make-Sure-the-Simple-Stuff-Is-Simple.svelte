<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 62. Make Sure the Simple Stuff Is Simple"><div class="titlepage"><div><div><h1 class="title"><a id="make_sure_the_simple_stuff_is_simple"/>Chapter 62. Make Sure the Simple Stuff Is Simple</h1></div></div></div><div class="epigraph"><p>Chad LaVigne is a solutions architect and technical hired gun for
      Baltimore-based TEKSystems, Inc. He works primarily in the Minneapolis
      area designing and implementing solutions utilizing Enterprise Java
      technologies.<a class="indexterm" id="IDX-CHP-62-0281"/></p><div class="attribution"><span>—<span class="attribution">Chad LaVigne</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject62_d1e3509"/><img alt="image with no caption" src="/images/id2716437/OEBPS/httpatomoreillycomsourceoreillyimages251958.png.jpg"/></div></div><p><span class="strong"><strong>SOFTWARE ARCHITECTS SOLVE</strong></span> a lot
    of very difficult problems but we also solve some relatively easy ones.
    What we don't want to do is apply a complicated solution to an easy
    problem. As obvious as that advice sounds, it can be hard follow. People
    who design software are smart—really smart. The simple problem-complex
    solution trap can be an easy one to fall into because we like to
    demonstrate our knowledge. If you find yourself designing a solution so
    clever that it may become self-aware, stop and think. Does the solution
    fit the problem? If the answer is no, reconsider your design options. Keep
    the simple stuff simple. You'll get plenty of chances to showcase your
    talent when the difficult problems arise, and they will.</p><p>This doesn't mean that we shouldn't implement elegant solutions. It
    means that if we're tasked with designing a system that only needs to
    support selling one type of SKU-based widget, it's probably a bad idea to
    design for hierarchies of dynamically configurable products.</p><p>The cost incurred by a complicated solution may seem small, but
    chances are that it's larger than you're giving it credit for.
    Over-engineering at the architectural level causes many of the same issues
    as it does at the development level, but the negative effects tend to be
    multiplied. Poor decisions made at the design level are more difficult to
    implement, maintain, and—worst of all—reverse. Before moving forward with
    an architectural decision that exceeds system requirements, ask yourself
    how difficult it would be to remove after it's in place.</p><p>The costs don't stop with the implementation and maintenance of the
    solution in question. Spending more time than necessary on an easy problem
    leaves less time for when the complicated issues show up. Suddenly your
    architecture decisions are creating scope creep and adding unnecessary
    risk to the project. Your time could be spent much more efficiently making
    sure no one else is doing that.</p><p>There's often a strong desire to justify solutions with a perceived
    benefit or implied requirements. Remember this: when you try to guess at
    future requirements, 50% of the time you're wrong and 49% of the time
    you're very, very wrong. Solve today's problem today. Get the application
    out the door on time and wait for feedback to generate real requirements.
    The simple design you create will make it much easier to integrate those
    new requirements when they arrive. If you beat the odds and your implied
    requirement becomes a real one on the next release, you'll already have a
    solution in mind. The difference is that now you'll be able to allocate
    appropriate time for it in the estimate because it's truly required.
    Before you know it, you've got the reputation of a team that makes good
    estimates and gets work done on time.</p></div></p>
</Slide>
		<Slide>
				<h2>62. Make Sure the Simple Stuff Is Simple</h2>
		</Slide>
</Slide>
