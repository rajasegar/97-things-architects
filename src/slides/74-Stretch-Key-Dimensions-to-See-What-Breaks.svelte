<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 74. Stretch Key Dimensions to See What Breaks"><div class="titlepage"><div><div><h1 class="title"><a id="stretch_key_dimensions_to_see_what_break"/>Chapter 74. Stretch Key Dimensions to See What Breaks</h1></div></div></div><div class="epigraph"><p>Stephen Jones designs solutions for Tier-1 Telco Billing and its
      related high-volume processes for companies such as Telstra and Optus in
      Australia, and the 1997 version of AT&amp;T in the U.S. This design work
      included the initial implementations of Telco billing systems, redesigns
      of post-bill dispute and fraud billing functions, and over two years
      managing 24/7 production support for Telstra.</p><div class="attribution"><span>—<span class="attribution">Stephen Jones</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject74_d1e3979"/><img alt="image with no caption" src="/images/id2718854/OEBPS/httpatomoreillycomsourceoreillyimages251986.png.jpg"/></div></div><p><span class="strong"><strong>AN APPLICATION'S DESIGN IS
    OUTLINED</strong></span> initially based on the specified business
    requirements, selected or existing technologies, performance envelope,
    expected data volumes, and the financial resources available to build,
    deploy, and operate it. The solution, whatever it is, will meet or exceed
    what is asked of it in the contemporary environment and is expected to run
    successfully (or it is not yet a solution).</p><p>Now take this solution and stretch the key dimensions to see what
    breaks.</p><p>This examination looks for limits in the design that will occur
    when, for example, the system becomes wildly popular and more customers
    use it, the products being processed increase their transaction counts per
    day, or six months of data must now be retained rather than the initially
    specified week. Dimensions are stretched individually and then in
    combination to tease out the unseen limits that might lie hidden in the
    initial design.</p><p>Stretching key dimensions allows an architect to validate a solution
    by:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>Understanding whether the planned infrastructure accommodates
        these increases, and where the limits are. If the infrastructure will
        break, this process identifies where it will break, which can be
        highlighted for the application's owner, or the planned infrastructure
        can be purchased with specific upgrade paths in mind.</p></li><li class="listitem"><p>Confirming that there are sufficient hours in the day to perform
        the processing at the expected throughput, with head room to
        accommodate "busy days" or "catch up" after an outage. A solution that
        cannot complete a day's processing in a day and relies on the weekend
        when things are quieter has no long-term future.</p></li><li class="listitem"><p>Validating that the data access choices that were made are still
        valid as the system scales. What might work for a week's worth of data
        may be unusable with six month's data loaded.</p></li><li class="listitem"><p>Confirming how the application's increased workload will be
        scaled across additional hardware (if required), and the transition
        path as the load increases. Working through the transition before the
        application is deployed can influence the data stored and its
        structure.</p></li><li class="listitem"><p>Confirming that the application can still be recovered if the
        data volumes are increased and/or the data is now split among an
        increased infrastructure.</p></li></ul></div><p>Based on this examination, elements of the design may be recognised
    as problems requiring redesign. The redesign will be cheaper whilst the
    design is still virtual, technical choices are not locked-in and the
    business data has yet to be stored in the repositories.</p></div></p>
</Slide>
		<Slide>
				<h2>74. Stretch Key Dimensions to See What Breaks</h2>
		</Slide>
</Slide>
