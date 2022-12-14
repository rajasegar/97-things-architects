<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 87. Pay Down Your Technical Debt"><div class="titlepage"><div><div><h1 class="title"><a id="pay_down_your_technical_debt"/>Chapter 87. Pay Down Your Technical Debt</h1></div></div></div><div class="epigraph"><p>Burk Hufnagel has been creating positive user experiences since
      1978 and is a lead software architect at LexisNexis.<a class="indexterm" id="IDX-CHP-87-0305"/></p><div class="attribution"><span>—<span class="attribution">Burkhardt Hufnagel</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject87_d1e4523"/><img alt="image with no caption" src="/images/id2727521/OEBPS/httpatomoreillycomsourceoreillyimages252000.png.jpg"/></div></div><p><span class="strong"><strong>ON ANY PROJECT THAT IS IN
    PRODUCTION</strong></span> (i.e., it has customers that are using it), there
    will come a time when a change must be made; either a bug needs fixing, or
    a new feature must be added. At that point there are two possible choices:
    you can take the time needed to "do it right," or you can take one or more
    "shortcuts" and try to get the change out the door sooner.</p><p>Generally, the business people (sales/marketing and customers) will
    want the change made as quickly as possible, while the developers and
    testers will be more interested in taking the time to properly design,
    implement, and test the change before delivering it to the
    customers.</p><p>As the project's architect, you'll have to decide which makes more
    sense and then convince the decision makers to take your advice; and, as
    with most architectural issues, there is a tradeoff involved. If you
    believe the system is reasonably stable, then it may make sense to go the
    "quick and dirty" route and get the change into production quickly. That's
    fine, but you need to know that in doing so your project is incurring some
    "technical debt" that must be repaid later. Repayment, in this case, means
    going back and making the change in the way you would have if you'd had
    the time and resources to do it right the first time.<a class="indexterm" id="IDX-CHP-87-0306"/></p><p>So why the concern over making changes properly now versus later?
    It's because there's a hidden cost to making these quick and dirty fixes.
    For financial debts the hidden cost is called "interest," and most anyone
    with a credit card knows how expensive just paying the interest on a debt
    can be. For technical debt, interest takes the form of instability in the
    system, and increased maintenance costs due to the hacked-in changes and
    lack of proper design, documentation, and/or tests. And, like financial
    interest, regular payments must be made until the original debt is
    repaid.</p><p>Now that you understand a bit more about the true cost of technical
    debt, you might decide the price is too high and you can't afford the
    cost. But when it's a choice between having the developers get the fix out
    as quickly as possible or taking a severe financial hit, it generally
    makes sense to get the fix out quickly. So, take the hit and get the
    change into production ASAP, but don't stop there.</p><p>Once the fix is in production, have the developers go back and fix
    it properly so that it can be included in the next scheduled release. This
    is the equivalent of charging something on your credit card and then
    paying off the balance at the end of the month so you don't get charged
    interest. This way you can provide the fast changes the business needs,
    while keeping your project out of debtor's prison.</p></div></p>
</Slide>
		<Slide>
				<h2>87. Pay Down Your Technical Debt</h2>
		</Slide>
</Slide>
