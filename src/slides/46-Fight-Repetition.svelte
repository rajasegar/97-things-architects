<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 46. Fight Repetition"><div class="titlepage"><div><div><h1 class="title"><a id="fight_repetition"/>Chapter 46. Fight Repetition</h1></div></div></div><div class="epigraph"><p>Niclas Nilsson is a software development coach, consultant,
      educator, and writer with a deep passion for the software development
      craft, and he loves good design and architecture. He is a cofounder of
      factor10 and the lead editor of the architecture community at
      InfoQ.<a class="indexterm" id="IDX-CHP-46-0255"/></p><div class="attribution"><span>—<span class="attribution">Niclas Nilsson</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject46_d1e2820"/><img alt="image with no caption" src="/images/id2705262/OEBPS/httpatomoreillycomsourceoreillyimages251918.png.jpg"/></div></div><p><span class="strong"><strong>ARE YOUR DEVELOPERS</strong></span> performing
    recurring tasks that need little thinking? Can you find recurring patterns
    in the code? Can you spot code that's been written copy-paste-modify
    style? If that's the case, your team is moving slower than it should and,
    oddly enough, you may be the cause.</p><p>Before explaining why, let's agree on a couple of truths about
    software development:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>Duplication is evil.</p></li><li class="listitem"><p>Repetitive work slows down development.</p></li></ul></div><p>As an architect, you set the tone. You've got the best overall grasp
    of the system and you probably wrote a trend-setting, end-to-end, vertical
    slice of the system that serves as an example for the team—an example that
    has been copied many times by now. Whenever a developer copies anything—be
    it a few lines of code, an XML file, or a class—that's a clear indication
    that something could be made simpler or even completely abstracted away.
    Most often, it's not the domain logic that is copied; it's the
    infrastructure code that just has to be there to make it work. For that
    reason, it's crucial that you can envision the effects your examples have.
    Any code and configuration in your examples will be the base for tens,
    hundreds, or maybe thousands of other slices of the system, which means
    you have to make sure that your code is clean, intention revealing, and
    containing nothing except what can't be abstracted away: the domain
    problem itself. As an architect, you need to be highly sensitive to any
    kind of repetitive patterns, since anything you write will (ironically) be
    repeated.</p><p>But that doesn't happen in your system, right? Take a look at that
    configuration file. What needs to be different if applied on another slice
    of the system, and what will stay the same? Look at a typical business
    layer method. Is there a pattern that shows up in other methods as well,
    containing things like transaction handling, logging, authentication, or
    auditing? How about the data access layer? Any code in there that will be
    the same except for names of entities and fields? Look broader. Can you
    find two or three lines of code that frequently seem to go together, and
    even though they operate on different objects, feel like the same thing?
    These are all examples of repetition. Repetition in code is something that
    developers eventually learn to filter out and ignore when reading the
    code, once they figure out where the interesting variabilities are found,
    but even if the developers get used to it, it slows them down. Code like
    that is clearly written for computers to execute, not for developers to
    read.</p><p>Your responsibility is to remove it. To do that, you may need to
    harvest frameworks, create better abstractions, perhaps ask the toolsmith
    to set up an aspect framework or write a few small code generators, but
    the repetition won't go away unless someone does something about
    it.</p><p>That someone is you.</p></div></p>
</Slide>
		<Slide>
				<h2>46. Fight Repetition</h2>
		</Slide>
</Slide>
