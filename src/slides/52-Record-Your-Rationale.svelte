<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 52. Record Your Rationale"><div class="titlepage"><div><div><h1 class="title"><a id="record_your_rationale"/>Chapter 52. Record Your Rationale</h1></div></div></div><div class="epigraph"><p>Timothy High is a software architect with more than 15 years'
      experience with web, multitiered client-server, and
      application-integration technologies. He is currently working as a
      software architect for Sakonnet Technologies, a leader in Energy Trading
      and Risk Management (ETRM) software.<a class="indexterm" id="IDX-CHP-52-0265"/></p><div class="attribution"><span>—<span class="attribution">Timothy High</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject52_d1e3051"/><img alt="image with no caption" src="/images/id2715880/OEBPS/httpatomoreillycomsourceoreillyimages251954.png.jpg"/></div></div><p><span class="strong"><strong>THERE IS MUCH DEBATE</strong></span> in the
    software development community about the value of documentation,
    especially with regard to the design of the software itself. The
    disagreements generally cluster around the perceived value of doing a "big
    upfront design," and the difficulties of maintaining design documentation
    synchronized with an ever-changing code base.<a class="indexterm" id="IDX-CHP-52-0266"/></p><p>One type of documentation that ages well, doesn't require much
    effort, and almost always pays off is a record of the rationale behind
    decisions that are made regarding the software architecture. As explained
    in Mark Richards's axiom "Architectural Tradeoffs," the definition of a
    software architecture is all about choosing the right tradeoffs between
    various quality attributes, cost, time, and other factors. It should be
    made clear to you, your managers, developers, and other software
    stakeholders why one solution was chosen over another and what tradeoffs
    this entailed. (Did you sacrifice horizontal scalability in the name of
    reducing hardware and licensing costs? Was security such a concern that it
    was acceptable to increase the overall response time in exchange for data
    encryption?)</p><p>The exact format of this documentation can vary according to what is
    appropriate for your project, from quick notes in a text document, wiki,
    or blog, to using a more formal template to record all aspects of each
    architectural decision. Whatever the form and format, the documentation
    should answer the basic questions "What was that decision we made?", and
    "Why did we make that decision?". A secondary question that is often asked
    and should be documented is "What other solutions were considered, and why
    were they rejected?" (actually, the question usually asked is, "Why can't
    we do it <span class="emphasis"><em>my</em></span> way?"). The documentation should also be
    searchable so that you can easily find it whenever it's needed.</p><p>This documentation may come in handy in a number of
    situations:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>As a means of communication to developers regarding important
        architectural principles that should be followed</p></li><li class="listitem"><p>To get the team "on the same page," or even head off a mutiny,
        when developers question the logic behind the architecture (or even to
        humbly accept criticism if it turns out a decision doesn't hold up
        under scrutiny)</p></li><li class="listitem"><p>To show managers and stakeholders exactly why the software is
        being built the way it is (such as why an expensive piece of hardware
        or software is necessary)</p></li><li class="listitem"><p>When handing off the project to a new architect (how many times
        have you inherited a piece of software and wondered exactly why the
        designers did it THAT way?)</p></li></ul></div><p>However, the most important benefits that come from this practice
    are:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>It forces you to be explicit about your reasoning in order to
        verify that your foundations are solid (see the next axiom <a class="xref" href="/links/id2716110/OEBPS/ch53.html" title="Chapter 53. Challenge Assumptions—Especially Your Own">Chapter 53</a>).</p></li><li class="listitem"><p>It can be used as a starting point to re-evaluate a decision
        when the conditions that influenced it have changed.</p></li></ul></div><p>The effort required to create this documentation is equivalent to
    jotting down a few notes whenever you have a meeting or discussion on the
    subject. Whatever the format you choose, this is one type of documentation
    that is worth the investment.</p></div></p>
</Slide>
		<Slide>
				<h2>52. Record Your Rationale</h2>
		</Slide>
</Slide>
