---
title: "GSOFA: Scalable Sparse Symbolic LU Factorization on GPUs"
collection: publications
permalink: /publication/2021-05-31-GSOFA
excerpt: 'This paper is about GPU based symbolic factorization for LU decomposition on sparse direct linear solvers.'
date: 2021-05-31
venue: 'IEEE TPDS Special Section: Innovative R&D toward the Exascale Era'
paperurl: 'https://anil-gaihre.github.io/files/GSOFA.pdf'
citation: 'Gaihre, Anil, Xiaoye S. Li, and Hang Liu. "GSOFA: Scalable Sparse LU Symbolic Factorization on GPUs." arXiv preprint arXiv:2007.00840 (2020)'
---
This paper is about GPU based symbolic factorization for LU decomposition sparse solvers. It introduces GSOFA, the first GPU-based symbolic factorization design with the following three optimizations to enable scalable LU symbolic factorization for nonsymmetric pattern sparse matrices on GPUs. First, we introduce a novel fine-grained parallel symbolic factorization algorithm that is well suited for the Single Instruction Multiple Thread (SIMT) architecture of GPUs. Second, we tailor supernode detection into a SIMT friendly process and strive to balance the workload, minimize the communication and saturate the GPU computing resources during supernode detection. Third, we introduce a three-pronged optimization to reduce the excessive space consumption problem faced by multi-source concurrent symbolic factorization.

[Download paper here](https://anil-gaihre.github.io/files/GSOFA.pdf)

Recommended citation: Gaihre, Anil, Hang Liu, and Xiaoye Li. "GSOFA: Scalable Sparse LU Symbolic Factorization on GPUs." IEEE Transactions on Parallel and Distributed Systems (2021).
