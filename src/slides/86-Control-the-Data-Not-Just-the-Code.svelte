<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 86. Control the Data, Not Just the Code"><div class="titlepage"><div><div><h1 class="title"><a id="control_the_data_comma_not_just_the_code"/>Chapter 86. Control the Data, Not Just the Code</h1></div></div></div><div class="epigraph"><p>Chad LaVigne is a solutions architect and technical hired gun for
      Baltimore-based TEKSystems, Inc. He works primarily in the Minneapolis
      area designing and implementing solutions utilizing Enterprise Java
      technologies.<a class="indexterm" id="IDX-CHP-86-0304"/></p><div class="attribution"><span>—<span class="attribution">Chad LaVigne</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject86_d1e4469"/><img alt="image with no caption" src="/images/id2716437/OEBPS/httpatomoreillycomsourceoreillyimages251958.png.jpg"/></div></div><p><span class="strong"><strong>SOURCE CODE CONTROL AND CONTINUOUS
    INTEGRATION</strong></span> are excellent tools for managing the application
    build and deployment process. Along with source code, schema and data
    changes are often a significant part of this process and thus warrant
    similar controls. If your build and deployment process includes a list of
    elaborate steps required for data updates, beware. These are the lists
    that always have you crossing your fingers. They look something like
    this:</p><div class="orderedlist"><ol class="orderedlist"><li class="listitem"><p>Create a list of scripts that need to be run, in order.</p></li><li class="listitem"><p>E-mail scripts to special database person.</p></li><li class="listitem"><p>Database person copies the scripts to a location where they're
        executed by a cron job.</p></li><li class="listitem"><p>Check script execution log and pray that all scripts ran
        successfully since you're not exactly sure what will happen if you
        rerun them.</p></li><li class="listitem"><p>Run validation scripts and spot-check the data.</p></li><li class="listitem"><p>Regression test the application and see what blows up.</p></li><li class="listitem"><p>Write scripts to insert missing data and fix blow-ups.</p></li><li class="listitem"><p>Repeat.</p></li></ol></div><p>OK, so that might be a slight exaggeration but it's not that far
    off. Many a project requires this type of acrobatic workflow for
    successful database migration. For some reason the data portion of the
    migration plan seems to be easily overlooked during architecture planning.
    As a result, it can become a brittle, manual process that gets bolted on
    as an afterthought.</p><p>This complex web-work creates many opportunities for process
    breakdown. To make matters worse, bugs caused by schema and data changes
    don't always get caught by unit tests as part of the nightly build report.
    They like to rear their ugly head in a loud, boisterous manner immediately
    after a build has been migrated. Database problems are usually tedious to
    reverse by hand and their solutions tend to be more difficult to validate.
    The value of a completely automated build process that is capable of
    restoring the database to a known state will never be more evident than
    when you're using it to fix an extremely visible issue. If you don't have
    the ability to drop the database and restore it to a state that is
    compatible with a specific build of the application, you are susceptible
    to the same type of problems you'd have if you couldn't back out a code
    change quickly.</p><p>Database changes shouldn't create a ripple in your build's
    time-space continuum. You need to be able to build the entire application,
    including the database, as one unit. Make data and schema management a
    seamless part of your automated build and testing process early on and
    include an undo button; it will pay large dividends. At best it will save
    hours of painful, high-stress problem solving after a late night blunder.
    At worst it will give your team the ability to confidently charge forward
    with refactoring of the data access layer.</p></div></p>
</Slide>
		<Slide>
				<h2>86. Control the Data, Not Just the Code</h2>
		</Slide>
</Slide>
