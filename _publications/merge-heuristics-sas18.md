---
title: "Volume-Based Merge Heuristics for Disjunctive Numeric Domains"
collection: publications
permalink: /publications/merge-heuristics-sas18
excerpt: 
date: 2018-08-29
venue: 'International Static Analysis Symposium (SAS)'
link: 'https://link.springer.com/chapter/10.1007/978-3-319-99725-4_23'
citation: 'Andrew Ruef, <b>Kesha Hietala</b>, Arlen Cox. &quot;Volume-Based Merge Heuristics for Disjunctive Numeric Domains.&quot; <i>
International Static Analysis Symposium (SAS)</i>. 2018.'
abstract: "Static analysis of numeric programs allows proving important properties of programs such as a lack of buffer overflows, division by zero, or integer overflow. By using convex numeric abstractions, such as polyhedra, octagons, or intervals, representations of program states are concise and the analysis operations are efficient. Unfortunately, many sets of program states can only be very imprecisely represented with a single convex numeric abstraction. This means that many important properties cannot be proven using only these abstractions. One solution to this problem is to use powerset abstractions where a set of convex numeric abstractions represents the union rather than the hull of those state sets. This leads to a new challenge: when to merge elements of the powerset and when to keep them separate. We present a new methodology for determining when to merge based on counting and volume arguments. Unlike previous techniques, this heuristic directly represents losses in precision through hull computations. In this paper we develop these techniques and show their utility on a number of programs from the SV-COMP and WCET benchmark suites."
---