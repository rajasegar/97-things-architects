<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 53. Challenge Assumptions—Especially Your Own"><div class="titlepage"><div><div><h1 class="title"><a id="challenge_assumptions_-_especially_your"/>Chapter 53. Challenge Assumptions—Especially Your Own</h1></div></div></div><div class="epigraph"><p>Timothy High is a software architect with more than 15 years'
      experience with web, multitiered client-server, and
      application-integration technologies. He is currently working as a
      software architect for Sakonnet Technologies, a leader in Energy Trading
      and Risk Management (ETRM) software.<a class="indexterm" id="IDX-CHP-53-0267"/></p><div class="attribution"><span>—<span class="attribution">Timothy High</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject53_d1e3113"/><img alt="image with no caption" src="/images/id2715880/OEBPS/httpatomoreillycomsourceoreillyimages251954.png.jpg"/></div></div><p><span class="strong"><strong>WETHERN'S LAW OF SUSPENDED JUDGMENT
    STATES</strong></span> (in a rather tongue-in-cheek fashion) that "Assumption
    is the mother of all screw-ups." A more popular take on this would be,
    "Don't assume—it makes an 'ass' of 'u' and 'me'." But when you are dealing
    with assumptions that could cost thousands, if not millions, of dollars
    it's not always a laughing matter.<a class="indexterm" id="IDX-CHP-53-0268"/></p><p>Best practices in software architecture state that you should
    document the rationale behind each decision that is made, especially when
    that decision involves a tradeoff (performance versus maintainability,
    cost versus time-to-market, and so on). In more formal approaches, it is
    common to record along with each decision the context of that decision,
    including the "factors" that contributed to the final judgment. Factors
    may be functional or nonfunctional requirements, but they also may just be
    "facts" (or factoids...) that the decision-makers found important
    (technology constraints, available skill sets, the political environment,
    etc.).</p><p>This practice is valuable because listing these factors helps
    highlight assumptions that the architects may have that affect important
    decisions about the software being designed. Very often these assumptions
    are based on "historical reasons," opinion, developer lore, FUDs, or even
    "something I heard in the hallway":</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>"Open source is not reliable."</p></li><li class="listitem"><p>"Bitmap indexes are more trouble than they're worth."</p></li><li class="listitem"><p>"The customer would <span class="emphasis"><em>never</em></span> accept a page
        that takes five seconds to load."</p></li><li class="listitem"><p>"The CIO would reject anything that isn't sold by a major
        vendor."</p></li></ul></div><p>It is important to make these assumptions visible and explicit for
    the sake of posterity and for future re-evaluation. However, it is even
    more critical to make sure that any assumptions that aren't based on
    relevant empirical evidence (or a confirmation from the people involved,
    for political factors) be validated before a decision is finalized. What
    if customers can wait five seconds for critical reports if you provide a
    counter? In exactly what way is exactly which open source project
    unreliable? Have you tested the bitmap indexes on your data, using your
    application's transactions and queries?</p><p>And don't overlook the word "relevant." Something that was true in
    an older version of your software may not be true today. The performance
    of bitmap indexes in one version of Oracle may not be the same as in
    another. An older version of a library may have had security holes that
    have already been fixed. Your old reliable software vendor may be on its
    last legs financially. The technology landscape changes every day, and so
    do people. Who knows? Maybe your CIO has become a closet fan of
    Linux.</p><p>Facts and assumptions are the pillars on which your software will be
    built. Whatever they are, make sure the foundations are solid.</p></div></p>
</Slide>
		<Slide>
				<h2>53. Challenge Assumptions—Especially Your Own</h2>
		</Slide>
</Slide>
