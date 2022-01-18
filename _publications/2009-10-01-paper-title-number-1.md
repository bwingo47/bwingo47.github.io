---
title: "Tensor Decomposition for Control of Many Systems with Reduced Inputs"
collection: publications
permalink: /publication/tensor_decomposition_for_ control_of_many_systems_with_reduced_inputs
date: 2017-05-30
venue: 'IEEE American Control Conference'
paperurl: 'https://ieeexplore.ieee.org/document/7963128'
citation: 'Q. Huang (B. Wingo) and R. C. Winck &quot;Tensor Decomposition for Control of Many Systems with Reduced Inputs.&quot; <i>IEEE American Control Conference</i> May, 2017, <i>published</i>'
---
<!-- This paper is about the number 1. The number 2 is left for future work.

[Download paper here](http://academicpages.github.io/files/paper1.pdf)

Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->

This paper proposes the use of a multi-dimensional grid to reduce the number of inputs required to control a large set of systems. This can allow for thousands of systems to be controlled by tens of inputs, saving resources and reducing complexity. Tensor decomposition, more specifically canonical decomposition and parallel factorization (CP), is used to determine the control input signals so that they are optimally close to independently controlling all the systems. The tensor decomposition is found using alternating least squares (ALS), and properties of this algorithm are utilized in a passivity proof that provides a way to verify the stability of the feedback system, which we call the CP-ALS System. The performance of the CPALS System is also examined by comparing its system response to that of the same system with independent control. This comparison reveals how the CP-ALS System works and how it is able to maintain nearly the same level of performance for many applications while reducing the number of inputs by potentially multiple orders of magnitude.