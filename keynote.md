---
layout: page
slide_id: 1
---

<div class="card">
	<div class="card-header text-white bg-inverse"><i class="fa fa-users mr-3" aria-hidden="true"></i>Keynote I</div>
	<div style="margin: 10px">
		<h5>Chaos to Cosmos: Orchestrating Complex Scientific Applications with Dynamic Runtime Systems</h5>
		<p>Hatem Ltaief, KAUST</p>
	<!---
        From the start, Legion was designed to be part of a larger software stack, with a distributed execution runtime
(i.e. Realm) below it, but also libraries, frameworks, and DSLs above it. Early successes with Legion came from
application code written directly to the Legion API, but more recently the vision of being an enabler for higher
levels of abstraction is coming to fruition. I will review several of these efforts, talk about their successes in 
scaling (whether to larger systems, larger workloads, or larger programmer audiences), and that will lead me into
discussion of some key challenges that are becoming more critical as this scaling continues.
<br><br>
Legion, and really all AMT systems, are at risk of becoming victims of their success. If anything, they are too good
at extracting parallelism from application code, and this manifests as increasing demands on the runtime portions
of these systems at larger scales. Much of the analysis and decision making being performed in real time (and
therefore with real overhead) is not actually contributing to improved performance because there was already
enough work to keep processors busy and data movement latencies hidden. I'll touch on past and current efforts
to attack this at the application level and in runtime implementation, but the best place in the stack to perform
optimizations like this (i.e. compilers) is severely underrepresented, and we should fix that.
-->
	</div>
</div>

<div class="card">
	<div class="card-header text-white bg-inverse"><i class="fa fa-users mr-3" aria-hidden="true"></i>Keynote II</div>
		<div style="margin: 10px">
            <h5>TBA</h5>
            <p>Alan Edelman, MIT</p>
	<!---
			<p>Alan Edelman, MIT</p>
			<h5>TBA</h5>
		<h5>Deep Codesign in the Post-Exascale Computing Era</h5>
		<p>Jeffrey Vetter, Oak Ridge National Laboratory, <a href="https://vetter.github.io/">https://vetter.github.io/</a></p>
		<p markdown="1">
			DOE has just deployed its first Exascale system at ORNL, so now is an appropriate time to revisit our Exascale predictions from over a decade ago 
			and think about post-Exascale. We are now seeing a Cambrian explosion of new technologies during this ‘golden age of architectures,’ making codesign of architectures 
			with software and applications more critical than ever. In this talk, I will revisit the Exascale trajectory, survey post-Exascale technologies, and discuss their implications 
			for both system design and software. As an example, I will describe Abisko, a new microelectronics codesign project, that focuses on designing a chiplet for analog spiking neural 
			networks using novel neuromorphic materials like electrochemical random access memory.
		</p>
	-->
    </div>
</div>


<div class="card">
	<div class="card-header text-white bg-inverse"><i class="fa fa-users mr-3" aria-hidden="true"></i>Keynote III</div>
		<div style="margin: 10px">
        <h5>Task-Graphs: Why aren't we all using them?</h5>
        <p>Christian Trott (SNL)</p>
	<p markdown="1">
	Task-Graphs are a very attractive concept to express complex algorithms, manage asynchronicity and expose available concurrency. However, very few HPC applications are written in terms of task-graphs.  In this talk I will provide reflections on what I believe some of the reasons are, based on the experience  gained with Kokkos adoption in the last decade. To ground the discussion, this talk will provide an overview of the Kokkos::Graph design - a Kokkos capability that despite being introduced 4 years ago, has found very little adoption. A comparison with CUDA Graphs will demonstrate design tradeoffs in this space, and help highlight  adoption hurdles and correctness pitfalls that are likely an important part of the reason why task-graphs are not more widely used. Last but not least the talk will touch on how the recently approved ISO C++ 26 Execution framework ("Senders and Receivers") can help overcome some of these adoption hurdles, and allow us to realize the promise of a task-graph based application design. 
    </p>
    </div>
</div>
