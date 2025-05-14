---
layout: default
title: Speakers
published: true
---

## Speakers

### Keynotes

#### <a href="https://www.cs.uni-salzburg.at/~anas/">Ana Sokolova</a>, University of Salzburg, Austria <br />
**Title**\
Semantics for Probabilistic Systems: From Bisimilarity to Epsilon-Bisimilarity, Coalgebraically

**Abstract**
<div style="text-align: justify">
Probabilistic systems have been inspiring examples for lot of development in the theory of coalgebra, in particular when it comes to semantics. We (as community) have been dealing with bisimilarity, trace, as well as behavioural distances -- the latter as generalizations of the notion of behavioural equivalence: instead of proving that states behave the same, they quantify how different/similar the behaviour of two states is. Related to behavioural distances is a notion of approximate bisimulation, known as epsilon-bisimulation / bisimilarity. Even though this is a beautiful notion, it has stood aside for some time -- as the induced distance was not understood in general terms. In recent work, with Joseé Desharnais, we revive this notion and show that it has an appealing coalgebraic characterization, too. Most of our work is based on the observation that the induced epsilon-distance is obtained in a similar way to the Kantorovich behaviour distance, by replacing the Kantorovich distance on distributions by the Lévy-Prokhorov one, and that it admits an equally nice coinductive characterization. This talk will be introductory to a great extent, focusing on behavioural equivalences and preorders of probabilistic systems, coalgebraically. In addition, I will present the recent results on epsilon-bisimulation and epsilon-distance, as well as the coalgebraic characterization thereof.
</div>

<br />

#### <a href="https://podkopaev.net/">Anton Podkopaev</a>, JetBrains, the Netherlands <br />
**Title**\
Generative AI and formal verification. Could they benefit each other?

**Abstract**
<div style="text-align: justify">
One of the important problems of using Generative AI for code generation is to make sure that the generated programs satisfy expectations. In most cases, the check is left to a software developer: they need to decide if the generated code is suitable or not. It doesn't scale well: any new generated component needs to be checked by hand and cannot be added to the code base w/o human supervision. In the future w/ more and more generated code, this will become the main bottleneck for software development. Thus this area requires some kind of tool support.
For mainstream programming languages, there are approaches to reduce the burden by applying techniques like testing and static analysis to check for absence of common bugs, but they don't help to verify the semantics of the generated program.
However, there are programming languages with rich type systems (Coq, Lean, Dafny, etc.) and extensions to more mainstream languages (Nagini for Python, Verus for Rust) allowing for automatic checking that a program satisfies its specification. For example, in these languages we may define a function type which requires the function to be a sorting algorithm. Any generated implementation may be automatically checked against the type, and if it typechecks, there is no need for a human to check it.
Currently, such languages are not widespread and mostly used for writing critical software components like cryptography libraries (BoringSSL), airplane firmware (Airbus), and highly scalable distributed systems (AWS). The reason for that is that they require significant expertise and effort to apply, but Generative AI looks like a promising solution to the problem.
In this talk, we are going to discuss how richly typed programming languages may help Generative AI and vice versa. Anton is going to present results of JetBrains Research in the area of applying LLMs to generating Coq code (the CoqPilot project) and verified imperative code (generation of Dafny and verified Python and Rust).
</div>

### Invited speakers

#### <a href="https://burcuku.github.io/home/">Burcu Ozkan</a>,  Delft University of Technology, the Netherlands <br />
**Title**\
Model-guided Testing of Distributed Systems

**Abstract**
<div style="text-align: justify">
Coverage-guided randomized testing is effective in finding corner-case bugs in software. However, existing coverage metrics, such as code coverage, are designed for sequential programs, and they are not suitable for assessing the coverage of distributed system behaviors.We present a coverage notion and coverage-guided testing algorithm for distributed systems implementations. Our main innovation is the use of an abstract formal model of the system that is used to define coverage. Our evaluation shows that guiding random test generation using model coverage effectively covers interesting points in the implementation state space. Bio: Burcu Kulahcioglu Ozkan is an assistant professor and Delft Technology Fellow in the TU Delft Software Engineering Research Group. She received her PhD from Koç University Istanbul, Turkey, followed by postdoctoral research at the Max Planck Institute for Software Systems (MPI-SWS) in Kaiserslautern, Germany. Her research focuses on model checking, software testing, and debugging of concurrent programs and distributed systems.
</div>

<br />

#### <a href="https://lmove.github.io/">Lina Ochoa Venegas</a>, Eindhoven University of Technology, the Netherlands <br />
**Title**\
Migration without Assimilation: A Software Evolution Perspective

**Abstract**
<div style="text-align: justify">
Lehman once stated that software must continually change, or else it becomes progressively less satisfactory. Software projects must not only adapt to internal changes but also respond to an ever-changing environment that inevitably impacts the system. These external influences can take the form of breaking changes, security issues, or bugs rippling from external libraries to internal code. They can also manifest as design erosion and low-quality implementations requiring an overhaul via refactorings. A plethora of static, deterministic, and change-specific tools have been released to help in migrating damaged code to a revamped version. With the advent of generative AI, this set has been extended to also include the one-size-fits-all solution: large language models. The challenge has thus shifted: it is no longer just about migrating code, but rather ensuring that the generated code preserves the original semantics of the modernised system. In this talk, we address the problem of validating assimilation in code migration, understood as the adoption of a different behaviour after code transformation. We also discuss new research avenues on providing a hybrid validation approach that combines static and data-driven methods to look for semantic loss in software evolution.
</div>

<br />

#### <a href="https://tobias.kap.pe/">Tobias Kappé</a>, Leiden University, the Netherlands <br />
**Title**\
On propositional program equivalence

**Abstract**
<div style="text-align: justify">
Most programmers have an intuitive understanding of general equivalences between programs. For instance, the branches of an if-then-else block can be swapped, as long as its condition is negated --- regardless of what the branches or condition look like. Such propositional program equivalences are useful to verify that a refactoring operation preserves program semantics, but they can be hard to justify by hand, especially when loops are involved. We will survey recent advances in propositional program equivalence from the perspective of Guarded Kleene Algebra with Tests (GKAT). Topic covered include algebraic reasoning about program equivalence and fast decision procedures, as well as connections to decompilation and control flow restructuring. This talk will cover joint work with Balder ten Cate, Justin Hsu, Nate Foster, Dexter Kozen, David E. Narváez, Nico Naus, Wojciech Różowski, Todd Schmid, Alexandra Silva, Steffen Smolka, and Cheng Zhang."
</div>

<br />

#### <a href="https://timcoopmans.com/">Tim Coopmans</a>, QuTech, the Netherlands
**Title**\
Computer science for quantum technology

**Abstract**
<div style="text-align: justify">
Quantum computing still has a stereotype that it is a field only truly accessible to physicists. To show that this is not true and computer scientists are needed in the field, I will present a range of examples of successful application of computer science in quantum technology that I was involved in.
</div>

<br />
