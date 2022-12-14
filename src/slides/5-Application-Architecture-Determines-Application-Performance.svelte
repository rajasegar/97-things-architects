<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 5. Application Architecture Determines Application Performance"><div class="titlepage"><div><div><h1 class="title"><a id="application_architecture_determines_appl"/>Chapter 5. Application Architecture Determines Application Performance</h1></div></div></div><div class="epigraph"><p>Randy Stafford is a practicing software professional with 20
      years' experience as a developer, analyst, architect, manager,
      consultant, and author/presenter.<a class="indexterm" id="IDX-CHP-5-0042"/></p><p>Currently for Oracle's middleware development A-Team, he engages
      globally for proof-of-concept projects, architecture reviews, and
      production crises with diverse customer organizations, specializing in
      grid, SOA, performance, HA, and JEE/ORM work.<a class="indexterm" id="IDX-CHP-5-0043"/></p><div class="attribution"><span>—<span class="attribution">Randy Stafford</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject5_d1e509"/><img alt="image with no caption" src="/images/id2613014/OEBPS/httpatomoreillycomsourceoreillyimages251904.png.jpg"/></div></div><p><span class="strong"><strong>APPLICATION ARCHITECTURE
    DETERMINES</strong></span> application performance. That might seem rather
    obvious, but real-world experience shows that it's not. For example,
    software architects frequently believe that simply switching from one
    brand of software infrastructure to another will be sufficient to solve an
    application's performance challenges. Such beliefs may be based on a
    vendor's benchmark trumpeting, say, 25% better performance than the
    closest competition's. But if the vendor's product performs an operation
    in three milliseconds while the competition's product takes four
    milliseconds, the 25% or one-millisecond advantage matters little in the
    context of a highly inefficient architecture at the root of an
    application's performance characteristics.</p><p>In addition to IT managers and vendor benchmarking teams, other
    groups of people—vendor support departments and authors of application
    performance management literature—recommend simply "tuning" the software
    infrastructure, by fiddling with memory allocations, connection pool
    sizes, thread pool sizes, and the like. But if the deployment of an
    application is insufficiently architected for the expected load, or if the
    application's functional architecture is too inefficient in its
    utilization of computing resources, then no amount of "tuning" will bring
    about the desired performance and scalability characteristics. Instead, a
    re-architecting of internal logic or deployment strategy, or both, will be
    required.</p><p>In the end, all vendor products and application architectures are
    constrained by the same fundamental principles of distributed computing
    and underlying physics: applications, and the products they use, run as
    processes on computers of limited capacity, communicating with one another
    via protocol stacks and links of nonzero latency. Therefore people need to
    appreciate that application architecture is the primary determinant of
    application performance and scalability. Those quality attributes cannot
    be miraculously improved with some silver-bullet switch of software
    brands, or infrastructure "tuning."Instead, improvements in those areas
    require the hard work of carefully considered (re-)architecting.</p></div></p>
</Slide>
		<Slide>
				<h2>5. Application Architecture Determines Application Performance</h2>
		</Slide>
</Slide>
