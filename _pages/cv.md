---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Distributed Systems, University of Illinois Urbana-Champaign, 2028 (expected)
* Dual Degree (BTech + MTech) in Computer Science & Engineering, Indian Institute of Technology Madras, 2023

Work experience
======
* Research Assistant, DASSL Lab, UIUC (Aug '23 - present)
  * Designing and building high-performance systems for the modern datacenter.  

* Research Intern, Microsoft Research India (Aug '22 - Jul '23)
  * Worked on improving reliability of Azure Cloud Services using concurrency testing tools such as Coyote for C++ programs.
  * Built a deterministic concurrency testing framework for a production scale replication library, Azure RSL, which provides an implementation of the Paxos consensus algorithm. Implemented several optimizations to improve state-space coverage.

* Research Fellow, IIT Madras (Sep '20 - Jul '23)
  * Investigated cutoff-based techniques for verifying that distributed protocols meet their specification irrespective of the size of the parameter they are instantiated with (such as number of nodes).
  * Proposed a framework to mechanize simulation based proofs for cutoffs and applied the approach on a variety of distributed protocols using Z3 as a backend SMT solver.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

CV
======
Latest version of my CV can be found [here](https://shreesha00.github.io/files/cv.pdf)