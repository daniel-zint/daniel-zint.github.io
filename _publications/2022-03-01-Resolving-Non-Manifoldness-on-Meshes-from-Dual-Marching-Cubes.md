---
title: "Resolving Non-Manifoldness on Meshes from Dual Marching Cubes"
collection: publications
permalink: /publication/2022-03-01-Resolving-Non-Manifoldness-on-Meshes-from-Dual-Marching-Cubes
date: 2022-03-01
venue: "Eurographics"
#paperurl: "http://academicpages.github.io/files/paper1.pdf"
#citation: "Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1)."
---

**Author(s):** D. Zint, P. Gürtler, R. Grosso

**Abstract:** There are several methods that reconstruct surfaces from volume data by generating triangle or quad meshes on the dual of the uniform grid. Those methods often provide meshes with better quality than the famous marching cubes. However, they have a common issue: the meshes are not guaranteed to be manifold. We address this issue by presenting a post-processing routine that resolves all non-manifold edges with local refinement. New vertices are positioned on the trilinear interpolant. We verify our method on a wide range of data sets and show that we are capable of resolving all non-manifold issues.

\[[pdf](https://diglib.eg.org/bitstream/handle/10.2312/egs20221029/045-048.pdf)\]
\[[code](https://github.com/PhiliGuertler/ManifoldDMC)\]
