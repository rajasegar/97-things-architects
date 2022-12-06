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
				<Head2>What can we do about it?</Head2>
				<p>Faced with the certainty of failure in our systems</p>
		</Slide>
		<Slide>
				<Head2>Accept that, no matter what</Head2>
				<p>Your system will have a variety of failure modes</p>
				<p>Deny that inevitability &rarr; You lose your power to control and contain</p>
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
						<li>Happen to emerge</li>
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
