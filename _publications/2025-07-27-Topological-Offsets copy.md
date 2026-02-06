---
title: "Topological Offsets"
collection: publications
permalink: /publication/2025-07-27-Topological-Offsets
date: 2025-07-27
venue: "ACM Transactions on Graphics (TOG)"
#paperurl: "http://academicpages.github.io/files/paper1.pdf"
#citation: "Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1)."
---

**Author(s):** D. Zint, Z. Chen, Y. Zhu, D. Zorin, T. Schneider, D. Panozzo

**Abstract:** We introduce Topological Offsets, a novel approach to generate manifold and self-intersection-free offset surfaces that are topologically equivalent to an offset infinitesimally close to the surface. Our approach, by construction, creates a manifold, watertight, and self-intersection-free offset surface strictly enclosing the input, while doing a best effort to move it to a prescribed distance from the input. Differently from existing approaches, we embed the input in a background mesh and insert a topological offset around the input with purely combinatorial operations. The topological offset is then inflated/deflated to match the user-prescribed distance while enforcing that no intersections or non-manifold configurations are introduced.
We evaluate the effectiveness and robustness of our approach on the Thingi10k dataset, and show that topological offsets are beneficial in multiple graphics applications, including (1) converting non-manifold surfaces to manifold ones, (2) creating layered offsets, and (3) reliably computing finite offsets.

\[[publication](https://dl.acm.org/doi/abs/10.1145/3731157)\]
\[[pdf](/files/topological-offsets.pdf)\]
\[[code](https://github.com/wildmeshing/topological-offsets/)\]
\[[presentation](/files/DZ_Topological_Offsets_10min_SIGGRAPH.pptx)\]
