<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 23. Database As a Fortress"><div class="titlepage"><div><div><h1 class="title"><a id="database_as_a_fortress"/>Chapter 23. Database As a Fortress</h1></div></div></div><div class="epigraph"><p>Dan Chak is the director of software development at CourseAdvisor
      Inc., a <span class="emphasis"><em>Washington Post company. He is the author
      of</em></span> Enterprise Rails (<span class="emphasis"><em>O'Reilly</em></span>).</p><div class="attribution"><span>—<span class="attribution">Dan Chak</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject23_d1e1278"/><img alt="image with no caption" src="/images/id2706332/OEBPS/httpatomoreillycomsourceoreillyimages251930.png.jpg"/></div></div><p><span class="strong"><strong>THE DATABASE IS WHERE ALL OF THE
    DATA</strong></span>, both input by your employees and collected from your
    customers, resides. User interfaces, business and application logic, and
    even employees will come and go, but your data lasts forever.
    Consequently, enough cannot be said about the importance of building a
    solid data model from Day One.</p><p>The exuberance over agile techniques has left many thinking that
    it's fine, or even preferable, to design applications as you go. Gone are
    the days of writing complex, comprehensive technical designs up front! The
    new school says deploy early and often. A line of code in production is
    better than 10 in your head. It seems almost too good to be true, and
    where your data is concerned, it is.</p><p>While business rules and user interfaces do evolve rapidly, the
    structures and relationships within the data you collect often do not.
    Therefore, it is critical to have your data model defined right from the
    start, both structurally and analytically. Migrating data from one schema
    to another in situ is difficult at best, time consuming always, and error
    prone often. While you can suffer bugs temporarily at the application
    layer, bugs in the database can be disastrous. Finding and fixing a
    data-layer design problem does not restore your data once it has been
    corrupted.</p><p>A solid data model is one that guarantees security of today's data,
    but is also extensible for tomorrow's. Guaranteeing security means being
    impervious to bugs that will—despite your best efforts—be pervasive in an
    ever-changing application layer. It means enforcing referential integrity.
    It means building in domain constraints wherever they are known. It means
    choosing appropriate keys that help you ensure your data's referential
    integrity and constraint satisfaction. Being extensible for tomorrow means
    properly normalizing your data so that you can easily add architectural
    layers upon your data model later. It means not taking shortcuts.</p><p>The database is the final gatekeeper of your precious data. The
    application layer, which is by design ephemeral, cannot be its own
    watchdog. For the database to keep proper guard, the data model must be
    designed to reject data that does not belong, and to prevent relationships
    that do not make sense. Keys, foreign key relationships, and domain
    constraints, when described in a schema, are succinct, easy to understand
    and verify, and ultimately self-documenting. Domain rules encoded in the
    data model are also physical and persistent; a change to application logic
    does not wash them away.</p><p>To get the most out of a relational database—to make it a true part
    of the application as opposed to simply a storehouse for application
    data—you need to have a solid understanding of what you are building from
    the start. As your product evolves, so too will the data layer, but at
    each phase of its evolution, it should always maintain its status as
    Fortress. If you trust it and bestow upon it the heavy responsibility of
    trapping bugs from other layers of your application, you will never be
    disappointed.</p></div></p>
</Slide>
		<Slide>
				<h2>23. Database As a Fortress</h2>
		</Slide>
</Slide>
