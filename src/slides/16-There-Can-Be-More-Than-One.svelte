<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 16. There Can Be More Than One"><div class="titlepage"><div><div><h1 class="title"><a id="there_can_be_more_than_one"/>Chapter 16. There Can Be More Than One</h1></div></div></div><div class="epigraph"><p>After many years as an amateur, Keith Braithwaite was first paid
      to write software in 1996. After that first job, maintaining a compiler
      built with lex and yacc, he progressed first to modelling microwave
      propagation for GSM network planning, then seasonal variations in demand
      for air freight, in C++. A move to consultancy (and Java) introduced him
      to CORBA and then EJB, and then what was called at the time
      "e-commerce." He is currently a principal consultant with Zuhlke and
      manages its Centre of Agile Practice.<a class="indexterm" id="IDX-CHP-16-0084"/></p><div class="attribution"><span>—<span class="attribution">Keith Braithwaite</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject16_d1e999"/><img alt="image with no caption" src="/images/id2698488/OEBPS/httpatomoreillycomsourceoreillyimages251912.png.jpg"/></div></div><p><span class="strong"><strong>IT SEEMS TO BE A NEVERENDING
    SOURCE</strong></span> of surprise and distress to system builders that one
    data model, one message format, one message transport—in fact, exactly one
    of any major architectural component, policy, or stance—won't serve all
    parts of the business equally well. Of course: an enterprise ("enterprise"
    is red flag #1) big enough to worry about how many different "Account"
    tables will impact system building next decade is most likely too big and
    diverse for one "Account" table to do the job anyway.</p><p>In technical domains we can force uniqueness. Very convenient for
    us. In business domains the inconsistent, multifaceted, fuzzy, messy world
    intrudes. Worse yet, business doesn't even deal with "the world," it deals
    with people's opinions about aspects of situations in parts of the world.
    One response is to deem the domain to be technical and apply a unique
    solution by fiat. But reality has been roughly defined as "that which does
    not go away when one stops believing in it" (Philip K. Dick), and the
    messiness always returns as the business evolves. Thus are born enterprise
    data teams, and so forth, who spend all their (very expensive) time trying
    to tame existential dread through DTD wrangling. Paying customers tend to
    find the level of responsiveness that comes from this somewhat
    unsatisfactory.</p><p>Why not face up to the reality of a messy world and allow multiple,
    inconsistent, overlapping representations, services, solutions? As
    technologists we recoil in horror from this. We imagine terrifying
    scenarios: inconsistent updates, maintenance overhead, spaghetti-plates of
    dependencies to manage. But let's take a hint from the world of data
    warehousing. The schemata data marts are often (relationally)
    denormalized, mix imported and calculated values arbitrarily, and present
    a very different view of the data than the underlying databases. And the
    sky does not fall because of the nonfunctional properties of a mart. The
    ETL process sits at the boundary of two very different worlds, typically
    transaction versus analytical processing. These have very different rates
    of update and query, very different throughput, different rates of change
    of design, perhaps very different volumes. This is the key: sufficiently
    different nonfunctional properties of a subsystem create a boundary across
    which managing inconsistent representations is tractable.<a class="indexterm" id="IDX-CHP-16-0085"/></p><p>Don't go duplicating representations, or having multiple transports
    just for the fun of it, but do always consider the possibility that
    decomposition of your system by nonfunctional parameters may reveal
    opportunities to allow diverse solutions to your customers'
    advantage.</p></div></p>
</Slide>
		<Slide>
				<h2>16. There Can Be More Than One</h2>
		</Slide>
</Slide>
