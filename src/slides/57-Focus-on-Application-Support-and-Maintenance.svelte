<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 57. Focus on Application Support and Maintenance"><div class="titlepage"><div><div><h1 class="title"><a id="focus_on_application_support_and_mainten"/>Chapter 57. Focus on Application Support and Maintenance</h1></div></div></div><div class="epigraph"><p>Mncedisi Kasper is a director of technology and strategy at Open
      Xcellence ICT Solutions, a South Africa-based company specializing in
      enterprise application integration and SAP (ABAP/XI) consultancy.</p><div class="attribution"><span>—<span class="attribution">Mncedisi Kasper</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject57_d1e3274"/><img alt="image with no caption" src="/images/id2716664/OEBPS/httpatomoreillycomsourceoreillyimages251962.png.jpg"/></div></div><p><span class="strong"><strong>THE SUPPORT AND MAINTENANCE OF AN
    APPLICATION</strong></span> should never, ever be an afterthought. Since over
    80% of an application's lifecycle is spent in maintenance, you should pay
    a lot of attention to the problems of support and maintenance when you're
    designing. Fail to heed this, and you'll watch with horror as your
    application stops being the architect's dream and becomes a vile beast
    that dies a horrible death and is forever remembered as a failure.</p><p>When most architects design applications, they think mainly of
    developers, who have IDEs and debuggers in place. If something goes wrong,
    highly skilled software engineers debug away and the bug is discovered.
    It's easy to think this way because most architects have spent most of
    their lives as developers rather than administrators. Unfortunately, the
    developer and the support guy have different skill sets, just as the
    development/testing environment and the production environment have
    different purposes.</p><p>Here are a few of the disadvantages that an administrator
    faces:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>An administrator can't resubmit a request message to reproduce
        the problem. When you're in production, you can't reissue a financial
        transaction against the "live" database to see what went wrong.</p></li><li class="listitem"><p>Once the application is in production, the pressure to fix bugs
        comes from customers and executives, not from the project manager and
        the testing team—and an angry CEO can be a lot more
        threatening.</p></li><li class="listitem"><p>Once you're in production, there is no debugger.</p></li><li class="listitem"><p>Once you're in production, deployment needs to be scheduled and
        co-ordinated. You can't take a production application down for a few
        minutes to test a bug fix.</p></li><li class="listitem"><p>The logging level is much higher in the development environment
        than in production.</p></li></ul></div><p>A few symptoms of this failure to plan for support are:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>Most problems require a developer's involvement.</p></li><li class="listitem"><p>The relationship between the development team and the support
        team is sour; the developers think the support team is a bunch of
        idiots.</p></li><li class="listitem"><p>The support team hates the new application.</p></li><li class="listitem"><p>The architect and development teams are spending a lot of time
        in production.</p></li><li class="listitem"><p>The application is restarted often as a way to resolve
        problems.</p></li><li class="listitem"><p>The administrators never have time to tune the system properly
        because they're always fighting fires.</p></li></ul></div><p>To ensure that your application succeeds once it's out of the
    developers' hands, you should:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>Understand that development and support require a different
        skill set.</p></li><li class="listitem"><p>Get a support lead as early in on the project as
        possible.</p></li><li class="listitem"><p>Make the support lead a core part of the team.</p></li><li class="listitem"><p>Involve a support lead with the planning for the application
        support.</p></li></ul></div><p>Design such that the learning curve for the support personnel is
    minimal. Traceability, auditing, and logging are crucial. When the
    administrators are happy, everybody is happy (especially your
    boss).</p></div></p>
</Slide>
		<Slide>
				<h2>57. Focus on Application Support and Maintenance</h2>
		</Slide>
</Slide>
