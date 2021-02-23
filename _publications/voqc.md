---
title: "A Verified Optimizer for Quantum Circuits"
collection: publications
permalink: /publication/voqc
excerpt: 
date: 2021-01-20
venue: 'Proceedings of the ACM Conference on Principles of Programming Languages (POPL)'
link: 'https://dl.acm.org/doi/10.1145/3434318'
paperurl: 'https://arxiv.org/pdf/1912.02250.pdf'
github: 'https://github.com/inQWIRE/SQIR'
citation: '<b>Kesha Hietala</b>, Robert Rand, Shih-Han Hung, Xiaodi Wu, Michael Hicks. &quot;A Verified Optimizer for Quantum Circuits.&quot; <i>Proceedings of the ACM Conference on Principles of Programming Languages (POPL)</i>. 2021.'
abstract: "We present VOQC, the first fully verified optimizer for quantum circuits, written using the Coq proof assistant. Quantum circuits are expressed as programs in a simple, low-level language called SQIR, a simple quantum intermediate representation, which is deeply embedded in Coq. Optimizations and other transformations are expressed as Coq functions, which are proved correct with respect to a semantics of SQIR programs. SQIR uses a semantics of matrices of complex numbers, which is the standard for quantum computation, but treats matrices symbolically in order to reason about programs that use an arbitrary number of quantum bits. SQIR's careful design and our provided automation make it possible to write and verify a broad range of optimizations in VOQC, including full-circuit transformations from cutting-edge optimizers."
---

**Distinguished paper at POPL 2021**