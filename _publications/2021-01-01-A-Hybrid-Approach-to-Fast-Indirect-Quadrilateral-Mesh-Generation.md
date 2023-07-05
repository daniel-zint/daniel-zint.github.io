---
title: "A Hybrid Approach to Fast Indirect Quadrilateral Mesh Generation"
collection: publications
permalink: /publication/2021-01-01-A-Hybrid-Approach-to-Fast-Indirect-Quadrilateral-Mesh-Generation
excerpt: '
**Author(s):** D. Zint, R. Grosso


**Abstract:** Indirect quadrilateral mesh generation methods are commonly used particularly for numerical simulations due to their adaptiveness to different element sizes across the domain. The well-known Blossom-Quad algorithm generates high quality meshes but has a worst case complexity of O(N^2 + N log N). A method which merges triangles using topological operations is less complex, indeed we show that it has a complexity of O(N log N), but resulting meshes might have low quality especially near boundaries. We propose a combination of these two methods. Boundary regions are processed by Blossom-Quad and the interior by triangle merging. Post-processing solves quality issues caused by triangle merging. The results are comparable to pure Blossom-Quad but this approach is much faster. Therefore, it is favorable especially on large meshes where the runtime of Blossom-Quad might become troublesome. The efficiency of this hybrid approach is shown on ocean meshes with up to several million triangles.


\[[publication](https://rdcu.be/df8i5)\]
\[[code](https://github.com/daniel-zint/RatRace)\]
'
date: 2021-01-01
venue: "Numerical Geometry, Grid Generation and Scientific Computing. Lecture Notes in Computational Science and Engineering, vol 143."
#paperurl: "http://academicpages.github.io/files/paper1.pdf"
#citation: "Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1)."
---

**Author(s):** D. Zint, R. Grosso

**Abstract:** Indirect quadrilateral mesh generation methods are commonly used particularly for numerical simulations due to their adaptiveness to different element sizes across the domain. The well-known Blossom-Quad algorithm generates high quality meshes but has a worst case complexity of O(N^2 + N log N). A method which merges triangles using topological operations is less complex, indeed we show that it has a complexity of O(N log N), but resulting meshes might have low quality especially near boundaries. We propose a combination of these two methods. Boundary regions are processed by Blossom-Quad and the interior by triangle merging. Post-processing solves quality issues caused by triangle merging. The results are comparable to pure Blossom-Quad but this approach is much faster. Therefore, it is favorable especially on large meshes where the runtime of Blossom-Quad might become troublesome. The efficiency of this hybrid approach is shown on ocean meshes with up to several million triangles.

\[[publication](https://rdcu.be/df8i5)\]
\[[code](https://github.com/daniel-zint/RatRace)\]
