---
title: "How We Built Cedar: A Verification-Guided Approach"
collection: publications
permalink: /publications/cedar-fse24
excerpt: 
date: 2024-07-10
venue: 'Companion Proceedings of the 32nd ACM International Conference on the Foundations of Software Engineering (FSE)'
link: 'https://dl.acm.org/doi/abs/10.1145/3663529.3663854'
paperurl: 'https://arxiv.org/pdf/2407.01688'
github: 'https://github.com/cedar-policy'
citation: 'Craig Disselkoen, Aaron Eline, Shaobo He, Kyle Headley, Michael Hicks, <b>Kesha Hietala</b>, John Kastner, Anwar Mamat, Matt McCutchen, Neha Rungta, Bhakti Shah, Emina Torlak, Andrew Wells. &quot;How We Built Cedar: A Verification-Guided Approach.&quot; <i>Companion Proceedings of the 32nd ACM International Conference on the Foundations of Software Engineering (FSE)</i>. 2024.'
abstract: "This paper presents verification-guided development (VGD), a software engineering process we used to build Cedar, a new policy language for expressive, fast, safe, and analyzable authorization. Developing a system with VGD involves writing an executable model of the system and mechanically proving properties about the model; writing production code for the system and using differential random testing (DRT) to check that the production code matches the model; and using property-based testing (PBT) to check properties of unmodeled parts of the production code. Using VGD for Cedar, we can build fast, idiomatic production code, prove our model correct, and find and fix subtle implementation bugs that evade code reviews and unit testing. While carrying out proofs, we found and fixed 4 bugs in Cedar’s policy validator, and DRT and PBT helped us find and fix 21 additional bugs in various parts of Cedar."
---
Industry track paper
