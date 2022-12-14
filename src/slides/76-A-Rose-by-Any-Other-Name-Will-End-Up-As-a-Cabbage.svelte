<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 76. A Rose by Any Other Name Will End Up As a Cabbage"><div class="titlepage"><div><div><h1 class="title"><a id="a_rose_by_any_other_name_will_end_up_as"/>Chapter 76. A Rose by Any Other Name Will End Up As a Cabbage</h1></div></div></div><div class="epigraph"><p>After a lifetime of playing with computers—starting with writing
      games in BASIC on the BBC computer and going on to such diverse elements
      as pascal, Mathematica, and using Labview to process hand-rolled
      databases made of raw text data files from experiments held together
      with sticky tape—Sam Gardiner stumbled into professional software
      development. He has been working in the software industry for six
      years.</p><div class="attribution"><span>—<span class="attribution">Sam Gardiner</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject76_d1e4066"/><img alt="image with no caption" src="/images/id2719103/OEBPS/httpatomoreillycomsourceoreillyimages251988.png.jpg"/></div></div><p><span class="strong"><strong>I OVERHEARD SOME PEOPLE DECIDING</strong></span>
    that they need more layers in their architecture. They were right, as it
    happens, but going about it a little backward. They were attempting to
    create a framework that would contain the business logic. Rather than
    solving some specific problems they started with the idea that they want a
    framework that wraps the database up and produces objects. And it should
    use object-relational mapping. And messages. And web services. And it
    should do all sorts of cool stuff.</p><p>Unfortunately, since they didn't exactly know what cool stuff it
    would do, they didn't know what to call it. So they held a little
    competition to suggest a name. And that is the point at which you must
    recognise that you have a problem: if you don't know what a thing should
    be called, you cannot know what it is. If you don't know what it is, you
    cannot sit down and write the code.</p><p>In this particular case, a quick browse throughout the source
    control history revealed the depth of the problem. Of course, there were
    lots of empty interface "implementations"! And the really funny thing is
    that they had already changed the names three times with no actual code.
    When they started they called it ClientAPI—the "client" refers to the
    customers of the business, not client as in "client-server"—and the final
    version was called ClientBusinessObjects. Great name: vague, broad, and
    misleading.</p><p>Of course, in the end, a name is just a pointer. Once everyone
    involved knows that the name is just a name and not a design metaphor then
    you can all move on. However, if you can't agree on a name that is
    specific enough for you to know when it is wrong, then you might have some
    difficulty even getting started. Design is all about trying to fulfill
    intentions—e.g., fast, cheap, flexible—and names convey intentions.</p><p>If you can't name it, you can't write it. If you change the name
    three times, then you should stop until you know what you are trying to
    build.</p></div></p>
</Slide>
		<Slide>
				<h2>76. A Rose by Any Other Name Will End Up As a Cabbage</h2>
		</Slide>
</Slide>
