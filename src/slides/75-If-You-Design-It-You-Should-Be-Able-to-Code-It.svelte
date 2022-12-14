<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 75. If You Design It, You Should Be Able to Code It"><div class="titlepage"><div><div><h1 class="title"><a id="if_you_design_it_comma_you_should_be_abl"/>Chapter 75. If You Design It, You Should Be Able to Code It</h1></div></div></div><div class="epigraph"><p>Mike Brown is a lead software engineer for Software Engineering
      Professionals, Inc. (<a class="ulink" href="http://www.sep.com">http://www.sep.com</a>). He has
      13 years of experience in IT, including 8 years' experience developing
      enterprise solutions in a wide range of vertical markets. He is a
      founder of the Indianapolis Alt.NET user group, a charter member of the
      WPF Disciples, and organizer of the upcoming Indy Arc professional user
      group.<a class="indexterm" id="IDX-CHP-75-0289"/></p><div class="attribution"><span>—<span class="attribution">Mike Brown</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject75_d1e4029"/><img alt="image with no caption" src="/images/id2717536/OEBPS/httpatomoreillycomsourceoreillyimages251970.png.jpg"/></div></div><p><span class="strong"><strong>IN ARCHITECTURE</strong></span>, it's tempting to
    create elaborate designs and abstractions that elegantly address the
    problem at hand. It is even more tempting to sprinkle new technologies
    into the project. At the end of the day, someone has to implement your
    design, and the architectural acrobatics that you have the developers
    perform impact the project.</p><p>When designing the architecture for your project, you need to have a
    feel for the amount of effort necessary to implement each element of your
    design; if you've developed an element before, it will be much easier to
    estimate the effort required.</p><p>Don't use a pattern in your design that you haven't personally
    implemented before. Don't rely on a framework that you haven't coded
    against before. Don't use a server that you haven't configured before. If
    your architecture depends on design elements that you haven't personally
    used, there are a number of negative side effects:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>You will not have experienced the learning curve that your
        developers will have to face. If you don't know how long it takes to
        learn a new technology, you won't be able to give a good estimate on
        time to implement.</p></li><li class="listitem"><p>You will not know the pitfalls to avoid when using the elements.
        Inevitably, things will not go as well as the demo that the trained
        expert in the technology provided. If you haven't worked with the
        technology before, you will be blindsided when this happens.</p></li><li class="listitem"><p>You will lose the confidence of your developers. When they ask
        questions about the design and you aren't able to give solid answers,
        they will quickly lose confidence in you and your design.</p></li><li class="listitem"><p>You will introduce unnecessary risk. Not knowing these things
        can put a big question mark on key elements of the solution. No one
        wants to start a project with big, unnecessary risks hanging
        around.</p></li></ul></div><p>So how does one go about learning new frameworks, patterns, and
    server platforms? Well, that's another axiom in and of itself: before
    anything, an architect is a developer.</p></div></p>
</Slide>
		<Slide>
				<h2>75. If You Design It, You Should Be Able to Code It</h2>
		</Slide>
</Slide>
