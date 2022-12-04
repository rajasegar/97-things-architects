<script>
 import Slide from '../lib/Slide.svelte';
</script>
<Slide>
		<Slide>
				<h2 class="bebrush text-yellow-500">Essential Complexity</h2>
				<p>Inherent Difficulty</p>
		</Slide>
		<Slide>
				<div class="grid grid-cols-2">
				<div class="place-items-center"> <img src="/assets/images/air-traffic.jpg" alt="Air traffic"/></div>
				<div>
						<ul>
								<li>Exact position - altitude, speed, direction and destination</li>
								<li>Real-time tracking</li>
								<li>Flight schedules - airport congestion</li>
								<li>Continuously changing environment</li>
								<li>Severe change in weather - entire schedule out of whack</li>
						</ul>
				</div>
				</div>
		</Slide>
		<Slide>
				<h2 class="bebrush text-yellow-500">Accidental Complexity</h2>
				<p>Things we feel we must build to mitigate essential complexity</p>

						<p>Example: Antiquated Air Traffic Control System</p>
						<p>Design to address essential complexity</p>
				<p>Introduces its own complexity</p>
				<p>So complex: Difficult to update</p>
		</Slide>
		<Slide>
				<h3 class="bebrush text-yellow-500">Accidental Complexity Disease</h3>
				<ul>
						<li>Frameworks</li>
						<li>Vendor Solutions</li>
				</ul>
		</Slide>
		<Slide>
				<h1 class="bebrush text-yellow-500">Useful</h1>
				<p>Frameworks - Specific problems</p>
		</Slide>
		<Slide>
				<h2 class="bebrush text-yellow-500">Over-engineered Frameworks</h2>
				<p>Add more complexity</p>
		</Slide>
		<Slide>
				<p>Developers are drawn to complexity</p>
		</Slide>
		<Slide>
				<p>Puzzle solving is fun</p>
				<p>Developers are problem solvers</p>
		</Slide>
		<Slide>
				<h3 class="bebrush text-yellow-500">Challenge</h3>
				<p>Removing accidental complexity while retaining the solution to the essential complexity</p>
		</Slide>
		<Slide>
				<ul>
						<li class="fragment">Prefer frameworks derived from working code</li>
						<li class="fragment">% of code directly addressing business problem</li>
						<li class="fragment">Wary eye on vendor driven solutions</li>
						<li class="fragment">Ensure the solution fits the problem</li>
				</ul>
		</Slide>
		<Slide>
				<h2 class="bebrush text-yellow-500">Architect's Duty</h2>
				<p>Solve problems inherent in essential complexity</p>
				<p>Without accidental complexity</p>
		</Slide>
<Slide>
		<h3 class="bebrush text-lime-500">Simplify Essential Complexity</h3>
		<h4 class="bebrush text-amber-500">Diminish Accidental Complexity</h4>
</Slide>
</Slide>

<style>
 img {
		 height: 500px;
 }
</style>
