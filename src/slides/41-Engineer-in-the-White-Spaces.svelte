<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 41. Engineer in the White Spaces"><div class="titlepage"><div><div><h1 class="title"><a id="engineer_in_the_white_spaces"/>Chapter 41. Engineer in the White Spaces</h1></div></div></div><div class="epigraph"><p>Michael Nygard wrote Release It! Design and Deploy
      Production-Ready Software (Pragmatic Bookshelf), which won a Jolt
      Productivity award in 2008. His other writings can be found at <a class="ulink" href="http://www.michaelnygard.com/blog">http://www.michaelnygard.com/blog</a>.<a class="indexterm" id="IDX-CHP-41-0236"/></p><div class="attribution"><span>—<span class="attribution">Michael Nygard</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject41_d1e2446"/><img alt="image with no caption" src="/images/id2698225/OEBPS/httpatomoreillycomsourceoreillyimages251910.png.jpg"/></div></div><p><span class="strong"><strong>A SYSTEM CONSISTS OF INTERDEPENDENT
    PROGRAMS</strong></span>. We call the arrangement of these programs and their
    relationships <span class="emphasis"><em>architecture</em></span>. When we diagram these
    systems, we often represent individual programs or servers as simplistic
    little rectangles, connected by arrows.</p><p>One little arrow might mean, "Synchronous request/reply using
    SOAP-XML over HTTP." That's quite a lot of information for one glyph to
    carry. There's not usually enough room to write all that, so we label the
    arrow with either "XML over HTTP" from an internal perspective, or "SKU
    Lookup" for the external perspective.</p><p>That arrow bridging programs looks like a direct contact, but it
    isn't. The white space between the boxes is filled with hardware and
    software components. This substrate may contain:</p><div class="informaltable"><table style="border-collapse: collapse;border-top: 0.5pt solid ; border-bottom: 0.5pt solid ; border-left: 0.5pt solid ; border-right: 0.5pt solid ; "><colgroup><col/><col/></colgroup><tbody><tr><td style="text-align: left" valign="top">
              <div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>Network interface cards</p></li><li class="listitem"><p>Network switches</p></li><li class="listitem"><p>Firewalls</p></li><li class="listitem"><p>IDS and IPS</p></li><li class="listitem"><p>Message queues or brokers</p></li><li class="listitem"><p>XML transformation engines</p></li><li class="listitem"><p>FTP servers</p></li></ul></div>
            </td><td style="text-align: left" valign="top">
              <div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>"Landing zone" tables</p></li><li class="listitem"><p>Metro-area SoNET rings</p></li><li class="listitem"><p>MPLS gateways</p></li><li class="listitem"><p>Trunk lines</p></li><li class="listitem"><p>Oceans</p></li><li class="listitem"><p>Cable-finding fishing trawlers</p></li></ul></div>
            </td></tr></tbody></table></div><p>There will always be four or five computers between program A and B,
    running their software for packet switching, traffic analysis, routing,
    threat analysis, and so on. As the architect bridging those programs, you
    must consider this substrate.</p><p>I saw one arrow labeled "Fulfillment". One server was inside my
    client's company, the other server was in a different one. That arrow,
    critical to customer satisfaction, unpacked a chain of events that
    resembled a game of "Mousetrap" more than a single interface. Messages
    went to message brokers that dumped to files, which were picked up by a
    periodic FTP job, and so on. That one "interface" had more than 20
    steps.</p><p>It's essential to understand the static and dynamic loads that arrow
    must carry. Instead of just "SOAP-XML over HTTP," that one little arrow
    should also say, "Expect one query per HTTP request and send back one
    response per HTTP reply. Expect up to 100 requests per second, and deliver
    responses in less than 250 milliseconds 99.999% of the time."</p><p>There's more we need to know about that arrow:</p><div class="itemizedlist"><ul class="itemizedlist"><li class="listitem"><p>What if the caller hits it too often? Should the receiver drop
        requests on the floor, refuse politely, or make the best effort
        possible?</p></li><li class="listitem"><p>What should the caller do when replies take more than 250
        milliseconds? Should it retry the call? Should it wait until later, or
        assume the receiver has failed and move on without that
        function?</p></li><li class="listitem"><p>What happens when the caller sends a request with version 1.0 of
        the protocol and gets back a reply in version 1.1? What if it gets
        back some HTML instead of XML? Or an MP3 file instead of XML?</p></li><li class="listitem"><p>What happens when one end of the interface disappears for a
        while?</p></li></ul></div><p>Answering these questions is the essence of engineering the white
    spaces.</p></div></p>
</Slide>
		<Slide>
				<h2>41. Engineer in the White Spaces</h2>
		</Slide>
</Slide>
