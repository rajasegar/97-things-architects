<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 15. Commit-and-Run Is a Crime"><div class="titlepage"><div><div><h1 class="title"><a id="commit-and-run_is_a_crime"/>Chapter 15. Commit-and-Run Is a Crime</h1></div></div></div><div class="epigraph"><p>Niclas Nilsson is a software development coach, consultant,
      educator, and writer with a deep passion for the software development
      craft, and he loves good design and architecture. He is a cofounder of
      factor10 and the lead editor of the architecture community at
      InfoQ.<a class="indexterm" id="IDX-CHP-15-0082"/></p><div class="attribution"><span>—<span class="attribution">Niclas Nilsson</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject15_d1e967"/><img alt="image with no caption" src="/images/id2705262/OEBPS/httpatomoreillycomsourceoreillyimages251918.png.jpg"/></div></div><p><span class="strong"><strong>IT'S LATE IN THE AFTERNOON</strong></span>. The
    team is churning out the last pieces of the new feature set for the
    iteration, and you can almost feel the rhythm in the room. John is in a
    bit of a hurry though. He's late for a date, but he manages to finish up
    his code, compile, and check in, and off he goes. A few minutes later, the
    red light turns on. The build is broken. John didn't have time to run the
    automated tests, so he made a commit-and-run and thereby left everybody
    else hanging. The situation is now changed and the rhythm is lost.
    Everyone now knows that if they do an update against the version control
    system, they will get the broken code onto their local machine as well,
    and since the team has a lot to integrate this afternoon to prepare for
    the upcoming demo, this is quite a disruption. John effectively put the
    team flow to a halt because now no integration can be done before someone
    takes the time to revert his changes.<a class="indexterm" id="IDX-CHP-15-0083"/></p><p>This scenario is way too common. Commit-and-run is a crime because
    it kills flow. It's one of the most common ways for a developer to try to
    save time for himself, and it ends up wasting other people's time and is
    downright disrespectful. Still, it happens everywhere. Why? Usually
    because it takes too long to build the system properly or to run the
    tests.</p><p>This is where you, the architect, come into play. If you've put a
    lot of effort into creating a flexible architecture where people can
    perform, taught the developers agile practices like test-driven
    development, and set up a continuous integration server, then you also
    want to nurture a culture where it's not all right to waste anybody else's
    time and flow in any way. To be able to get that, you need to make sure
    the system, among other things, has a sound architecture for automated
    testing, since it will change the behavior of the developers. If tests run
    fast, developers will run them more often, which itself is a good thing,
    but it also means that they won't leave their colleagues with broken code.
    If the tests are dependent on external systems or if they need to hit the
    database, re-engineer them so they can be run locally with mocks or stubs,
    or at the very least with an in-memory database, and let the build server
    run them in the slow way. People should not have to wait for computers,
    because if they have to, they will take shortcuts, which often causes
    problems for others instead.</p><p>Invest time in making the system fast to work with. It increases
    flow, lessens the reasons for working in silos, and in the end makes it
    possible to develop faster. Mock things, create simulators, lessen
    dependencies, divide the system in smaller modules, or do whatever you
    have to. Just make sure there's no reason to even think about doing a
    commit-and-run.</p></div></p>
</Slide>
		<Slide>
				<h2>15. Commit-and-Run Is a Crime</h2>
		</Slide>
</Slide>
