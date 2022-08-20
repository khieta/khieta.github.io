---
title: "Finding Substitutable Binary Code By Synthesizing Adapters"
collection: publications
permalink: /publications/adapter-synth-tse19
excerpt: 
date: 2019-07-25
venue: 'IEEE Transactions on Software Engineering'
link: 'https://ieeexplore.ieee.org/document/8776650'
citation: 'Vaibhav Sharma, <b>Kesha Hietala</b>, Stephen McCamant. &quot;Finding Substitutable Binary Code By Synthesizing Adapters.&quot; <i>IEEE Transactions on Software Engineering (TSE)</i>. 2019.'
abstract: "Independently developed codebases typically contain many segments of code that perform same or closely related operations (semantic clones). Finding functionally equivalent segments enables applications like replacing a segment by a more efficient or more secure alternative. Such related segments often have different interfaces, so some glue code (an adapter) is needed to replace one with the other. We present an algorithm that searches for replaceable code segments by attempting to synthesize an adapter between them from some finite family of adapters; it terminates if it finds no possible adapter. We implement our technique using concrete adapter enumeration based on Intel's Pin framework and binary symbolic execution, and explore the relation between size of adapter search space and total search time. We present examples of applying adapter synthesis for improving security of binary functions and switching between binary implementations of RC4. We present two large-scale evaluations: (1) we run adapter synthesis on more than 13,000 function pairs from the Linux C library, and (2) we reverse engineer fragments of ARM binary code by running more than a million adapter synthesis tasks. Our results confirm that several instances of adaptably equivalent binary functions exist in real-world code, and suggest that adapter synthesis can be applied for automatically replacing binary code with its adaptably equivalent variants."
---