---
title: "FastVer2: A Provably Correct Monitor for Concurrent, Key-Value Stores"
collection: publications
permalink: /publications/fastver-cpp23
excerpt: 
date: 2023-01-17
venue: 'Proceedings of the ACM SIGPLAN International Conference on Certified Programs and Proofs (CPP)'
paperurl: '../files/drafts/fastver2-cpp-2023.pdf'
citation: 'Arvind Arasu, Tahina Ramananandro, Aseem Rastogi, Nikhil Swamy, Aymeric Fromherz, <b>Kesha Hietala</b>, Bryan Parno, Ravi Ramamurthy. &quot;FastVer2: A Provably Correct Monitor for Concurrent, Key-Value Stores.&quot; <i>Proceedings of the ACM SIGPLAN International Conference on Certified Programs and Proofs (CPP)</i>. 2023.'
abstract: "FastVer is a protocol that uses a variety of memory-checking techniques to monitor the integrity of key-value stores with only a modest runtime cost. Arasu et al. formalize the high-level design of FastVer in the F★ proof assistant and prove it correct. However, their formalization did not yield a provably correct implementation---FastVer is implemented in unverified C++ code.

In this work, we present FastVer2, a low-level, concurrent implementation of FastVer in Steel, an F★ DSL based on concurrent separation logic that produces C code, and prove it correct with respect to FastVer’s high-level specification. Our proof is the first end-to-end system proven using Steel, and in doing so we contribute new ghost-state constructions for reasoning about monotonic state. Our proof also uncovered a few bugs in the implementation of FastVer.

We evaluate FastVer2 by comparing it against FastVer. Although our verified monitor is slower in absolute terms than the unverified code, its performance also scales linearly with the number of cores, yielding a throughput of more that 10M op/sec. We identify several opportunities for performance improvement, and expect to address these in the future."
---