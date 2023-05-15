---
title: "A Formally Certified End-to-end Implementation of Shor’s Factorization Algorithm"
collection: publications
permalink: /publications/shors-pnas23
excerpt: 
date: 2023-05-15
venue: 'Proceedings of the National Academy of Sciences (PNAS)'
link: 'https://www.pnas.org/doi/10.1073/pnas.2218775120'
paperurl: 'https://arxiv.org/pdf/2204.07112.pdf'
citation: 'Yuxiang Peng, <b>Kesha Hietala</b>, Runzhou Tao, Liyi Li, Robert Rand, Michael Hicks, Xiaodi Wu. &quot;A Formally Certified End-to-end Implementation of Shor’s Factorization Algorithm.&quot; <i>Proceedings of the National Academy of Sciences (PNAS)</i>. 2023.'
abstract: "Quantum computing technology may soon deliver revolutionary improvements in algorithmic performance, but it is useful only if computed answers are correct. While hardware---level decoherence errors have garnered significant attention, a less recognized obstacle to correctness is that of human programming errors---"bugs." Techniques familiar to most programmers from the classical domain for avoiding, discovering, and diagnosing bugs do not easily transfer, at scale, to the quantum domain because of its unique characteristics. To address this problem, we have been working to adapt formal methods to quantum programming. With such methods, a programmer writes a mathematical specification alongside the program and semiautomatically proves the program correct with respect to it. The proof’s validity is automatically confirmed—certified—by a "proof assistant." Formal methods have successfully yielded high-assurance classical software artifacts, and the underlying technology has produced certified proofs of major mathematical theorems. As a demonstration of the feasibility of applying formal methods to quantum programming, we present a formally certified end-to-end implementation of Shor’s prime factorization algorithm, developed as part of a framework for applying the certified approach to general applications. By leveraging our framework, one can significantly reduce the effects of human errors and obtain a high-assurance implementation of large-scale quantum applications in a principled way."
---