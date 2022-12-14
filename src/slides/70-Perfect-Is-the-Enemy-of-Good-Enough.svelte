<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 70. &quot;Perfect&quot; Is the Enemy of &quot;Good Enough&quot;"><div class="titlepage"><div><div><h1 class="title"><a id="quotation_mark_perfect_quotation_mark_is"/>Chapter 70. "Perfect" Is the Enemy of "Good Enough"</h1></div></div></div><div class="epigraph"><p>Greg Nyberg is currently an independent J2EE computer consultant
      with 18 years' experience designing, building, testing, and deploying
      large, high-volume, transactional applications such as reservation
      systems, call centers, and consumer websites. He is the author of the
      WebLogic companion workbook for <span class="emphasis"><em>Enterprise
      JavaBeans</em></span>, Third Edition, (O'Reilly), and the lead author of
      the book <span class="emphasis"><em>Mastering WebLogic Server</em></span> (Wiley).</p><div class="attribution"><span>—<span class="attribution">Greg Nyberg</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject70_d1e3824"/><img alt="image with no caption" src="/images/id2718349/OEBPS/httpatomoreillycomsourceoreillyimages251982.png.jpg"/></div></div><p><span class="strong"><strong>SOFTWARE DESIGNERS</strong></span>, and
    architects in particular, tend to evaluate solutions by how elegant and
    optimum they are for a given problem. Like judges at a beauty contest, we
    look at a design or implementation and immediately see minor flaws or
    warts that could be eliminated with just a few more changes or refactoring
    iterations. Domain models simply beg for one more pass to see if there are
    any common attributes or functions that can be moved into base classes.
    Services duplicated in multiple implementations cry out their need to
    become web services. Queries complain about "buffer gets" and nonunique
    indexes, and demand attention.</p><p>My advice: don't give in to the temptation to make your design, or
    your implementation, perfect! Aim for "good enough" and stop when you've
    achieved it.</p><p>What exactly is "good enough," you might ask? Good enough means that
    the remaining imperfections do not impact system functionality,
    maintainability, or performance in any meaningful way. The architecture
    and design hangs together. The implementation works and meets the
    performance requirements. Code is clear, concise, and well documented.
    Could it be better? Sure, but it is good enough, so stop. Declare victory
    and move on to the next task.</p><p>The search for perfection in design and implementation leads, in my
    opinion, to overdesigned and obfuscated solutions that are, in the end,
    harder to maintain.</p><p>A number of the axioms in this book caution designers to avoid
    unnecessary abstraction or complexity. Why do we have problems keeping
    things simple? Because we are seeking the perfect solution! Why else would
    an architect introduce complexity in a workable solution except to address
    a perceived imperfection in the simpler design?</p><p>Remember that application development is not a beauty contest, so
    stop looking for flaws and wasting time chasing perfection.</p></div></p>
</Slide>
		<Slide>
				<h2>70. "Perfect" Is the Enemy of "Good Enough"</h2>
		</Slide>
</Slide>
