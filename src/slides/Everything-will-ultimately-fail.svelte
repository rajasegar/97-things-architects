<script>
 import Slide from '../lib/Slide.svelte';
 import Center from '../lib/Center.svelte';
 import Head2 from '../lib/Head2.svelte';
 import Head3 from '../lib/Head3.svelte';
</script>
<Slide>
		<Slide>
				<Head2>Hardware is fallible</Head2>
				<Head3>so we add redundancy</Head3>
				<ul>
						<li>Survive individual failures</li>
						<li>Likelihood of at least one failure</li>
				</ul>
		</Slide>
		<Slide>
				<Head2>Software is fallible</Head2>
						<ul>
								<li>Applications made of software</li>
								<li>Vulnerable to failures</li>
								<li>Monitoring: tell us when apps fail</li>
								<li>Monitoring made of more software: it too is fallible</li>
						</ul>
		</Slide>
		<Slide>
				<Head2>Humans make mistakes</Head2>
				<p>We are fallible also</p>
		</Slide>
		<Slide>
				<Head2>Automation</Head2>
				<ul>
						<li>Removes: The Chance for an error of commission</li>
						<li>Increases: The Chance for an error of omission</li>
				</ul>
				<p>Range of situations</p>
		</Slide>
		<Slide>
				<p>Add monitoring to automation</p>
				<Head2>More software</Head2>
				<Head3>More opportunities for failures</Head3>
		</Slide>
		<Slide>
				<Head2>Networks</Head2>
				<ul>
						<li>Hardware</li>
						<li>Software</li>
						<li>Very long wires</li>
				</ul>
		</Slide>
		<Slide>
				<Head2>Unpredictable</Head2>
				<p>State space of a large network &rarr; Infinite</p>
		</Slide>
		<Slide>
				<Head2>Individual components may act deterministically</Head2>
				<h3 class="bebrush">but still produce essentially chaotic behavior</h3>
		</Slide>
		<Slide>
				<p>Every safety mechanism</p>
				<Head2>we employ to mitigate one kind of failure</Head2>
				<Head3>adds new failure modes.</Head3>

		</Slide>
		<Slide>
				<Head2>Three Mile Island accident</Head2>
				<Center>
						<img src="/assets/images/3-mile-island.webp" alt="Three Mile Island" />
				</Center>
				<ul>
						<li>Pressure relief value</li>
				<li>Safety mechanism meant to prevent failures</li>
				</ul>
		</Slide>
		<Slide>
				<p>Faced with the certainty of failure in our systems</p>
				<Head2>What can we do about it?</Head2>
		</Slide>
		<Slide>
				<Head2>Accept that</Head2>
				<p>Your system will have a variety of failure modes</p>
				<p>Deny that inevitability &rarr; You lose your power to control and contain</p>
		</Slide>
		<Slide>
				<Head2>Once you accept</Head2>
				<h3>Failures will happen</h3>
				<p>the ability to design your system's reaction to specific failures</p>
		</Slide>
		<Slide>
				<Head2>Crumple zones</Head2>
				<p>Areas designed to protect passengers by failing first</p>
				<Center>
						<img src="/assets/images/crumple-zones.webp" alt="Crumple zones"/>
				</Center>
				<p>Safe Failure modes</p>
				<ul>
						<li>Contain the damage</li>
						<li>Protect the rest of the system</li>
				</ul>
		</Slide>
		<Slide>
				<Head3>If you do not design your failure modes</Head3>
				<ul>
						<li>Unpredictable</li>
						<li>Usually dangerous</li>
				</ul>
		</Slide>
		<Slide>
				<h2 class="bebrush text-yellow-500">Everything will ultimately fail</h2>
		</Slide>
</Slide>

<style>
 img {
		 height: 250px;
 }
</style>
