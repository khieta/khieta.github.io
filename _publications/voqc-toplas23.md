---
title: "A Verified Optimizer for Quantum Circuits (Journal Version)"
collection: publications
permalink: /publications/voqc-toplas23
excerpt: 
date: 2023-09-23
venue: 'ACM Transactions on Programming Languages and Systems (TOPLAS)'
link: 'https://dl.acm.org/doi/10.1145/3604630'
github: 'https://github.com/inQWIRE/SQIR'
citation: '<b>Kesha Hietala</b>, Robert Rand, Liyi Li, Shih-Han Hung, Xiaodi Wu, Michael Hicks. &quot;A Verified Optimizer for Quantum Circuits.&quot; <i>ACM Transactions on Programming Languages and Systems (TOPLAS), 45(3)</i>. 2023.'
abstract: "We present VOQC, the first verified optimizer for quantum circuits, written using the Coq proof assistant. Quantum circuits are expressed as programs in a simple, low-level language called SQIR, a small quantum intermediate representation, which is deeply embedded in Coq. Optimizations and other transformations are expressed as Coq functions, which are proved correct with respect to a semantics of SQIR programs. SQIR programs denote complex-valued matrices, as is standard in quantum computation, but we treat matrices symbolically to reason about programs that use an arbitrary number of quantum bits. SQIR’s careful design and our provided automation make it possible to write and verify a broad range of optimizations in VOQC, including full-circuit transformations from cutting-edge optimizers."
---