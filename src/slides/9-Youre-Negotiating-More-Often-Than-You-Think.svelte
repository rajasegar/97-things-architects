<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 9. You're Negotiating More Often Than You Think"><div class="titlepage"><div><div><h1 class="title"><a id="you_apostrophy_re_negotiating_more_often"/>Chapter 9. You're Negotiating More Often Than You Think</h1></div></div></div><div class="epigraph"><p>Michael Nygard wrote Release It! Design and Deploy
      Production-Ready Software (Pragmatic Bookshelf), which won a Jolt
      Productivity award in 2008. His other writings can be found at <a class="ulink" href="http://www.michaelnygard.com/blog">http://www.michaelnygard.com/blog</a>.<a class="indexterm" id="IDX-CHP-9-0046"/></p><div class="attribution"><span>—<span class="attribution">Michael Nygard</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject9_d1e642"/><img alt="image with no caption" src="/images/id2698225/OEBPS/httpatomoreillycomsourceoreillyimages251910.png.jpg"/></div></div><p><span class="strong"><strong>WE'VE ALL BEEN HIT WITH
    BUDGETECTURE</strong></span>. That's when sound technology choices go out the
    window in favor of cost-cutting. The conversation goes something like
    this.<a class="indexterm" id="IDX-CHP-9-0047"/></p><p>"Do we really need X?" asks the project sponsor.</p><p>For "X", you can substitute nearly anything that's vitally necessary
    to make the system run: software licenses, redundant servers, offsite
    backups, or power supplies. It's always asked with a sort of paternalistic
    tone, as though the grown-up has caught us blowing all our pocket money on
    comic books and bubble gum, while the serious adults are trying to get on
    with buying more buckets to carry their profits around in.</p><p>The correct way to answer this is "Yes. We do." That's almost never
    the response.</p><p>After all, we're trained as engineers, and engineering is all about
    making trade-offs. We know good and well that you don't really need
    extravagances like power supplies, so long as there's a sufficient supply
    of hamster wheels and cheap interns in the data center. So instead of
    saying, "Yes. We do," we say something like, "Well, you could do without a
    second server, provided you're willing to accept downtime for routine
    maintenance and whenever a parity bit flips, causing a crash, but if we
    get error-checking parity memory then we get around that, so we just have
    to worry about the operating system crashing, which it does about every
    three-point-nine days, so we'll have to do nightly restart. The interns
    can do that whenever they get a break from the power-generating hamster
    wheels."</p><p>All of which might be completely true, but is utterly the wrong
    thing to say. The sponsor stopped listening right after the word
    "Well."</p><p>The problem is that you see your part as an engineering role, while
    your sponsor clearly understands he's engaged in a negotiation. We're
    looking for a collaborative solution-finding exercise; they're looking for
    a win-lose tactical maneuver. And in a negotiation, the last thing you
    want to do is make concessions on the first demand. In fact, the right
    response to the "do we really need" question is something like
    this:</p><p>"Without a second server, the whole system will come crashing down
    at least three times daily, particularly when it's under heaviest load or
    when you are doing a demo for the Board of Directors. In fact, we really
    need four servers so we can take one HA pair down independently at any
    time while still maintaining 100% of our capacity, even in case one of the
    remaining pair crashes unexpectedly."</p><p>Of course, we both know you don't really need the third and fourth
    servers. This is a counter-negotiating gambit to get the sponsor to change
    the subject to something else. You're upping the ante and showing that
    you're already running at the bare, dangerous, nearly irresponsible
    minimum tolerable configuration. And besides, if you do actually get the
    extra servers, you can certainly use one to make your QA environment match
    production, and the other will make a great build box.</p></div></p>
</Slide>
		<Slide>
				<h2>9. You're Negotiating More Often Than You Think</h2>
		</Slide>
</Slide>
