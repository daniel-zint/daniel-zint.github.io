---
title: "Block-Structured Grid Generation for High-Performance Ocean Simulation (Thesis)"
collection: publications
permalink: /publication/2021-12-01-Block-Structured-Grid-Generation-for-High-Performance-Ocean-Simulation
excerpt: '
**Author(s):** D. Zint


**Abstract:** In high‐performance computing, block‐structured grids are favored due to their geometric adaptability while supporting computational performance optimizations connected with structured grid discretizations. However, many problems on geometrically complex domains are traditionally solved using fully unstructured meshes. We address this deficiency in the two‐dimensional case by presenting a method which generates block‐structured grids (BSGs) with a prescribed number of blocks from an arbitrary triangular grid.


Each block in a BSG contains a structured grid. Vertex repositioning is one of the key operations for adapting a structured grid to a domain. We present an algorithm called discrete mesh optimization (DMO), a greedy approach to topology‐consistent mesh quality improvement. The method optimizes vertex positions according to a user defined quality metric. It is easily adaptable to any mesh and metric as it does not rely on differentiable functions. We give examples for triangle, quadrilateral, and tetrahedral meshes and for various metrics. We show that DMO outperforms other state of the art methods in terms of convergence and runtime.


We generate BSGs consisting of quadrilateral blocks which contain structured triangle grids. This design combines advantages of triangular and quadrilateral meshes. A robust method for generating a prescribed number of quadrilateral blocks is required for that. We compare different methods for indirect quadrilateral mesh generation and show that a combination of those methods delivers good performance and high quality results. We show the efficiency of our hybrid approach on ocean meshes with up to several million triangles.


Our research on BSG generation has shown that Ocean domains are often too complex to be represented accurately by BSGs. We extend our method by masking elements, which enables accurate representation of fractal boundary shapes as we can resolve geometry on a high granularity. The performance of the BSG generation is evaluated on grids constructed for regional ocean problems utilizing two‐dimensional shallow water equations.


\[[publication](https://opus4.kobv.de/opus4-fau/frontdoor/index/index/start/2/rows/20/sortfield/score/sortorder/desc/searchtype/simple/query/high+performance+ocean/docId/17841)\]
\[[pdf](https://opus4.kobv.de/opus4-fau/files/17841/DissertationDanielZint.pdf)\]
\[[code](https://github.com/daniel-zint/hpmeshgen)\]
'
date: 2021-12-01
#venue: "Thesis"
#paperurl: "http://academicpages.github.io/files/paper1.pdf"
#citation: "Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1)."
---

**Author(s):** D. Zint

**Abstract:** In high‐performance computing, block‐structured grids are favored due to their geometric adaptability while supporting computational performance optimizations connected with structured grid discretizations. However, many problems on geometrically complex domains are traditionally solved using fully unstructured meshes. We address this deficiency in the two‐dimensional case by presenting a method which generates block‐structured grids (BSGs) with a prescribed number of blocks from an arbitrary triangular grid.

Each block in a BSG contains a structured grid. Vertex repositioning is one of the key operations for adapting a structured grid to a domain. We present an algorithm called discrete mesh optimization (DMO), a greedy approach to topology‐consistent mesh quality improvement. The method optimizes vertex positions according to a user defined quality metric. It is easily adaptable to any mesh and metric as it does not rely on differentiable functions. We give examples for triangle, quadrilateral, and tetrahedral meshes and for various metrics. We show that DMO outperforms other state of the art methods in terms of convergence and runtime.

We generate BSGs consisting of quadrilateral blocks which contain structured triangle grids. This design combines advantages of triangular and quadrilateral meshes. A robust method for generating a prescribed number of quadrilateral blocks is required for that. We compare different methods for indirect quadrilateral mesh generation and show that a combination of those methods delivers good performance and high quality results. We show the efficiency of our hybrid approach on ocean meshes with up to several million triangles.

Our research on BSG generation has shown that Ocean domains are often too complex to be represented accurately by BSGs. We extend our method by masking elements, which enables accurate representation of fractal boundary shapes as we can resolve geometry on a high granularity. The performance of the BSG generation is evaluated on grids constructed for regional ocean problems utilizing two‐dimensional shallow water equations.

\[[publication](https://opus4.kobv.de/opus4-fau/frontdoor/index/index/start/2/rows/20/sortfield/score/sortorder/desc/searchtype/simple/query/high+performance+ocean/docId/17841)\]
\[[pdf](https://opus4.kobv.de/opus4-fau/files/17841/DissertationDanielZint.pdf)\]
\[[code](https://github.com/daniel-zint/hpmeshgen)\]
