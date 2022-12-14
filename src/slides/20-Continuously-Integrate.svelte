<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 20. Continuously Integrate"><div class="titlepage"><div><div><h1 class="title"><a id="continuously_integrate"/>Chapter 20. Continuously Integrate</h1></div></div></div><div class="epigraph"><p>Dave Bartlett is an enthusiastic software professional with more
      than 25 years' experience as a programmer, developer, architect,
      manager, consultant, and instructor. He currently works for clients
      through Commotion Technologies, Inc., a private consulting firm, and
      lectures at Penn State University's Graduate Engineering School in Great
      Valley, Pennsylvania. His main work efforts today are with the Federal
      Reserve Bank of Philadelphia, helping to design and build web, portal,
      and composite applications for use within the Federal Reserve System and
      the United States Treasury.<a class="indexterm" id="IDX-CHP-20-0089"/></p><div class="attribution"><span>—<span class="attribution">David Bartlett</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject20_d1e1133"/><img alt="image with no caption" src="/images/id2705927/OEBPS/httpatomoreillycomsourceoreillyimages251926.png.jpg"/></div></div><p><span class="strong"><strong>THE BUILD AS A "BIG BANG" EVENT</strong></span>
    in project development is dead. The architect, whether an application or
    enterprise architect, should promote and encourage the use of continuous
    integration methods and tools for every project.<a class="indexterm" id="IDX-CHP-20-0090"/></p><p>The term <span class="emphasis"><em>continuous integration</em></span> (CI) was first
    coined by Martin Fowler in a design pattern. CI refers to a set practices
    and tools that ensure automatic builds and testing of an application at
    frequent intervals, usually on an integration server specifically
    configured for these tasks. The convergence of unit testing practices and
    tools in conjunction with automated build tools makes CI a must for any
    software project today.</p><p>Continuous integration targets a universal characteristic of the
    software development process: the integration point between source code
    and running application. At this integration point the many pieces of the
    development effort come together and are tested. You have probably heard
    the phrase "build early and often," which was a risk-reduction technique
    to ensure there were no surprises at this point in development. "Build
    early and often" has now been replaced by CI, which includes the build but
    also adds features that improve communication and coordination within the
    development team.<a class="indexterm" id="IDX-CHP-20-0091"/></p><p>The most prominent part of a CI implementation is the build, which
    is usually automated. You have the ability to do a manual build, but
    builds can also be kicked off nightly or can be triggered by source code
    changes. Once the build is started, the latest version of the source code
    is pulled from the repository, and the CI tools attempts to build the
    project and then test it. Lastly, notification is sent out, detailing the
    results of the build process. These notifications can be sent in various
    forms including email or instant messages.</p><p>Continuous integration will provide a more stable and directed
    development effort. As an architect you will love it, but more important,
    your organization and your development teams will be more effective and
    efficient.</p></div></p>
</Slide>
		<Slide>
				<h2>20. Continuously Integrate</h2>
		</Slide>
</Slide>
