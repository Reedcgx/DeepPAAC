# DeepPAAC: Deep Principal-Agent Actor-Critic Algorithm

This repository contains the implementation of **DeepPAAC** (Deep Principal-Agent Actor-Critic), a novel deep learning approach for solving Hamilton-Jacobi-Bellman (HJB) equations arising in continuous-time principal-agent problems. This code implements **Section 4.3 and Section 4.4** from the paper:

> **DeepPAAC: A New Deep Galerkin Method for Principal-Agent Problems**  
> Michael Ludkovski, Changgen Xie, Zimu Zhu  
> arXiv preprint: [https://arxiv.org/pdf/2511.04309](https://arxiv.org/pdf/2511.04309)

## Overview

We consider numerical resolution of principal-agent (PA) problems in continuous time. We formulate a generic PA model with **continuous and lump payments** and a **multi-dimensional strategy of the agent**. To tackle the resulting Hamilton-Jacobi-Bellman equation with an **implicit Hamiltonian**, we develop the DeepPAAC Actor-Critic algorithm.

This project extends and innovates upon the Deep Galerkin Method (DGM) originally proposed by Sirignano and Spiliopoulos. The implementation is inspired by and builds upon the codebase from [alialaradi/DeepGalerkinMethod](https://github.com/alialaradi/DeepGalerkinMethod), with significant modifications and innovations to handle the unique challenges of principal-agent problems.


## Requirements

### Dependencies

```
tensorflow >= 2.15
```

## Citation

```bibtex
@article{ludkovski2025deeppaacnewdeepgalerkin,
  title={DeepPAAC: A New Deep Galerkin Method for Principal-Agent Problems}, 
  author={Michael Ludkovski and Changgen Xie and Zimu Zhu},
  year={2025},
  eprint={2511.04309},
  archivePrefix={arXiv},
  url={https://arxiv.org/abs/2511.04309}
}
```

## Acknowledgments

This implementation builds upon the Deep Galerkin Method framework from:
- A. Al-Aradi, A. Correia, D. Naiff, G. Jardim, and Y. F. Saporito, "Extensions of the deep Galerkin method," *Applied Mathematics and Computation*, vol. 430, p. 127287, 2022. [arXiv:1912.01455](https://arxiv.org/abs/1912.01455), [GitHub repository](https://github.com/alialaradi/DeepGalerkinMethod)
- Sirignano, J. and Spiliopoulos, K., "DGM: A deep learning algorithm for solving partial differential equations," *Journal of Computational Physics*, 2018.
