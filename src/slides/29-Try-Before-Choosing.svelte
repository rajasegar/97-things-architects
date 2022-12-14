<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 29. Try Before Choosing"><div class="titlepage"><div><div><h1 class="title"><a id="try_before_choosing"/>Chapter 29. Try Before Choosing</h1></div></div></div><div class="epigraph"><p>Erik Doernenburg is a technology principal at ThoughtWorks, Inc.,
      where he helps clients with the design and implementation of large-scale
      enterprise solutions.</p><div class="attribution"><span>—<span class="attribution">Erik Doernenburg</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject29_d1e1615"/><img alt="image with no caption" src="/images/id2707207/OEBPS/httpatomoreillycomsourceoreillyimages251936.png.jpg"/></div></div><p><span class="strong"><strong>CREATING AN APPLICATION REQUIRES MAKING MANY
    DECISIONS</strong></span>. Some might involve choosing a framework or library,
    while others revolve around the use of specific design patterns. In either
    case the responsibility for the decision generally lies with the architect
    on the team. A stereotypical architect might gather all the information
    that can be gathered, then mull over it for a while, and finally decree
    the solution from the ivory tower for it to be implemented by the
    developers. Not surprisingly, there is a better way.</p><p>In their work on lean development, Mary and Tom Poppendieck describe
    a technique for making decisions. They argue that we should delay
    commitment until the last responsible moment; that is, the moment at
    which, if the team does not make a decision, it is made for them—when
    inaction results in an outcome that is not (easily) reversible. This is
    prudent because the later a decision is made, the more information is
    available on which to base the decision. However, in many cases more
    information is not the same as enough information, and we also know that
    the best decisions are made in hindsight. What does this mean for the good
    architect?</p><p>The architect should constantly be on the lookout for decisions that
    will have to be made soon. Provided the team has more than a handful of
    developers and practices collective code ownership, the architect can,
    when such a decision point approaches, ask several developers to come up
    with a solution to the problem and go with it for a while. As the last
    responsible moment approaches, the team meets to assess the benefits and
    drawbacks of the different solutions. Usually, now with the benefit of
    hindsight, the best solution to the problem is apparent to everybody. The
    architect does not have to make the decision, he or she merely
    orchestrates the decision-making process.</p><p>This approach works for small decisions as well as for large ones.
    It can allow a team to figure out whether or not to use the Hibernate
    templates provided by the Spring framework, but it can equally answer the
    question of which JavaScript framework to use. The duration for which the
    different approaches evolve is obviously very dependent on the complexity
    of the decision.</p><p>Trying two or even more approaches to the same problem requires more
    effort than making a decision upfront and then just implementing one.
    However, chances are that an upfront decision leads to a solution that is
    later recognized to be suboptimal, leaving the architect with a dilemma:
    either the team rolls back the current implementation or it lives with the
    consequences, both of which result in wasted effort. Even worse, it is
    entirely possible that nobody on the team recognizes that the approach
    chosen is not the best one, because none of the alternatives was explored.
    In this case, effort is wasted without any chance of addressing the waste.
    After all, trying multiple approaches might be the least expensive
    option.</p></div></p>
</Slide>
		<Slide>
				<h2>29. Try Before Choosing</h2>
		</Slide>
</Slide>
