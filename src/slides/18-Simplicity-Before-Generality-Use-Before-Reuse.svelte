<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 18. Simplicity Before Generality, Use Before Reuse"><div class="titlepage"><div><div><h1 class="title"><a id="simplicity_before_generality_comma_use"/>Chapter 18. Simplicity Before Generality, Use Before Reuse</h1></div></div></div><div class="epigraph"><p>Kevlin Henney is an independent consultant and trainer. His work
      focuses on patterns and architecture, programming techniques and
      languages, and development process and practice. He is coauthor of
      <span class="emphasis"><em>A Pattern Language for Distributed Computing</em></span> and
      <span class="emphasis"><em>On Patterns and Pattern Languages</em></span> (both from
      Wiley).<a class="indexterm" id="IDX-CHP-18-0087"/></p><div class="attribution"><span>—<span class="attribution">Kevlin Henney</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject18_d1e1068"/><img alt="image with no caption" src="/images/id2705654/OEBPS/httpatomoreillycomsourceoreillyimages251922.png.jpg"/></div></div><p><span class="strong"><strong>A COMMON PROBLEM IN COMPONENT
    FRAMEWORKS</strong></span>, class libraries, foundation services, and other
    infrastructure code is that many are designed to be general purpose
    without reference to concrete applications. This leads to a dizzying array
    of options and possibilities that are often unused, misused, or just not
    useful. Most developers work on specific systems: the quest for unbounded
    generality rarely serves them well (if at all). The best route to
    generality is through understanding known, specific examples and focusing
    on their essence to find an essential common solution. Simplicity through
    experience rather than generality through guesswork.</p><p>Favoring simplicity before generality acts as a tiebreaker between
    otherwise equally viable design alternatives. When there are two possible
    solutions, favor the one that is simpler and based on concrete need rather
    than the more intricate one that boasts of generality. Of course, it is
    entirely possible (and more than a little likely) that the simpler
    solution will turn out to be the more general one in practice. And if that
    doesn't turn out to be the case, it will be easier to change the simpler
    solution to what you now know you need than to change the "general" one
    that turns out not to be quite general enough in the right way.<a class="indexterm" id="IDX-CHP-18-0088"/></p><p>Although well meant, many things that are designed just to be
    general purpose often end up satisfying no purpose. Software components
    should, first and foremost, be designed for use and to fulfill that use
    well. Effective generality comes from understanding, and understanding
    leads to simplification.</p><p>Generalization can allow us to reduce a problem to something more
    essential, resulting in an approach that embodies regularity across known
    examples, a regularity that is crisp, concise, and well grounded. However,
    too often generalization becomes a work item in itself, pulling in the
    opposite direction, adding to the complexity rather than reducing it. The
    pursuit of speculative generality often leads to solutions that are not
    anchored in the reality of actual development. They are based on
    assumptions that later turn out to be wrong, offer choices that later turn
    out not to be useful, and accumulate baggage that becomes difficult or
    impossible to remove, thereby adding to the accidental complexity
    developers and future architects must face.</p><p>Although many architects value generality, it should not be
    unconditional. People do not on the whole pay for (or need) generality:
    they tend to have a specific situation, and it is a solution to that
    specific situation that has value. We can find generality and flexibility
    in trying to deliver specific solutions, but if we weigh anchor and forget
    the specifics too soon, we end up adrift in a sea of nebulous
    possibilities, a world of tricky configuration options, overburdened (not
    just overloaded) parameter lists, long-winded interfaces, and
    not-quite-right abstractions. In pursuit of arbitrary flexibility, you can
    often lose valuable properties—accidental or intended—of alternative,
    simpler designs.</p></div></p>
</Slide>
		<Slide>
				<h2>18. Simplicity Before Generality, Use Before Reuse</h2>
		</Slide>
</Slide>
