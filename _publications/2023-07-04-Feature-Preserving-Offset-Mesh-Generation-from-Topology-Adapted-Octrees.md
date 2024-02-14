---
title: "Feature-Preserving Offset Mesh Generation from Topology-Adapted Octrees"
collection: publications
permalink: /publication/2023-07-04-Feature-Preserving-Offset-Mesh-Generation-from-Topology-Adapted-Octrees
date: 2023-07-04
venue: "Computer Graphics Forum"
#paperurl: "http://academicpages.github.io/files/paper1.pdf"
#citation: "Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1)."
---

**Author(s):** D. Zint, N. Maruani, M. Rouxel-Labbé, P. Alliez

**Abstract:** We introduce a reliable method to generate offset meshes from input triangle meshes or triangle soups. Our method proceeds in two steps. The first step performs a Dual Contouring method on the offset surface, operating on an adaptive octree that is refined in areas where the offset topology is complex. Our approach substantially reduces memory consumption and runtime compared to isosurfacing methods operating on uniform grids. The second step improves the output Dual Contouring mesh with an offset-aware remeshing algorithm to reduce the normal deviation between the mesh facets and the exact offset. This remeshing process reconstructs concave sharp features and approximates smooth shapes in convex areas up to a user-defined precision. We show the effectiveness and versatility of our method by applying it to a wide range of input meshes. We also benchmark our method on the Thingi10k dataset: watertight and topologically 2-manifold offset meshes are obtained for 100% of the cases.

\[[publication](https://diglib.eg.org/handle/10.1111/cgf14906)\]
\[[pdf](https://inria.hal.science/hal-04135266/document)\]
\[[presentation](/files/Daniel Zint - Feature-Preserving Offset Mesh Generation from Topology-Adapted Octrees.pptx)\]
\[code (coming soon)\]
