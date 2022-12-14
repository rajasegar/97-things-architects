<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 48. Don't Control, but Observe"><div class="titlepage"><div><div><h1 class="title"><a id="don_apostrophy_t_control_comma_but"/>Chapter 48. Don't Control, but Observe</h1></div></div></div><div class="epigraph"><p>Gregor Hohpe is a software architect with Google, Inc. Gregor is a
      widely recognized thought leader on asynchronous messaging architectures
      and service-oriented architectures. He coauthored the seminal book
      <span class="emphasis"><em>Enterprise Integration</em></span> Patterns (Addison-Wesley
      Professional) and speaks regularly at technical conferences around the
      world.<a class="indexterm" id="IDX-CHP-48-0259"/></p><div class="attribution"><span>—<span class="attribution">Gregor Hohpe</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject48_d1e2909"/><img alt="image with no caption" src="/images/id2715296/OEBPS/httpatomoreillycomsourceoreillyimages251952.png.jpg"/></div></div><p><span class="strong"><strong>TODAY'S SYSTEMS ARE DISTRIBUTED AND LOOSELY
    COUPLED</strong></span>. Building loosely coupled systems is a bit of a drag,
    so why do we bother? Because we want our systems to be flexible so they do
    not break apart at the slightest change. This is a critical property in
    today's environments, where we may only control a small portion of our
    application, the remainder living in distributed services or third-party
    packages, controlled by other departments or external vendors.</p><p>So, it looks like the effort to build a system that is flexible and
    can evolve over time is a good idea. But that also means our system will
    change over time. As in "today's system is not what it was yesterday."
    Unfortunately, this makes documenting the system challenging. It's
    commonly known that documentation is out of date the moment it is printed,
    but in a system that changes all the time, things can only be worse.
    Moreover, building a system that is flexible generally means the
    architecture is more complex and it's more difficult to get the proverbial
    "big picture." For example, if all system components communicate with one
    another over logical, configurable channels, one better have a look at the
    channel configuration to get any idea what is going on. Sending messages
    into the logical la-la-land is unlikely to trigger a compiler error, but
    it is sure to disappoint the user whose action was encapsulated in that
    message.</p><p>Being a control-freak architect is so yesteryear, leading to tightly
    coupled and brittle solutions. But letting the software run wild is sure
    to spawn chaos. You have to supplement the lack of control with other
    mechanisms to avoid doing an instrument flight without the instruments.
    But what kind of instruments do we have? Plenty, actually. Today's
    programming languages support reflection, and almost all runtime platforms
    provide runtime metrics. As your system becomes more configurable, the
    current system configuration is another great source of information.
    Because so much raw data is difficult to understand, extract a model from
    it. For example, once you figure out which components send messages to
    which logical channels, and which components listen to these channels, you
    can create a graph model of the actual communication between components.
    You can do this every few minutes or hours, providing an accurate and
    up-to-date image of the system as it evolves. Think of it as "Reverse
    MDA."<sup>[<a class="footnote" href="#ftn.CHP-48-FN-1" id="CHP-48-FN-1">9</a>]</sup> Instead of a model driving the architecture, you build a
    flexible architecture, and extract the model from the actual system
    state.</p><p>In many cases, it's easy to visualize this model, creating the
    literal big picture. However, resist the temptation to plot the 3×5-meter
    billboard of boxes and lines, which contains every class in your system.
    That picture may pass as contemporary art, but it's not a useful software
    model. Instead, use a 1,000-foot view as described by Erik Doernenburg, a
    level of abstraction that actually tells you something. On top of that,
    you can make sure your model passes basic validation rules, such as the
    absence of circular dependencies in a dependency graph, or no messages
    being sent to a logical channel no one listens to.</p><p>Letting go of control is a scary thing, even when it comes to system
    architecture. But supplemented by observation, model extraction, and
    validation, it is probably the way only to architect for the 21st
    century.</p><div class="footnotes"><br/><hr/><div class="footnote"><p><sup>[<a class="para" href="#CHP-48-FN-1" id="ftn.CHP-48-FN-1">9</a>] </sup>MDA = model-driven architecture.</p></div></div></div></p>
</Slide>
		<Slide>
				<h2>48. Don't Control, but Observe</h2>
		</Slide>
</Slide>
