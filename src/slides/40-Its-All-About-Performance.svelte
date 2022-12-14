<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 40. It's All About Performance"><div class="titlepage"><div><div><h1 class="title"><a id="it_apostrophy_s_all_about_performance"/>Chapter 40. It's All About Performance</h1></div></div></div><div class="epigraph"><p>Craig Russell is a practicing software architect specializing in
      object persistence and distributed systems. He currently works as a
      senior staff engineer at Sun Microsystems.</p><div class="attribution"><span>—<span class="attribution">Craig Russell</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject40_d1e2398"/><img alt="image with no caption" src="/images/id2714064/OEBPS/httpatomoreillycomsourceoreillyimages251944.png.jpg"/></div></div><p><span class="strong"><strong>IMAGINE A PERSONAL VEHICLE THAT IS
    ROOMY</strong></span>, comfortable, fuel efficient, inexpensive to produce, and
    98% recyclable. You want one? Sure. Everyone does. Just one problem: its
    top speed is 6 miles/hour (10 km/hour). Still want one? This small example
    demonstrates that performance is just as important as any other
    criterion.<a class="indexterm" id="IDX-CHP-40-0233"/></p><p>The reason many designers put performance at the bottom of their
    lists might be that computers are so much faster at computation than their
    human counterparts that the designers assume that the speed of the system
    will be acceptable. And if today's systems aren't fast enough, Moore's Law
    will take care of everything. But hardware speed is only part of the
    system.</p><p>Performance is sometimes thought of as a simple measurement of the
    time it takes for a system to respond to user input. But system designers
    must consider many aspects of performance, including performance of the
    analysts and programmers who implement the design; performance of the
    human interactions of the system; and performance of the noninteractive
    components.</p><p>Performance of the people building the system is often called
    productivity, and it is important because it directly affects the cost and
    schedule of the project. A team that delivers a project late and over
    budget has a lot of 'splainin' to do. Using tools and prebuilt components
    can dramatically affect how quickly the system can be built and start
    returning value.<a class="indexterm" id="IDX-CHP-40-0234"/></p><p>Performance of the human interactions is critical to acceptance of
    the system. Many factors of system design contribute to this aspect of
    performance, response time being perhaps the most obvious. But response
    time isn't the only factor. Just as important are intuitiveness of the
    interface and number of gestures required to achieve a goal, both of which
    directly affect performance.</p><p>More than response time per se, a good system specification will
    measure task time, defined as the time required to complete a
    domain-specific task, including all human interactions with the system. In
    addition to system response time, this measurement includes operator think
    time and operator data entry time, which are not under the control of the
    system. But including these times gives motivation to the proper design of
    the human interface. Proper attention to the way information is presented
    and the number of gestures required to complete the task will result in
    better human operational performance.<a class="indexterm" id="IDX-CHP-40-0235"/></p><p>Performance of the noninteractive components is equally important to
    the success of the system. For example, a "nightly" batch run that takes
    more than 24 hours to complete will result in an unusable system.
    Performance of the disaster recovery component is also a critical
    consideration. In case of total destruction of one part of the system, how
    quickly can operational status be restored, in order to allow normal
    business to resume?</p><p>When considering the implementation and operation of a successful
    system, architects and designers should always pay careful attention to
    performance.</p></div></p>
</Slide>
		<Slide>
				<h2>40. It's All About Performance</h2>
		</Slide>
</Slide>
