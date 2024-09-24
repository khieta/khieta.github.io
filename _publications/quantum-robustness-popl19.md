---
title: "Quantitative Robustness Analysis of Quantum Programs"
collection: publications
permalink: /publications/quantum-robustness-popl19
excerpt: 
date: 2019-01-02
venue: 'Proceedings of the ACM Conference on Principles of Programming Languages (POPL)'
link: 'https://dl.acm.org/doi/10.1145/3290344'
paperurl: 'https://arxiv.org/pdf/1811.03585.pdf'
citation: 'Shih-Han Hung, <b>Kesha Hietala</b>, Shaopeng Zhu, Mingsheng Ying, Michael Hicks, Xiaodi Wu. &quot;Quantitative Robustness Analysis of Quantum Programs.&quot; <i>Proceedings of the ACM Conference on Principles of Programming Languages (POPL)</i>. 2019.'
abstract: "Quantum computation is a topic of significant recent interest, with practical advances coming from both research and industry. A major challenge in quantum programming is dealing with errors (quantum noise) during execution. Because quantum resources (e.g., qubits) are scarce, classical error correction techniques applied at the level of the architecture are currently cost-prohibitive. But while this reality means that quantum programs are almost certain to have errors, there as yet exists no principled means to reason about erroneous behavior. This paper attempts to fill this gap by developing a semantics for erroneous quantum while-programs, as well as a logic for reasoning about them. This logic permits proving a property we have identified, called є-robustness, which characterizes possible “distance” between an ideal program and an erroneous one. We have proved the logic sound, and showed its utility on several case studies, notably: (1) analyzing the robustness of noisy versions of the quantum Bernoulli factory (QBF) and quantum walk (QW); (2) demonstrating the (in)effectiveness of different error correction schemes on single-qubit errors; and (3) analyzing the robustness of a fault-tolerant version of QBF."
---