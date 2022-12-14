<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 77. Stable Problems Get High-Quality Solutions"><div class="titlepage"><div><div><h1 class="title"><a id="stable_problems_get_high-quality_solutio"/>Chapter 77. Stable Problems Get High-Quality Solutions</h1></div></div></div><div class="epigraph"><p>After a lifetime of playing with computers—starting with writing
      games in BASIC on the BBC computer and going on to such diverse elements
      as pascal, Mathematica, and using Labview to process hand-rolled
      databases made of raw text data files from experiments held together
      with sticky tape—Sam Gardiner stumbled into professional software
      development. He has been working in the software industry for six
      years.<a class="indexterm" id="IDX-CHP-77-0290"/></p><div class="attribution"><span>—<span class="attribution">Sam Gardiner</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject77_d1e4097"/><img alt="image with no caption" src="/images/id2719103/OEBPS/httpatomoreillycomsourceoreillyimages251988.png.jpg"/></div></div><p><span class="strong"><strong>REAL-WORLD PROGRAMMING</strong></span> is not
    about solving the problem that someone gives to you. In the computer
    science classroom, you must solve the binary-sort problem given to you. In
    the real world, the best architects don't solve hard problems, they work
    around them. The skill is in drawing boundaries around diffuse and diverse
    software problems so that they are stable and self-contained.</p><p>An architect should be able to look at a whole mess of concepts and
    data and process and separate them into smaller pieces or "chunks." The
    important thing about those problem chunks is that they are stable,
    allowing them to be solved by a system chunk that is finite and stable in
    scope. The problem chunks should be:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>Internally cohesive: the chunk is conceptually unified, so all
        of the tasks, data, and features are related</p></li><li class="listitem"><p>Well separated from other chunks: the chunks are conceptually
        normalized; there is little or no overlap between them</p></li></ul></div><p>The person who is excessively good at doing this may not even know
    that she is doing it, just as a person with a good sense of direction
    knows where she is. It just seems to make sense to her to break up the
    tasks, data, and features in a way that provides a nice edge or interface
    to the system. I'm not talking about the actual interfaces of an
    object-oriented language, but system boundaries.</p><p>For instance, a relational database management system has a very
    nice system boundary. It manages literally any type of data that can be
    serialized into a stream of bytes, and it can organize, search, and
    retrieve that data. Simple.</p><p>What is interesting is that if the problem is stable, then when it
    is solved, it is solved permanently. In five/fifty years' time you might
    want to slap a web/telepathic interface over it, but your core system
    won't need to change. The system is durable because the problem is
    durable.</p><p>Of course, the code needs to be pretty neat, but if the problem is
    neat, the code can be neat, as there are no special cases. And neat code
    is good because it is easy to test and easy to review, and that means that
    the implementation quality can be very high. As you don't have messy code,
    you can concentrate on things that are outside the domain of user-visible
    features like using reliable messaging or distributed transactions, or
    driving up performance by using multithreading or even low-level languages
    like assembly code. Because the problem isn't changing, you can
    concentrate on driving up the quality to the point where it is a
    feature.</p><p>A stable problem allows you to create a system with a stable design;
    stable design allows you to concentrate on making an application that has
    very high quality.</p></div></p>
</Slide>
		<Slide>
				<h2>77. Stable Problems Get High-Quality Solutions</h2>
		</Slide>
</Slide>
