---
layout: page
slide_id: 1
---

<div class="card">
    <div class="card-header text-white bg-inverse"><i class="fa fa-users mr-3" aria-hidden="true"></i>Keynote I</div>
    <div style="margin: 10px">
        <h5>Improving the HPC experience, did Julia get it right or will AI hide the problem (or both)?</h5>
        <p>Alan Edelman, MIT</p>
        <p markdown="1">
            For years I was sad that not enough hard work went into making HPC much easier on the human, and much more portable. I kind of felt that there was too much chasing "machoflops" and not enough software engineering that would result in bringing more programmers to HPC. My benchmark was how many undergraduates are using HPC for interesting projects. Another observation was that it seemed infrastructure was rarely funded or encouraged.
        </p>

        <p markdown="1">
            Julia has been and is making strides in this direction, but new to the table is AI (something this tech lover turned luddite wanted to avoid always fearful this bandwagon is going to collapse and collapse hard.) I will talk about the original ongoing efforts and our SmartSolve (Funded by DARPA DIAL) project that we hope will bring everything together for HPC. Most importantly we will encourage everyone to participate; we can not do this entirely ourselves and value your contributions.
        </p>
    </div>
</div>

<div class="card">
	<div class="card-header text-white bg-inverse"><i class="fa fa-users mr-3" aria-hidden="true"></i>Keynote II</div>
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
	<div class="card-header text-white bg-inverse"><i class="fa fa-users mr-3" aria-hidden="true"></i>Keynote III</div>
		<div style="margin: 10px">
        <h5>Task-Graphs: Why aren't we all using them?</h5>
        <p>Christian Trott (SNL)</p>
	<p markdown="1">
	Task-Graphs are a very attractive concept to express complex algorithms, manage asynchronicity and expose available concurrency. However, very few HPC applications are written in terms of task-graphs.  In this talk I will provide reflections on what I believe some of the reasons are, based on the experience  gained with Kokkos adoption in the last decade. To ground the discussion, this talk will provide an overview of the Kokkos::Graph design - a Kokkos capability that despite being introduced 4 years ago, has found very little adoption. A comparison with CUDA Graphs will demonstrate design tradeoffs in this space, and help highlight  adoption hurdles and correctness pitfalls that are likely an important part of the reason why task-graphs are not more widely used. Last but not least the talk will touch on how the recently approved ISO C++ 26 Execution framework ("Senders and Receivers") can help overcome some of these adoption hurdles, and allow us to realize the promise of a task-graph based application design. 
    </p>
    </div>
</div>
