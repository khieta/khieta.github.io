---
title: "Verified Compilation of Quantum Oracles"
collection: publications
permalink: /publications/vqo-oopsla22
excerpt: 
date: 2022-10-31
venue: 'Proceedings of the ACM on Programming Languages (OOPSLA)'
link: 'https://dl.acm.org/doi/abs/10.1145/3563309'
paperurl: 'https://arxiv.org/pdf/2112.06700.pdf'
github: 'https://github.com/inQWIRE/VQO'
citation: 'Liyi Li, Finn Voichick, <b>Kesha Hietala</b>, Yuxiang Peng, Xiaodi Wu, Michael Hicks. &quot;Verified Compilation of Quantum Oracles.&quot; <i>Proceedings of the ACM on Programming Languages (OOPSLA)</i>. 2022.'
abstract: "Quantum algorithms often apply classical operations, such as arithmetic or predicate checks, over a quantum superposition of classical data; these so-called oracles are often the largest components of a quantum program. To ease the construction of efficient, correct oracle functions, this paper presents VQO, a high-assurance framework implemented with the Coq proof assistant. The core of VQO is OQASM, the oracle quantum assembly language. OQASM operations move qubits between two different bases via the quantum Fourier transform, thus admitting important optimizations, but without inducing entanglement and the exponential blowup that comes with it. OQASM's design enabled us to prove correct VQO's compilers -- from a simple imperative language called OQIMP to OQASM, and from OQASM to SQIR, a general-purpose quantum assembly language -- and allowed us to efficiently test properties of OQASM programs using the QuickChick property-based testing framework. We have used VQO to implement a variety of arithmetic and geometric operators that are building blocks for important oracles, including those used in Shor's and Grover's algorithms. We found that VQO's QFT-based arithmetic oracles require fewer qubits, sometimes substantially fewer, than those constructed using 'classical' gates; VQO's versions of the latter were nevertheless on par with or better than (in terms of both qubit and gate counts) oracles produced by Quipper, a state-of-the-art but unverified quantum programming platform."
---