<script>
 import Slide from '../lib/Slide.svelte';
 import Center from '../lib/Center.svelte';
 import LemonMilkHeading2 from '../lib/LemonMilkHeading2.svelte';
 import Head2 from '../lib/LemonMilk/Head2.svelte';
 import Head3 from '../lib/LemonMilk/Head3.svelte';
</script>
<Slide>
		<Slide>
				<Head3>Fast is not a requirement</Head3>
				<ul>
						<li>Neither is responsive</li>
						<li>Nor extensible</li>
				</ul>
		</Slide>
		<Slide>
				<LemonMilkHeading2>Primary reason</LemonMilkHeading2>
				<p>No objective way to tell if met</p>
				<p>Still users want them</p>
		</Slide>
		<Slide>
				<LemonMilkHeading2>Architect's Role</LemonMilkHeading2>
				<ul>
						<li>Help the system have these qualities</li>
						<li>Balance the inevitable conflicts & inconsistencies</li>
				</ul>
		</Slide>
		<Slide>
				<LemonMilkHeading2>Objective criteria</LemonMilkHeading2>
				<p>At the mercy of: </p>
				<ul>
						<li>Capricious users</li>
						<li>Obsessive programmers</li>
				</ul>
		</Slide>
		<Slide>
				<p>As with all requirements, we seek to write down these desires </p>
				<LemonMilkHeading2>Vague adjectives</LemonMilkHeading2>
				<ul>
						<li>Flexible</li>
						<li>Maintainable</li>
						<li>Usable</li>
				</ul>
		</Slide>
		<Slide>
				<p>Every case</p>
				<Head3>can be quantified & thresholds set</Head3>
		</Slide>
		<Slide>
				<Head2>If not done</Head2>
				<ul>
						<li>No basis for acceptance of the system</li>
						<li>Valuable guidance is stolen from its builders</li>
						<li>Vision is blurred for those architecting</li>
				</ul>
		</Slide>
		<Slide>
				<LemonMilkHeading2>Simple questions</LemonMilkHeading2>
				<ul>
						<li>How many?</li>
						<li>In what period?</li>
						<li>How often?</li>
						<li>How soon?</li>
						<li>Increasing or decreasing?</li>
						<li>At what rate?</li>
				</ul>
				<p>Can't be answered => Need is not understood</p>
		</Slide>

		<Slide>
				<p>Answers &rarr; Business case for the system</p>
				<p>If not:  </p>
				<Head2>hard thinking</Head2>
		</Slide>
		<Slide>
				<p>If the business hasn't (won't) tell you those numbers</p>
				<h4>Ask yourself why not</h4>
				<Head2>Go get them</Head2>
		</Slide>
		<Slide>
				<Head3>System needs to be "scalable"</Head3>
				<p>Ask where new users are going to come from & why?</p>
				<p>Ask how many and by when?</p>
		</Slide>
		<Slide>
				<Head2>Reject</Head2>
				<Head3>"Lots" and "soon"</Head3>
		</Slide>
		<Slide>
				<Head3>Uncertain quantitative criteria</Head3>
				<Center>
				<img src="/assets/images/uncertain-quantitative-criteria.jpg" alt="uncertain quantitative criteria"/>
				</Center>
		</Slide>

		<Slide>
				<p>Range cannot be given</p>
				<Head3>required behavior is not understood</Head3>
		</Slide>
		<Slide>
				<Head2>Architecture unfolds</Head2>
				<p>Checked against these criteria to see if it is in tolerance</p>
		</Slide>

		<Slide>
				<Head3>Performance drifts</Head3>
				<p>Valuable feedback is obtained</p>
		</Slide>

		<Slide>
				<p>Finding these ranges & checking against them</p>
				<Head3>Time-consuming & expensive business</Head3>
		</Slide>

		<Slide>
				<Head2>No one cares</Head2>
				<ul>
						<li>The System being performant</li>
						<li>Pay for performance trials</li>
						<li>More than likely performance doesn't matter</li>
				</ul>
		</Slide>

		<Slide>
				<Head3>Free to focus your architectural efforts</Head3>
				<p>Aspects of the system worth paying for</p>
		</Slide>

		<Slide>
				<ul>
						<li>Must respond to user input no more than 1500 ms</li>
						<li>Under normal load, avg response time 750 - 1250 ms</li>
						<li>Response time less than 500 ms => can't be distinguished => We won't pay  to go below</li>
				</ul>
				<Head3>Now, that's a requirement</Head3>
		</Slide>

		<Slide>
				<LemonMilkHeading2>Quantify</LemonMilkHeading2>
		</Slide>
</Slide>
