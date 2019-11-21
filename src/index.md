@def title = "The Julia Language Blog"
@def hasmath = false
@def hascode = false

<!-- Note: by default hasmath == true and hascode == false. You can change this in
the config file by setting hasmath = false for instance and just setting it to true
where appropriate -->

<!-- I can't understand what they're doing over in julialang.org/blog's jekyll-land
so let's go with a simple CSS grid -->

The Julia blog discusses issues of numerical, technical, distributed and parallel computing, as well as programming language design, and how these issues touch upon the design and implementation of the Julia programming language. Also see the [Julia Computing blog](http://juliacomputing.com/blog/) for another source of information regarding ongoing Julia development.

Blogs from the broader Julia community can be found at [Julia Bloggers](http://www.juliabloggers.com/).

This is a mirror of the official Julia blog, a playground useful when developing with  [JuDoc](https://github.com/tlienart/JuDoc.jl). The JuDoc source for this is [here](https://github.com/cormullion/julialangblog).

~~~
<style>
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
  grid-gap: 1rem;
}

.grid > div {
}

.grid > h2, .grid > p {
  background: #f2f2f2;
  padding: 0.5rem 0.5rem 1rem 0.5rem;
  font-size: 0.9em;
  line-height: 1.1rem;
  border-radius: 5px;
  text-align:left;
}
</style>
<div class="grid">
~~~


[Pkg + BinaryBuilder — The Next Generation](/pub/2019-11-19-artifacts.html) 2019-11-19

[Profiling tool wins and woes](/pub/2019-09-16-profilers.html) 2019-09-16

[Julia的版本发布流程](/pub/2019-09-07-release-process-zh-cn.html) 2019-09-07

[Julia夏季会议@Beijing & 本地化奖](/pub/2019-09-07-julia-workshop-beijing-zh_cn.html) 2019-09-07

[Julia Workshop@Beijing](/pub/2019-09-07-julia-workshop-beijing.html) 2019-09-07

[Julia’s Release Process](/pub/2019-08-28-release-process.html) 2019-08-28

[Julia User & Developer Survey 2019](/pub/2019-08-06-2019-julia-survey.html) 2019-08-06

[Julia将支持可组合的多线程并行机制](/pub/2019-07-30-multithreading-zh-cn.html) 2019-07-30

[Announcing composable multi-threaded parallelism in Julia](/pub/2019-07-23-multithreading.html) 2019-07-23

[Hello @DiffEqBot](/pub/2019-06-18-diffeqbot.html) 2019-06-18

[A Summer of Julia 2019](/pub/2019-05-31-jsoc19.html) 2019-05-31

[Beyond machine learning pipelines with MLJ](/pub/2019-05-02-beyond-ml-pipelines-with-mlj.html) 2019-05-02

[DiffEqFlux.jl – Julia 的神經微分方程套件](/pub/2019-04-04-fluxdiffeq-zh_tw.html) 2019-04-04

[A Julia interpreter and debugger](/pub/2019-03-19-debuggers.html) 2019-03-19

[The Julia Project and Its Entities](/pub/2019-02-12-julia-entities.html) 2019-02-12

[GSoC 2018 - Parallel Implementations of Graph Analysis Algorithms](/pub/2019-02-03-light-graphs.html) 2019-02-03

[DiffEqFlux.jl – A Julia Library for Neural Differential Equations](/pub/2019-01-18-fluxdiffeq.html) 2019-01-18

**2018**

[Building a Language and Compiler for Machine Learning](/pub/2018-12-03-ml-language-compiler.html) 2018-12-03

[How to get started with Julia 1.0's package manager](/pub/2018-09-12-Pkgtutorial.html) 2018-09-12

[A portrait of JuliaCon 2018](/pub/2018-09-11-juliacon2018.html) 2018-09-11

[The Julia Community Prizes, 2018](/pub/2018-09-04-julia-community-prizes.html) 2018-09-04

[GSoC 2018 and Speech Recognition for the Flux Model Zoo: The Conclusion](/pub/2018-08-14-GSoC2018-speech-recognition.html) 2018-08-14

[GSoC 2018: Adding Newer Features and Speeding up Convolutions in Flux](/pub/2018-08-13-adding-newer-features-and-speeding-up-convolutions-in-flux.html) 2018-08-13

[Union-splitting: what it is, and why you should care](/pub/2018-08-09-union-splitting.html) 2018-08-09

[Announcing the release of Julia 1.0](/pub/2018-08-08-one-point-zero.html) 2018-08-08

[Julia 1.0 正式發佈](/pub/2018-08-08-one-point-zero-zh_tw.html) 2018-08-08

[Julia 1.0正式发布](/pub/2018-08-08-one-point-zero-zh_cn.html) 2018-08-08

[Anunciando el release de Julia 1.0](/pub/2018-08-08-one-point-zero-es.html) 2018-08-08

[GSoC 2018: Reinforcement Learning and Generative models using Flux](/pub/2018-08-06-GSoC-Final-Summary.html) 2018-08-06

[Writing Iterators in Julia 0.7](/pub/2018-07-08-iterators-in-julia-0.7.html) 2018-07-08

[First-Class Statistical Missing Values Support in Julia 0.7](/pub/2018-06-19-missing.html) 2018-06-19

[Extensible broadcast fusion](/pub/2018-05-11-extensible-broadcast-fusion.html) 2018-05-11

[Tetris coming to Julia language for v1.0](/pub/2018-04-01-tetris-and-you.html) 2018-04-01

[Some π-ography](/pub/2018-03-14-pifonts.html) 2018-03-14

[Julia joins NumFOCUS in Google Summer of Code 2018](/pub/2018-02-21-gsoc2018-numfocus.html) 2018-02-21

**2017**

[機器學習以及程式語言](/pub/2017-12-25-ml&pl-zh_tw.html) 2017-12-25

[机器学习与编程语言](/pub/2017-12-20-ml&pl-cn.html) 2017-12-20

[On Machine Learning and Programming Languages](/pub/2017-12-06-ml&pl.html) 2017-12-06

[GSoC 2017: Native Julia second order ODE and BVP solvers](/pub/2017-11-01-gsoc-ode.html) 2017-11-01

[NeuralNetDiffEq.jl: A Neural Network solver for ODEs](/pub/2017-10-13-gsoc-NeuralNetDiffEq.html) 2017-10-13

[Command interpolation for dummies](/pub/2017-10-05-command-interpolation-for-dummies.html) 2017-10-05

[GSoC 2017 Project: Hamiltonian Indirect Inference](/pub/2017-09-19-Hamiltonian-Indirect-Inference.html) 2017-09-19

[GSoC 2017: Parallelism in BioJulia](/pub/2017-09-07-bio-parallel.html) 2017-09-07

[GSoC 2017: Efficient Discretizations of PDE Operators](/pub/2017-09-06-gsoc-derivative_operators.html) 2017-09-06

[GSoC 2017 Project: MCMC with flexible numbers of parameters](/pub/2017-09-03-GSOC-MCMC-with-flexible-numbers-of-parameters.html) 2017-09-03

[GSoC 2017 : A Wrapper for the FEniCS Finite Element Toolbox](/pub/2017-09-01-gsoc-fenics.html) 2017-09-01

[GSoC 2017: Documentation Browser for Juno](/pub/2017-08-28-gsoc-docs-in-juno.html) 2017-08-28

[GSoC 2017: Implementing iterative solvers for numerical linear algebra](/pub/2017-08-23-native-julia-implementations-of-iterative-solvers-for-numerical-linear-algebra.html) 2017-08-23

[JuliaCon 2017 on the West Coast](/pub/2017-08-15-juliacon.html) 2017-08-15

[Creating domain-specific languages in Julia using macros](/pub/2017-08-09-dsl.html) 2017-08-09

[Julia 0.6 Release Announcement](/pub/2017-06-27-julia-0.6-release.html) 2017-06-27

[Julia available in Raspbian on the Raspberry Pi](/pub/2017-05-03-raspberry-pi-julia.html) 2017-05-03

[Upgrades to the REPL in Julia 0.6](/pub/2017-04-25-repl-0.6-highlights.html) 2017-04-25

[Knowing where you are: custom array indices in Julia](/pub/2017-04-18-offset-arrays.html) 2017-04-18

[Paper in SIAM Review: Julia - A Fresh Approach to Numerical Computing](/pub/2017-03-18-julia-fresh-paper.html) 2017-03-18

[Some fun with π; in Julia](/pub/2017-03-14-piday.html) 2017-03-14

[Technical preview: Native GPU programming with CUDAnative.jl](/pub/2017-03-14-cudanative.html) 2017-03-14

[More Dots: Syntactic Loop Fusion in Julia](/pub/2017-01-21-moredots.html) 2017-01-21

**2016**

[Julia 0.5 Highlights](/pub/2016-10-11-julia-0.5-highlights.html) 2016-10-11

[Julia 0.5 Release Announcement](/pub/2016-10-10-julia-0.5-release.html) 2016-10-10

[StructuredQueries.jl - A generic data manipulation framework](/pub/2016-10-03-StructuredQueries.html) 2016-10-03

[A Personal Perspective On JuliaCon 2016](/pub/2016-09-21-juliacon2016.html) 2016-09-21

[BioJulia 2016 - online sequence search, sequence demultiplexing, new readers and much more&#33;](/pub/2016-09-10-biojulia2016-mid.html) 2016-09-10

[Graft.jl - General purpose graph analytics for Julia](/pub/2016-08-22-GSoC2016-Graft.html) 2016-08-22

[Announcing support for complex-domain linear programs in Convex.jl](/pub/2016-08-17-announcing-support-for-complex-domain-linear-programs-in-Convex.jl.html) 2016-08-17

[An invitation to JuliaCon 2016](/pub/2016-05-08-juliacon-invitation.html) 2016-05-08

[BioJulia Project in 2016](/pub/2016-04-30-biojulia2016.html) 2016-04-30

[Google Summer of Code 2016](/pub/2016-04-14-gsoc.html) 2016-04-14

[Generalizing AbstractArrays: opportunities and challenges](/pub/2016-03-27-arrays-iteration.html) 2016-03-27

[An introduction to ParallelAccelerator.jl](/pub/2016-03-01-parallelaccelerator.html) 2016-03-01

[Multidimensional algorithms and iteration](/pub/2016-02-01-iteration.html) 2016-02-01

[Julia IDE work in Atom](/pub/2016-01-07-atom-work.html) 2016-01-07

**2015**

[JSoC 2015 project: DataStreams.jl](/pub/2015-10-25-datastreams.html) 2015-10-25

[JSoC 2015 project: Automatic Differentiation in Julia with ForwardDiff.jl](/pub/2015-10-23-auto-diff-in-julia.html) 2015-10-23

[JSoC 2015 project: Interactive Visualizations in Julia with GLVisualize.jl](/pub/2015-10-22-glvisualize.html) 2015-10-22

[JSoC 2015 project: Efficient data structures and algorithms for sequence analysis in BioJulia](/pub/2015-10-21-biojulia-sequence-analysis.html) 2015-10-21

[JSoC 2015 project: Interactive 3D Graphics in the Browser with Compose3D](/pub/2015-10-20-compose3d-threejs.html) 2015-10-20

[JSoC 2015 project: NullableArrays.jl](/pub/2015-10-16-nullablearrays.html) 2015-10-16

[Julia 0.4 Release Announcement](/pub/2015-10-09-julia-0.4-release.html) 2015-10-09

[JuliaCon 2015 Preview - Deep Learning, 3D Printing, Parallel Computing, and so much more](/pub/2015-05-30-juliacon-preview.html) 2015-05-30

[Julia Summer of Code 2015](/pub/2015-05-23-jsoc-cfp.html) 2015-05-23

2014

[Julia 0.3 Release Announcement](/pub/2014-08-20-julia-0.3-release.html) 2014-08-20

[JuliaCon 2014 Optimization Presentations](/pub/2014-08-09-juliacon-opt-session.html) 2014-08-09

[JuliaCon 2014 Opening Session Presentations](/pub/2014-08-09-juliacon-opening-session.html) 2014-08-09

**2013**

[Fast Numeric Computation in Julia](/pub/2013-09-04-fast-numeric.html) 2013-09-04

[Building GUIs with Julia, Tk, and Cairo, Part II](/pub/2013-05-23-graphical-user-interfaces-part2.html) 2013-05-23

[Building GUIs with Julia, Tk, and Cairo, Part I](/pub/2013-05-23-graphical-user-interfaces-part1.html) 2013-05-23

[Passing Julia Callback Functions to C](/pub/2013-05-10-callback.html) 2013-05-10

[Put This In Your Pipe](/pub/2013-04-08-put-this-in-your-pipe.html) 2013-04-08

[Distributed Numerical Optimization](/pub/2013-04-05-distributed-numerical-optimization.html) 2013-04-05

[Videos from the Julia tutorial at MIT](/pub/2013-03-30-julia-tutorial-MIT.html) 2013-03-30

[Efficient Aggregates in Julia](/pub/2013-03-05-efficient-aggregates.html) 2013-03-05

2012

[Design and implementation of Julia](/pub/2012-08-16-design-and-implementation-of-julia.html) 2012-08-16

[New York Open Stats Meetup](/pub/2012-04-18-nyc-open-stats-meetup-announcement.html) 2012-04-18

[Lang.NEXT Announcement](/pub/2012-03-24-lang-next-talk-announcement.html) 2012-03-24

[Shelling Out Sucks](/pub/2012-03-11-shelling-out-sucks.html) 2012-03-11

[Stanford Talk Video](/pub/2012-03-01-stanford-talk-video.html) 2012-03-01

[Stanford Talk Announcement](/pub/2012-02-27-talk-announcement.html) 2012-02-27

[Why We Created Julia](/pub/2012-02-14-why-we-created-julia.html) 2012-02-14

[为什么我们要创造](/pub/2012-02-14-why-we-created-julia-zh_CN.html) 2012-02-14

~~~
</div>
~~~
