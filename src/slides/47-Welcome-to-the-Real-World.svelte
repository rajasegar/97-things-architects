<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 47. Welcome to the Real World"><div class="titlepage"><div><div><h1 class="title"><a id="welcome_to_the_real_world"/>Chapter 47. Welcome to the Real World</h1></div></div></div><div class="epigraph"><p>Gregor Hohpe is a software architect with Google, Inc. Gregor is a
      widely recognized thought leader on asynchronous messaging architectures
      and service-oriented architectures. He coauthored the seminal book
      <span class="emphasis"><em>Enterprise Integration Patterns</em></span> (Addison-Wesley
      Professional) and speaks regularly at technical conferences around the
      world.<a class="indexterm" id="IDX-CHP-47-0256"/></p><div class="attribution"><span>—<span class="attribution">Gregor Hohpe</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject47_d1e2863"/><img alt="image with no caption" src="/images/id2715296/OEBPS/httpatomoreillycomsourceoreillyimages251952.png.jpg"/></div></div><p><span class="strong"><strong>ENGINEERS LIKE PRECISION</strong></span>,
    especially software engineers who live in the realm of ones and zeros.
    They are used to working with binary decisions, one or zero, true or
    false, yes or no. Everything is clear and consistent, guaranteed by
    foreign key constraints, atomic transactions, and checksums.</p><p>Unfortunately, the real world is not quite that binary. Customers
    place orders, only to cancel them a moment later. Checks bounce, letters
    are lost, payments delayed, and promises broken. Data entry errors are
    bound to happen every so often. Users prefer "shallow" user interfaces,
    which give them access to many functions at once without being boxed into
    a lengthy, one-dimensional "process," which is easier to program and seems
    more "logical" to many developers. Instead of the call stack controlling
    the program flow, the user is in charge.<a class="indexterm" id="IDX-CHP-47-0257"/></p><p>Worse yet, widely distributed systems introduce a whole new set of
    inconsistencies into the game. Services may not be reachable, change
    without prior notice, or do not provide transactional guarantees. When you
    run applications on thousands of machine, failure is no longer a question
    of "if," but of "when." These systems are loosely coupled, asynchronous,
    concurrent, and do not adhere to traditional transaction semantics. You
    should have taken the blue pill!</p><p>As computer scientists' brave new world is crumbling, what are we to
    do? As is so often the case, awareness is a first important step toward a
    solution. Say goodbye to the good old predictive call-stack architecture,
    where you get to define what happens when and in what order. Instead, be
    ready to respond to events at any time in any order, regaining your
    context as needed. Make asynchronous requests concurrently instead of
    calling methods one by one. Avoid complete chaos by modeling your
    application using event-driven process chains or state models. Reconcile
    errors through compensation, retry, or tentative operations.<a class="indexterm" id="IDX-CHP-47-0258"/></p><p>Sounds scary and more than you bargained for? Luckily, the real
    world has to deal with the same issues for a long time: delayed letters,
    broken promises, messages crossing in transit, payments posted to the
    wrong account—the examples are countless. Accordingly, people had to
    resend letters, write off bad orders, or tell you to ignore the payment
    reminder in case you already sent a payment. So don't just blame the real
    world for your headaches, but also use it as a place to look for
    solutions. After all, Starbucks does not two-phase commit,
    either.<sup>[<a class="footnote" href="#ftn.CHP-47-FN-1" id="CHP-47-FN-1">8</a>]</sup> Welcome to the real world.</p><div class="footnotes"><br/><hr/><div class="footnote"><p><sup>[<a class="para" href="#CHP-47-FN-1" id="ftn.CHP-47-FN-1">8</a>] </sup>See <a class="ulink" href="http://www.eaipatterns.com/ramblings/18_starbucks.html">http://www.eaipatterns.com/ramblings/18_starbucks.html</a>.</p></div></div></div></p>
</Slide>
		<Slide>
				<h2>47. Welcome to the Real World</h2>
		</Slide>
</Slide>
