---
title: "An Optimization Framework for the Design of Radiofrequency Coils for Magnetic Resonance Imaging"
collection: publications
permalink: /publication/2025-08-04-An-Optimization-Framework-for-the-Design-of-Radiofrequency-Coils-for-Magnetic-Resonance-Imaging
date: 2025-08-04
venue: "bioRxiv"
#paperurl: "http://academicpages.github.io/files/paper1.pdf"
#citation: "Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1)."
---

**Author(s):** J.E.C. Serralles, I. Giannakopoulos, S. Wang, D. Chen, D. Zint, D. Panozzo, D. Zorin, R. Lattanzi

**Abstract:** The radiative characteristics of the radiofrequency receive coils dictate the signal-to-noise ratio (SNR) of magnetic resonance images. Despite the crucial importance of RF coils, the practical coil design process has remained a largely empirical one. This work introduces a novel optimization framework for rational coil design, which relies on a fully automated pipeline that combines rapid electromagnetic simulations, shape optimization and coil meshing. The objective function iteratively maximizes SNR performance in a target region of interest with respect to the ultimate intrinsic SNR, which is the theoretically highest SNR independent from any particular coil design. The forward simulation employs a fast electromagnetic solver based on coupled surface and volume integral equations. The coils are represented as B-spline curves with an associated width, and automatically meshed for EM simulation. We implemented a new method to tune and decouple coils at each iteration without manual user intervention. The algorithm optimizes the size and position of a given number of coils with a combination of grid search and a line search. We demonstrated the framework by designing receive arrays of increasing complexity that yield optimal SNR for different target regions inside a numerical head model. SNR simulation time ranged from 15 s for a 3-coil configuration to 32 s for a 12-coil array, constrained to a helmet-like surface, including tuning and decoupling. The optimized 12-coil geometry yielded 9\% higher average SNR performance in the brain at 3 T. This work represents the first automated coil optimization framework that uses full-wave electromagnetic simulations and ultimate performance benchmarks. This novel approach enables the systematic design of coils for magnetic resonance imaging with significantly improved SNR performance, potentially transforming coil development from empirical design to physics-driven optimization.

\[[publication](https://www.biorxiv.org/content/early/2025/08/06/2025.08.04.668545)\]
\[[pdf](https://www.biorxiv.org/content/early/2025/08/06/2025.08.04.668545.full.pdf)\]
