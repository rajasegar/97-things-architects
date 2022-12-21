<script>
 import Slide from '../lib/Slide.svelte';
 import Head2 from '../lib/Cocogoose/Head2.svelte';
 import Head3 from '../lib/Cocogoose/Head3.svelte';
 import Center from '../lib/Center.svelte';
</script>

<Slide>
    <Slide bgColor="#fff">
        <h4 class="cocogoose text-yellow-900">Architect is a Bridge</h4>
        <Center>
            <img src="/assets/images/bridge-bg.jpg" alt="bridge"/>
        </Center> 
        <h3 class="cocogoose text-yellow-700"> The context of business enterprise application development</h3>
        <p>Between business & tech communities of an organization</p>
    </Slide> 
    <Slide>
        <Head2>Architect</Head2>
        <ul>
	          <li> Representing and protecting the interests of each party</li>
	          <li> Often mediating</li>
            <li> Allowing the business to drive</li>
        </ul>
        <Center><img src="/assets/images/mediator1.png" alt="Mediator"/></Center> 

    </Slide>
    <Slide bgImage="/assets/images/spot-light.jpeg" bgOpacity="50%">
        <Head2>The light </Head2> 
        <p>Business organization's objectives and operating realities</p>
        <p>Architect leads technology-oriented decision making</p>
    </Slide>
    <Slide>
        <Center>
            <img src="/assets/images/roi.png" height="400" alt="Roi"/>
            </Center>
        <Head2> Return on Investment</Head2>
        <ul>
            <li>Routinely plan for</li>
            <li>Articulate a specific & desired</li>
        </ul>
        <p>Before undertaking a software development initiative</p>
    </Slide> 
    <Slide>
        <Head3>Architect must understand</Head3>
        <ul>
            <li>Desired ROI</li>
            <li>By implication</li>
            <li>Limits of the value of the software initiative to the business</li>
        </ul> 
        <p> To avoid making technology decisions that could cause the opportunity to be outspent</p>
    </Slide>
    <Slide>
        <Head3> ROI - Major piece of objective context</Head3>
        <ul>
            <li>In the give-and-take converstations</li>
            <li>Value vs Cost of Delivery of a feature</li>
            <li>With the Dev team about technical design & implementation</li> 
        </ul>
    </Slide>

    <Slide>
        <Head3>Example</Head3>
        <p>The Architect must be careful</p>
        <ul><li> To represent the interests of the business to the Dev team</li>
        <li> By not agreeing to choose technology that has unacceptably costly licensing and support cost implications</li>
        <li>When the software is deployed into testing or production</li>
        </ul> 
    </Slide>

    <Slide>
        <p>Part of the challenge of</p>
        <Head3>Letting the Business "drive"</Head3> 
            <p> Providing enough quality information</p>
        <ul>
            <li>About the ongoing software development effort</li>
            <li> Back into the business</li>
            <li>To support good business decision making</li>
        </ul> 
    </Slide> 
    <Slide> <Head3> Transparency becomes crucial</Head3></Slide>
    <Slide>
        <Head3>Architect + Dev Management</Head3>
        <h4>Create & Nurture</h4>
        <p>The Means for regular, ongoing information feedback loops</p> 
        <Center>
        <img src="/assets/images/feedback-loop.png" alt="Feedback loop"/>
        </Center>
    </Slide> 
    <Slide>
        <p>Can be accomplished by a variety of:</p>
        <Head3> Lean Software Techniques</Head3>
        <ul> <li> Big visible charts</li>
            <li>Continuous integration</li>
            <li>Frequent releases of working software to the business starting early</li> 
        </ul>
    </Slide> 
    <Slide>
        <Head3>Software development is fundamentally a design activity</Head3>
        <p> Ongoing process of decision making until the developed system goes into production.
        </p> 
    </Slide>

    <Slide>
        <Head2>Appropriate</Head2>
        <h4 class="cocogoose text-yellow-600">Software developers to make many decisions</h4>
        <p>But usually not to make business decisions</p>
    </Slide>

    
		<Slide>
				<p>The extent business community </p>
						<Head3>fails to fulfill its responsibility</Head3>
						<ul>
								<li>Provide direction</li>
								<li>Answer questions</li>
								<li>Make business decisions</li>
						</ul>
						<p>Actually delegating the business decision making to Software Devs</p>
		</Slide>
		<Slide>
				<Head2>Macro-context</Head2>
				<p>Ongoing series of micro-decisions made by developers</p>
				<ul>
						<li>Communicating and protecting the sofware architecture & business objectives</li>
						<li>Ensure that developers do no make business decisions</li>
				</ul>
		</Slide>
		<Slide>
				<Head3>Technical decision making untethered</Head3>
				<ul>
						<li>Commitments</li>
						<li>Expectations</li>
						<li>Realities</li>
				</ul>
				<p>Articulated by business community - ongoing basis</p>

						<Head2>Costly speculation</Head2>
						<h4 class="cocogoose text-yellow-600">Unjustifiable expenditure of scarce resources</h4>

		</Slide>
		<Slide>
				<Head2>Long-term interests of Software Dev Team</Head2>
				<p>Best served when business drives</p>
		</Slide>
    <Slide>
        <Head2>Business Drives</Head2>  
    </Slide>
    
</Slide>

<style>
 img {
   height: 400px!important;
 }
</style>
