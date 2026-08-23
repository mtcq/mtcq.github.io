---
layout: page
permalink: /resources/
title: resources
nav: true
description: Here are some resources for learning quantum information, from introductory material to more specialised topics.
---

Choose a topic below to explore.

<div class="resource-sections">

<details class="resource-section" id="first-steps">
<summary><h2>First steps in quantum information</h2></summary>
<div class="resource-content" markdown="1">

Linear algebra lies at the heart of quantum information and quantum computing, so a solid background in linear algebra is essential for understanding quantum information. At the same time, I would argue that quantum information offers an excellent route into linear algebra. Here are some resources that I recommend as starting points.

### Introductory quantum information

- **An excellent introductory course:** John Watrous's [*Understanding Quantum Information and Computation*](https://arxiv.org/abs/2507.11536) consists of 16 lessons, each with written notes and an accompanying video in the freely available [YouTube playlist](https://www.youtube.com/playlist?list=PLOFEBzvs-VvqKKMXX4vbi4EB1uaErFMSO). It begins with the basics and continues through quantum algorithms, channels, measurements, and quantum error correction.
- **The standard textbook:** Michael Nielsen and Isaac Chuang's [*Quantum Computation and Quantum Information*](https://www.cambridge.org/highereducation/books/quantum-computation-and-quantum-information/01E10196D0A682A6AEFFEA52D53BE9AE#overview) is a long-standing reference in the field. Chapter 2, “Introduction to Quantum Mechanics”, reviews linear algebra and quantum mechanics using bra–ket notation. First published in 2000, the book remains a valuable reference for anyone continuing in quantum information.
- **An information theory perspective:** Chapter 3, “The Noiseless Quantum Theory”, of Mark M. Wilde's [*From Classical to Quantum Shannon Theory*](https://arxiv.org/abs/1106.1445) provides another introduction to linear algebra with a quantum-information perspective. The book is freely available on arXiv; further information can be found on [Wilde's website](https://www.markwilde.com/).
- **Short supplementary lectures:** Artur Ekert's [*Introduction to Quantum Information Science*](https://www.youtube.com/playlist?list=PLkespgaZN4gmu0nWNmfMflVRqw0VPkCGH) video series covers a wide range of topics in short lectures. It is useful for revision, alternative explanations, and supplementary material alongside a master's programme.

### Linear algebra support

- **A rigorous general introduction:** Nathaniel Johnston's [*Introduction to Linear and Matrix Algebra*](https://njohnston.ca/publications/introduction-to-linear-and-matrix-algebra/) is not tailored to quantum information and does not use bra–ket notation, but it provides a strong foundation in linear algebra. His accompanying [44-video lecture series](https://www.youtube.com/playlist?list=PLOAf1ViVP13jmawPabxnAa00YFIetVqbd) is freely available on YouTube.
- **Visual intuition:** 3Blue1Brown's [*Essence of Linear Algebra*](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) develops an intuitive understanding of the motivation behind key definitions. These videos are excellent for building insight, but should be combined with a textbook and exercises to develop technical fluency.

### A more advanced reference

- John Watrous's [*The Theory of Quantum Information*](https://jhwatrous.github.io/books-and-courses.html) is freely available from his website. The basic mathematical concepts appear in Chapter 1, “Mathematical Preliminaries”. This book does not use bra–ket notation and is more advanced and computer-science-oriented than the other introductory resources, so it is best suited to readers with greater mathematical maturity.

<!-- Add recommended books, lecture notes, courses, and papers below. -->
</div>
</details>

<details class="resource-section" id="higher-order-quantum-operations">
<summary><h2>Higher-order quantum operations</h2></summary>
<div class="resource-content" markdown="1">

Higher-order quantum operations are transformations whose inputs and outputs can themselves be quantum operations. They provide a natural language for quantum circuits with open slots, transformations of quantum channels, and processes involving indefinite causal order. The resources below offer different levels of depth and focus.

- **A direct and compact introduction:** For a concise starting point, I recommend Chapter 2 of my HDR thesis, [*Quantum information processing via higher-order operations*]({{ '/assets/pdf/HDR_MTQ_final_version.pdf' | relative_url }}) (2025). It reviews the Choi representation and the required quantum-information concepts before introducing supermaps, superchannels, quantum testers, superinstruments, and multi-slot superchannels. The later chapters illustrate how the framework can be applied to transforming and discriminating quantum channels.
- **A tutorial and comprehensive review:** For a broader and more pedagogical treatment, I recommend our review [*Higher-Order Quantum Operations*](https://arxiv.org/abs/2503.09693), written with Philip Taranto, Simon Milz, Mio Murao, and Kavan Modi (2025). It combines a tutorial introduction with an extensive survey of physical examples, applications, the current literature, and open problems.
- **Indefinite quantum causality:** If your main interest is indefinite causal order and related foundational questions, I recommend our review [*Indefinite Quantum Causality*](https://arxiv.org/abs/2606.19438), written with Fabio Costa, Giulia Rubino, Cyril Branciard, and Časlav Brukner (2026). It introduces the process matrix formalism and surveys key results, experimental implementations, and recent advances in the field.

<!-- Add recommended books, lecture notes, courses, and papers below. -->
</div>
</details>

<details class="resource-section" id="quantum-correlations">
<summary><h2>Quantum correlations</h2></summary>
<div class="resource-content" markdown="1">

Entanglement, EPR steering, and Bell nonlocality are among the central forms of quantum correlation, forming a hierarchy of increasingly strong departures from classical physics. Joint measurability concerns quantum measurements rather than correlations directly, but it is closely connected to both steering and Bell nonlocality. I recommend the following reviews as starting points.

- **Bell nonlocality:** For a comprehensive introduction to Bell nonlocality, I recommend [*Bell nonlocality*](https://arxiv.org/abs/1303.2849) by Nicolas Brunner, Daniel Cavalcanti, Stefano Pironio, Valerio Scarani, and Stephanie Wehner (2014). It develops the main concepts and tools used to describe and study nonlocality, and explains its importance in quantum information science.
- **EPR steering:** For EPR steering, I recommend [*Quantum steering*](https://arxiv.org/abs/1903.06663) by Roope Uola, Ana C. S. Costa, H. Chau Nguyen, and Otfried Gühne (2020). It introduces steering and local hidden state models, explains their relationship to entanglement and Bell nonlocality, and discusses criteria for steerability, connections with measurement incompatibility, and applications to quantum information processing.
- **Joint measurability:** For joint measurability and measurement incompatibility, I recommend [*Colloquium: Incompatible measurements in quantum information science*](https://arxiv.org/abs/2112.06784) by Otfried Gühne, Erkka Haapasalo, Tristan Kraft, Juha-Pekka Pellonpää, and Roope Uola (2023). It covers the basic definitions, applications to uncertainty relations, the characterisation of quantum correlations and quantum state discrimination, and emerging directions such as resource theories of incompatibility.

<!-- Add recommended books, lecture notes, courses, and papers below. -->
</div>
</details>

<details class="resource-section" id="semidefinite-programming">
<summary><h2>Semidefinite programming</h2></summary>
<div class="resource-content" markdown="1">

- **SDPs and quantum information:** My main recommendation for learning about SDPs in quantum information is [*Semidefinite Programming in Quantum Information Science*](https://doi.org/10.1088/978-0-7503-3343-6) by Paul Skrzypczyk and Daniel Cavalcanti, published by IOP Publishing in 2023. Chapter 3, which covers quantum states, is [freely available on arXiv](https://arxiv.org/abs/2306.11637).
- **Convex optimisation:** For a broader introduction to convex optimisation, including SDPs, an excellent standard reference is Stephen Boyd and Lieven Vandenberghe's [*Convex Optimization*](https://web.stanford.edu/~boyd/cvxbook/). The complete book is freely available from the authors' website.
- **JuMP:** For solving SDPs numerically, I recommend [JuMP.jl](https://jump.dev/JuMP.jl/stable/), a Julia modelling language for mathematical optimisation. Its documentation includes a useful worked example on [quantum state discrimination](https://jump.dev/JuMP.jl/stable/tutorials/conic/quantum_discrimination/).
- **Ket.jl:** If you use Julia for quantum information and semidefinite programming, I also recommend [Ket.jl](https://dev-ket.github.io/Ket.jl/dev/), a toolbox for quantum information, nonlocality, and entanglement that can be used together with JuMP.

<!-- Add recommended books, lecture notes, courses, and papers below. -->
</div>
</details>

</div>
