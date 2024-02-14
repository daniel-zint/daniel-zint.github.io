---
title: "A parallel dual marching cubes approach to quad only surface reconstruction"
collection: publications
permalink: /publication/2022-02-01-A-parallel-dual-marching-cubes-approach-to-quad-only-surface-reconstruction
date: 2022-02-01
venue: "Vis Comput 38, 1301–1316"
#paperurl: "http://academicpages.github.io/files/paper1.pdf"
#citation: "Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1)."
---

**Author(s):** R. Grosso, D. Zint

**Abstract:** We present a novel method that reconstructs surfaces from volume data using a dual marching cubes approach without lookup tables. The method generates quad only meshes which are consistent across cell borders, i.e., they are manifold and watertight. Vertices are positioned exactly on the reconstructed surface almost everywhere, leading to higher accuracy than other reconstruction methods. A halfedge data structure is used for storing the meshes which is convenient for further processing. The method processes elements in parallel and therefore runs efficiently on GPU. Due to the transition between layers in volume data, meshes have numerous vertices with valence three. We use simplification patterns for eliminating quads containing these vertices wherever possible which reduces the number of elements and increases quality. We briefly describe a CUDA implementation of our method, which allows processing huge amounts of data on GPU at almost interactive time rates. Finally, we present runtime and quality results of our method on medical and synthetic data sets.

\[[publication](https://rdcu.be/df78O)\]
\[[code](https://github.com/rogrosso/tmc)\]
