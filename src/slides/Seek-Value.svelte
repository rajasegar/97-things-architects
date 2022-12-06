<script>
 import Slide from '../lib/Slide.svelte';
 import Center from '../lib/Center.svelte';
 import Head2 from '../lib/Head2.svelte';
 import Head3 from '../lib/Head3.svelte';
</script>
<Slide>
		<Slide>
				<h3 class="bebrush">Viable solution <span class="text-yellow-500">x</span> Requirement</h3>
		</Slide>
		<Slide>
				<h2 class="bebrush">Classic Story</h2>
				<p>Harry Hillaker - Lead desinger of F-16 Falcon</p>
				<Center>
				<img src="/assets/images/F16.jpeg" alt="F16 Falcon"/>
				</Center>
				<ul>
						<li>Design a Mach 2-2.5 aircraft</li>
						<li><span class="text-yellow-500">Objective:</span> "Cheap" lightweight aircraft</li>
				</ul>
		</Slide>
		<Slide>
				<Head2>Why Mach 2.5?</Head2>
				<p>to be able to escape from combat</p>
		</Slide>
		<Slide>
				<h2 class="bebrush text-yellow-500">Real need on the table</h2>
				<ul>
						<li>Address the root problem</li>
						<li>Provide a working solution</li>
				</ul>
		</Slide>
		<Slide>
				<Head2>An agile aircraft</Head2>
				<ul>
						<li>High thrust-to-weight ratio</li>
						<li>Acceleration & Maneuverability</li>
						<li><span class="text-amber-500 font-bold">NOT</span> Maximum speed</li>
				</ul>
		</Slide>
		<Slide>
				<Head2>Asking for the intended value</Head2>
				<ul>
						<li>Address the real problem</li>
						<li>Provide a better & cheaper solution</li>
				</ul>
		</Slide>
		<Slide>
				<Head2>Focus on value</Head2>
				<ul>
						<li>Simplifies prioritization</li>
						<li>Most valuable requirements <span class="text-yellow-500 font-bold text-6xl">&rarr;</span> Driving requirements</li>
				</ul>
		</Slide>
		<Slide>
				<h2 class="bebrush text-yellow-500">Collaboration over contract</h2>
				<Center>
						<img src="/assets/images/agile-manifesto.png" alt="Agile manifesto" />
				</Center>
				<p>The Agile Manifesto</p>
		</Slide>
		<Slide>
				<Head2>The why question</Head2>
				<ul>
						<li>Arranging workshops & meetings</li>
						<li>Focus in on customer needs</li>
						<li>Help customer to answer the "why" question</li>
				</ul>
		</Slide>
		<Slide>
				<Head2>Answering the "why" question</Head2>
				<ul>
						<li>Difficult</li>
						<li>Tacit knowledge</li>
				</ul>
		</Slide>
		<Slide>
				<Head3>Avoid discussions about technical solution</Head3>
				<p>Customer's domain <span class="text-yellow-500 font-bold"> -- FOCUS --></span> Domain of software development</p>
		</Slide>
		<Slide>
				<h2 class="bebrush text-yellow-500">Seek value in the requested capabilities</h2>
		</Slide>
</Slide>

<style>
 img {
		 height: 400px;
 }
</style>
