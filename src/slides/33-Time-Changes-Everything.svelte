<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 33. Time Changes Everything"><div class="titlepage"><div><div><h1 class="title"><a id="time_changes_everything"/>Chapter 33. Time Changes Everything</h1></div></div></div><div class="epigraph"><p>Philip Nelson is a technology generalist whose career began in
      hardware; moved to networks, systems, and administration; and finally
      changed to software development and architecture, where he found the
      most interesting things were going on. He has worked on software
      problems in transportation, finance, manufacturing, marketing, and many
      infrastructure-related areas.<a class="indexterm" id="IDX-CHP-33-0125"/></p><div class="attribution"><span>—<span class="attribution">Philip Nelson</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject33_d1e1756"/><img alt="image with no caption" src="/images/id2707797/OEBPS/httpatomoreillycomsourceoreillyimages251938.png.jpg"/></div></div><p><span class="strong"><strong>ONE OF THE THINGS</strong></span> I've been most
    entertained by as the years have gone by is observing what things have
    lasted and what haven't. So many patterns, frameworks, paradigm changes,
    and algorithms—all argued for with passion by smart people, thinking of
    the long term, balancing all the known issues—have not warranted more than
    a yawn over the long haul. Why? What is history trying to tell us?</p><div class="sect1"><div class="titlepage"><div><div><h1 class="title"><a id="pick_a_worthy_challenge-id1"/></h1></div></div></div><div class="sect2" title="Pick a Worthy Challenge"><div class="titlepage"><div><div><h2 class="title"><a id="pick_a_worthy_challenge"/>Pick a Worthy Challenge</h2></div></div></div><p>This one is tricky for a software architect. Challenges or
        problems are given to us, so we don't have the luxury of choosing,
        right? It's not that simple. First of all, we often make the mistake
        of believing that we can't influence what we are asked to do. Usually
        we can, but it gets us out of our comfort zone in the technology
        space. There are dragons there when we don't choose to do the right
        things. Time passes, we have worked diligently and hard solving the
        requested challenge, and in the end it doesn't matter: we didn't do
        what was really needed and our work is wasted. Over time, a good
        solution to the right challenge will probably outlast all
        others.<a class="indexterm" id="IDX-CHP-33-0126"/><a class="indexterm" id="IDX-CHP-33-0127"/></p></div><div class="sect2" title="Simple Rules"><div class="titlepage"><div><div><h2 class="title"><a id="simple_rules"/>Simple Rules</h2></div></div></div><p>We say it to ourselves: keep it simple, stupid. We say it, but
        we don't do it. We don't do it because we don't have to. We are smart
        and we can handle some complexity and easily justify it because it
        adds agility to our design, because it is more elegant to our
        aesthetic sensibilities, because we believe we can anticipate the
        future. Then time passes; you walk away from the project for a year or
        more. When you come back to it, you almost always wonder why you did
        what you did. If you had to do it all over again, you would probably
        do it differently. Time does this to us. It makes us look silly. It is
        good to realize this early, get over yourself, and really try to learn
        what simple means in the lens that only time can grind.</p></div><div class="sect2" title="Be Happy with That Old Stuff"><div class="titlepage"><div><div><h2 class="title"><a id="be_happy_with_that_old_stuff"/>Be Happy with That Old Stuff</h2></div></div></div><p>Architects love to search for the "one true way": the
        methodology or school of thought that provides the predictability we
        crave and the clear answers that always seem just out of reach. The
        problem is that whatever guiding light you have in one year will
        probably not match the guiding light you have in a couple of years,
        much less a decade later. As you look back, you will always be looking
        at designs that don't match your current expectations. Learn to
        embrace that old stuff, and resist the temptation to think you should
        go back and "fix" it. Was the solution an appropriate one for the
        problem? Did it solve the needs of the problem? Keep these as your
        measure—you will be a lot happier.<a class="indexterm" id="IDX-CHP-33-0128"/><a class="indexterm" id="IDX-CHP-33-0129"/><a class="indexterm" id="IDX-CHP-33-0130"/><a class="indexterm" id="IDX-CHP-33-0131"/><a class="indexterm" id="IDX-CHP-33-0132"/><a class="indexterm" id="IDX-CHP-33-0133"/><a class="indexterm" id="IDX-CHP-33-0134"/><a class="indexterm" id="IDX-CHP-33-0135"/><a class="indexterm" id="IDX-CHP-33-0136"/><a class="indexterm" id="IDX-CHP-33-0137"/><a class="indexterm" id="IDX-CHP-33-0138"/><a class="indexterm" id="IDX-CHP-33-0139"/><a class="indexterm" id="IDX-CHP-33-0140"/><a class="indexterm" id="IDX-CHP-33-0141"/><a class="indexterm" id="IDX-CHP-33-0142"/><a class="indexterm" id="IDX-CHP-33-0143"/><a class="indexterm" id="IDX-CHP-33-0144"/><a class="indexterm" id="IDX-CHP-33-0145"/><a class="indexterm" id="IDX-CHP-33-0146"/><a class="indexterm" id="IDX-CHP-33-0147"/><a class="indexterm" id="IDX-CHP-33-0148"/><a class="indexterm" id="IDX-CHP-33-0149"/><a class="indexterm" id="IDX-CHP-33-0150"/><a class="indexterm" id="IDX-CHP-33-0151"/><a class="indexterm" id="IDX-CHP-33-0152"/><a class="indexterm" id="IDX-CHP-33-0153"/><a class="indexterm" id="IDX-CHP-33-0154"/><a class="indexterm" id="IDX-CHP-33-0155"/><a class="indexterm" id="IDX-CHP-33-0156"/><a class="indexterm" id="IDX-CHP-33-0157"/><a class="indexterm" id="IDX-CHP-33-0158"/><a class="indexterm" id="IDX-CHP-33-0159"/><a class="indexterm" id="IDX-CHP-33-0160"/><a class="indexterm" id="IDX-CHP-33-0161"/><a class="indexterm" id="IDX-CHP-33-0162"/><a class="indexterm" id="IDX-CHP-33-0163"/><a class="indexterm" id="IDX-CHP-33-0164"/><a class="indexterm" id="IDX-CHP-33-0165"/><a class="indexterm" id="IDX-CHP-33-0166"/><a class="indexterm" id="IDX-CHP-33-0167"/><a class="indexterm" id="IDX-CHP-33-0168"/><a class="indexterm" id="IDX-CHP-33-0169"/><a class="indexterm" id="IDX-CHP-33-0170"/><a class="indexterm" id="IDX-CHP-33-0171"/><a class="indexterm" id="IDX-CHP-33-0172"/><a class="indexterm" id="IDX-CHP-33-0173"/><a class="indexterm" id="IDX-CHP-33-0174"/><a class="indexterm" id="IDX-CHP-33-0175"/><a class="indexterm" id="IDX-CHP-33-0176"/><a class="indexterm" id="IDX-CHP-33-0177"/><a class="indexterm" id="IDX-CHP-33-0178"/><a class="indexterm" id="IDX-CHP-33-0179"/><a class="indexterm" id="IDX-CHP-33-0180"/><a class="indexterm" id="IDX-CHP-33-0181"/><a class="indexterm" id="IDX-CHP-33-0182"/><a class="indexterm" id="IDX-CHP-33-0183"/><a class="indexterm" id="IDX-CHP-33-0184"/><a class="indexterm" id="IDX-CHP-33-0185"/><a class="indexterm" id="IDX-CHP-33-0186"/><a class="indexterm" id="IDX-CHP-33-0187"/><a class="indexterm" id="IDX-CHP-33-0188"/><a class="indexterm" id="IDX-CHP-33-0189"/><a class="indexterm" id="IDX-CHP-33-0190"/><a class="indexterm" id="IDX-CHP-33-0191"/><a class="indexterm" id="IDX-CHP-33-0192"/><a class="indexterm" id="IDX-CHP-33-0193"/><a class="indexterm" id="IDX-CHP-33-0194"/><a class="indexterm" id="IDX-CHP-33-0195"/><a class="indexterm" id="IDX-CHP-33-0196"/><a class="indexterm" id="IDX-CHP-33-0197"/><a class="indexterm" id="IDX-CHP-33-0198"/><a class="indexterm" id="IDX-CHP-33-0199"/><a class="indexterm" id="IDX-CHP-33-0200"/><a class="indexterm" id="IDX-CHP-33-0201"/><a class="indexterm" id="IDX-CHP-33-0202"/><a class="indexterm" id="IDX-CHP-33-0203"/><a class="indexterm" id="IDX-CHP-33-0204"/><a class="indexterm" id="IDX-CHP-33-0205"/><a class="indexterm" id="IDX-CHP-33-0206"/><a class="indexterm" id="IDX-CHP-33-0207"/><a class="indexterm" id="IDX-CHP-33-0208"/><a class="indexterm" id="IDX-CHP-33-0209"/><a class="indexterm" id="IDX-CHP-33-0210"/><a class="indexterm" id="IDX-CHP-33-0211"/><a class="indexterm" id="IDX-CHP-33-0212"/><a class="indexterm" id="IDX-CHP-33-0213"/><a class="indexterm" id="IDX-CHP-33-0214"/><a class="indexterm" id="IDX-CHP-33-0215"/><a class="indexterm" id="IDX-CHP-33-0216"/><a class="indexterm" id="IDX-CHP-33-0217"/><a class="indexterm" id="IDX-CHP-33-0218"/><a class="indexterm" id="IDX-CHP-33-0219"/><a class="indexterm" id="IDX-CHP-33-0220"/><a class="indexterm" id="IDX-CHP-33-0221"/><a class="indexterm" id="IDX-CHP-33-0222"/></p></div></div></div></p>
</Slide>
		<Slide>
				<h2>33. Time Changes Everything</h2>
		</Slide>
</Slide>
