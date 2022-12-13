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
				<p>At the mercy of capricious users & obsessive programmers</p>
		</Slide>
		<Slide>
				<LemonMilkHeading2>Vague adjectives</LemonMilkHeading2>
				<ul>
						<li>Flexible</li>
						<li>Maintainable</li>
						<li>Usable</li>
				</ul>
		</Slide>
		<Slide>
				<p>Every case</p>
				<Head3>Phenomena can be quantified and thresholds set</Head3>
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
				<p>No answer => The need is not understood</p>
		</Slide>

		<Slide>
				<p>Answers &rarr; Business case for the system</p>
				<p>If not &rarr; Some hard thinking needs to be done</p>
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
				<LemonMilkHeading2>Quantify</LemonMilkHeading2>
		</Slide>
</Slide>
