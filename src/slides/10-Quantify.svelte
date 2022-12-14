<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 10. Quantify"><div class="titlepage"><div><div><h1 class="title"><a id="quantify"/>Chapter 10. Quantify</h1></div></div></div><div class="epigraph"><p>After many years as an amateur, Keith Braithwaite was first paid
      to write software in 1996. After that first job, maintaining a compiler
      built with lex and yacc, he progressed first to modelling microwave
      propagation for GSM network planning, then seasonal variations in demand
      for air freight, in C++. A move to consultancy (and Java) introduced him
      to CORBA and then EJB, and then what was called at the time
      "e-commerce." He is currently a principal consultant with Zuhlke and
      manages its Centre of Agile Practice.<a class="indexterm" id="IDX-CHP-10-0048"/></p><div class="attribution"><span>—<span class="attribution">Keith Braithwaite</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject10_d1e685"/><img alt="image with no caption" src="/images/id2698488/OEBPS/httpatomoreillycomsourceoreillyimages251912.png.jpg"/></div></div><p><span class="strong"><strong>"FAST" IS NOT A REQUIREMENT</strong></span>.
    Neither is "responsive." Nor "extensible." The primary reason why not is
    that you have no objective way to tell if they're met. But still users
    want them. The architect's role is largely to help the system have these
    qualities, and to balance the inevitable conflicts and inconsistencies
    between them. Without objective criteria, architects are at the mercy of
    capricious users ("no, I won't accept it, still not fast enough") and of
    obsessive programmers ("no, I won't release it, still not fast
    enough").<a class="indexterm" id="IDX-CHP-10-0049"/><a class="indexterm" id="IDX-CHP-10-0050"/></p><p>As with all requirements, we seek to write down these desires. Too
    often then the vague adjectives come out: "flexible," "maintainable," and
    the rest. It turns out that in every case (yes, even "usable," with
    effort), these phenomena can be quantified and thresholds set. If this is
    not done, then there is no basis for acceptance of the system by its
    users, valuable guidance is stolen from its builders as they work, and the
    vision is blurred for those architecting it.</p><p>Some simple questions to ask: How many? In what period? How often?
    How soon? Increasing or decreasing? At what rate? If these questions
    cannot be answered, then the need is not understood. The answers should be
    in the business case for the system and if they are not, then some hard
    thinking needs to be done. If you work as an architect and the business
    hasn't (or won't) tell you these numbers, ask yourself why not. Then go
    get them. The next time someone tells you that a system needs to be
    "scalable," ask that person where new users are going to come from and
    why. Ask how many and by when? Reject "Lots" and "soon" as answers.</p><p>Uncertain quantitative criteria must be given as a range: the least,
    the nominal, and the most. If this range cannot be given, then the
    required behavior is not understood. As an architecture unfolds, it can be
    checked against these criteria to see if it is (still) in tolerance. As
    the performance against some criteria drifts over time, valuable feedback
    is obtained. Finding these ranges and checking against them is a
    time-consuming and expensive business. If no one cares enough about the
    system being "performant" (neither a requirement nor a word) to pay for
    performance trials, then more than likely performance doesn't matter. You
    are then free to focus your architectural efforts on aspects of the system
    that are worth paying for.</p><p>"Must respond to user input in no more than 1,500 milliseconds.
    Under normal load (defined as...), the average response time must be
    between 750 and 1,250 milliseconds. Response times less than 500
    milliseconds can't be distinguished by the user, so we won't pay to go
    below that." <span class="emphasis"><em>Now that's a requirement</em></span>.</p></div></p>
</Slide>
		<Slide>
				<h2>10. Quantify</h2>
		</Slide>
</Slide>
