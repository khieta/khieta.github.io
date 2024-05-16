---
title: "Cedar: A New Language for Expressive, Fast, Safe, and Analyzable Authorization"
collection: publications
permalink: /publications/cedar-oopsla24
excerpt: 
date: 2024-04-29
venue: 'Proceedings of the ACM on Programming Languages (OOPSLA)'
link: 'https://dl.acm.org/doi/10.1145/3649835'
paperurl: 'https://arxiv.org/pdf/2403.04651'
github: 'https://github.com/cedar-policy'
citation: 'Joseph W. Cutler, Craig Disselkoen, Aaron Eline, Shaobo He, Kyle Headley, Michael Hicks, <b>Kesha Hietala</b>, Lef Ioannidis, John Kastner, Anwar Mamat, Darin McAdams, Matt McCutchen, Neha Rungta, Emina Torlak, Andrew Wells. &quot;Cedar: A New Language for Expressive, Fast, Safe, and Analyzable Authorization.&quot; <i>Proceedings of the ACM on Programming Languages (OOPSLA)</i>. 2024.'
abstract: "Cedar is a new authorization policy language designed to be ergonomic, fast, safe, and analyzable. Rather than embed authorization logic in an application’s code, developers can write that logic as Cedar policies and delegate access decisions to Cedar’s evaluation engine. Cedar’s simple and intuitive syntax supports common authorization use-cases with readable policies, naturally leveraging concepts from role-based, attribute-based, and relation-based access control models. Cedar’s policy structure enables access requests to be decided quickly. Cedar’s policy validator leverages optional typing to help policy writers avoid mistakes, but not get in their way. Cedar’s design has been finely balanced to allow for a sound and complete logical encoding, which enables precise policy analysis, e.g., to ensure that when refactoring a set of policies, the authorized permissions do not change. We have modeled Cedar in the Lean programming language, and used Lean’s proof assistant to prove important properties of Cedar’s design. We have implemented Cedar in Rust, and released it open-source. Comparing Cedar to two open-source languages, OpenFGA and Rego, we find (subjectively) that Cedar has equally or more readable policies, but (objectively) performs far better."
---