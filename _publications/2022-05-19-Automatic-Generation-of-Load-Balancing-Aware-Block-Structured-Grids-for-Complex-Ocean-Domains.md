---
title: "Automatic Generation of Load-Balancing-Aware Block-Structured Grids for Complex Ocean Domains"
collection: publications
permalink: /publication/2022-05-19-Automatic-Generation-of-Load-Balancing-Aware-Block-Structured-Grids-for-Complex-Ocean-Domains
date: 2022-05-19
venue: "Proceedings of the 2022 SIAM International Meshing Roundtable"
#paperurl: "http://academicpages.github.io/files/paper1.pdf"
#citation: "Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1)."
---

**Author(s):** D. Zint, R. Grosso, V. Aizinger, S. Faghih-Naini, S. Kuckuk, H. Köstler

**Abstract:** Many high-performance computing applications involve sophisticated finite element simulations on complex domains and, for this reason, often cannot use a single structured grid for the entire domain. A popular alternative are block-structured grids (BSGs) that are more flexible geometrically but still offer a significant amount of structure. However, the standard generation process for BSGs relies heavily on manual input to define the segmentation of the computational domain – a rather difficult task to perform for complex geometries. Ocean domains often contain fractal boundary shapes and details such as islands and channels that cannot be accurately represented using BSGs. We present a method to automatically generate BSGs with an exactly specified number of blocks for real-world domains arising in 2D ocean simulations. Our BSGs consist of quad blocks refined via structured triangular grids and employ masks to accurately represent small features. The performance of the proposed BSG generation method is evaluated for realistic ocean domains and validated using simulations of the two-dimensional shallow water equations discretized by the discontinuous Galerkin method.

\[[publication](https://zenodo.org/record/6562440)\]
\[[pdf](https://internationalmeshingroundtable.com/assets/papers/2022/03-Zint-compressed.pdf)\]
\[[code](https://github.com/daniel-zint/hpmeshgen)\]
