<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 8. Everything Will Ultimately Fail"><div class="titlepage"><div><div><h1 class="title"><a id="everything_will_ultimately_fail"/>Chapter 8. Everything Will Ultimately Fail</h1></div></div></div><div class="epigraph"><p>Michael Nygard wrote Release It! Design and Deploy
      Production-Ready Software (Pragmatic Bookshelf), which won a Jolt
      Productivity award in 2008. His other writings can be found at <a class="ulink" href="http://www.michaelnygard.com/blog">http://www.michaelnygard.com/blog</a>.<a class="indexterm" id="IDX-CHP-8-0045"/></p><div class="attribution"><span>—<span class="attribution">Michael Nygard</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject8_d1e597"/><img alt="image with no caption" src="/images/id2698225/OEBPS/httpatomoreillycomsourceoreillyimages251910.png.jpg"/></div></div><p><span class="strong"><strong>HARDWARE IS FALLIBLE, SO WE ADD
    REDUNDANCY</strong></span>. This allows us to survive individual hardware
    failures, but increases the likelihood of having at least one failure
    present at any given time.</p><p>Software is fallible. Our applications are made of software, so
    they're vulnerable to failures. We add monitoring to tell us when the
    applications fail, but that monitoring is made of more software, so it too
    is fallible.</p><p>Humans make mistakes; we are fallible also. So, we automate actions,
    diagnostics, and processes. Automation removes the chance for an error of
    commission, but increases the chance of an error of omission. No automated
    system can respond to the same range of situations that a human
    can.</p><p>Therefore, we add monitoring to the automation. More software, more
    opportunities for failures.</p><p>Networks are built out of hardware, software, and very long wires.
    Therefore, networks are fallible. Even when they work, they are
    unpredictable because the state space of a large network is, for all
    practical purposes, infinite. Individual components may act
    deterministically, but still produce essentially chaotic behavior.</p><p>Every safety mechanism we employ to mitigate one kind of failure
    adds new failure modes. We add clustering software to move applications
    from a failed server to a healthy one, but now we risk "split-brain
    syndrome" if the cluster's network acts up.</p><p>It's worth remembering that the Three Mile Island accident was
    largely caused by a pressure relief value—a safety mechanism meant to
    prevent certain types of overpressure failures.</p><p>So, faced with the certainty of failure in our systems, what can we
    do about it?</p><p>Accept that, no matter what, your system will have a variety of
    failure modes. Deny that inevitability, and you lose your power to control
    and contain them. Once you accept that failures will happen, you have the
    ability to design your system's reaction to specific failures. Just as
    auto engineers create crumple zones—areas designed to protect passengers
    by failing first—you can create safe failure modes that contain the damage
    and protect the rest of the system.</p><p>If you do not design your failure modes, then you will get whatever
    unpredictable—and usually dangerous—ones happen to emerge.</p></div></p>
</Slide>
		<Slide>
				<h2>8. Everything Will Ultimately Fail</h2>
		</Slide>
</Slide>
