<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 68. You Have to Understand Hardware, Too"><div class="titlepage"><div><div><h1 class="title"><a id="you_have_to_understand_hardware_comma_to"/>Chapter 68. You Have to Understand Hardware, Too</h1></div></div></div><div class="epigraph"><p>Kamal Wickramanayake is an IT and software architect who lives in
      Sri Lanka. He is TOGAF-certified by The Open Group.</p><div class="attribution"><span>—<span class="attribution">Kamal Wickramanayake</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject68_d1e3757"/><img alt="image with no caption" src="/images/id2718108/OEBPS/httpatomoreillycomsourceoreillyimages251978.png.jpg"/></div></div><p><span class="strong"><strong>FOR MANY SOFTWARE ARCHITECTS</strong></span>,
    hardware capacity planning is a topic that lies beyond their comfort zone,
    yet it remains an important part of the architect's job. There are a
    number of reasons why software architects often fail to properly consider
    hardware, but they mostly have to do with a lack of understanding and
    unclear requirements.</p><p>The primary reason we neglect hardware considerations is that we are
    focused on software and tend to ignore hardware demands. In addition, we
    are naturally isolated from hardware by high-level languages and software
    frameworks.<a class="indexterm" id="IDX-CHP-68-0285"/></p><p>Unclear requirements are also a factor, as they may change or may be
    poorly understood. As the architecture evolves, hardware considerations
    will also change. In addition, our clients may not understand or be able
    to predict the size of their own user base or system usage dynamics.
    Finally, hardware is constantly evolving. What we knew about hardware in
    the past does not apply today.</p><p>Without hardware expertise, predicting hardware configurations for
    systems to be developed is highly error prone. To compensate, some
    software architects use large safety factors. Such safety factors are
    generally not based on objective assessments or founded in any
    methodology. In most of the cases, this leads to excessive infrastructure
    capacities that will not be utilized even in periods of peak demand. As a
    result, clients' money is wasted on more hardware than a system will ever
    need.</p><p>The best defense against poor hardware planning is to work closely
    with an infrastructure architect. Infrastructure architects, unlike
    software architects, are specialists in hardware capacity planning, and
    they should be a part of your team. However, not every software architect
    has the luxury of working with an infrastructure architect. In such cases
    there are some things a software architect can do to mitigate errors when
    planning for hardware.</p><p>Drawing on your own past experience can help. You've implemented
    systems in the past, so you have some knowledge of hardware capacity
    planning—even if it was an afterthought at the time. You can also discuss
    the topic with your client and convince them to set aside funds for
    hardware capacity planning. Budgeting for capacity planning can be much
    more cost effective than buying more hardware than you need. In this case,
    horizontal scalability is the key—adding hardware as needed rather than
    overbuying in the beginning. To make a horizontal strategy work, software
    architects need to constantly measure capacity and isolate software
    components to execute in performance-predictable environments.</p><p>Hardware capacity planning is as important as software architecture,
    and it needs to be given a first-order priority whether you have an
    infrastructure architect on hand or not. Just as an architect is
    responsible for establishing the links between business demands and a
    software solution, she is responsible for envisioning the links between
    hardware and software.</p></div></p>
</Slide>
		<Slide>
				<h2>68. You Have to Understand Hardware, Too</h2>
		</Slide>
</Slide>
