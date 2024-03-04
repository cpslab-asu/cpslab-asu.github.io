+++
title = 'Part-X: A family of stochastic algorithms for search-based test generation with probabilistic guarantees'
description = 'Stochastic algorithm for search-based test generation with probabalistic guarantees.'
date = 2023-08-15
draft = false
+++

## Abstract

Requirements driven search-based testing (also known as falsification) has
proven to be a practical and effective method for discovering erroneous
behaviors in Cyber-Physical Systems. Despite the constant improvements on the
performance and applicability of falsification methods, they all share a common
characteristic. Namely, they are best-effort methods which do not provide any
guarantees on the absence of erroneous behaviors (falsifiers) when the testing
budget is exhausted. The absence of finite time guarantees is a major limitation
which prevents falsification methods from being utilized in certification
procedures. In this paper, we address the finite-time guarantees problem by
developing a new stochastic algorithm. Our proposed algorithm not only estimates
(bounds) the probability that falsifying behaviors exist, but also identifies the
regions where these falsifying behaviors may occur. We demonstrate the
applicability of our approach on standard benchmark functions from the
optimization literature and on the F16 benchmark problem.

Note to Practitioners — The safety assurance problem for Cyber-Physical Systems
(CPS) remains an open challenge. To demonstrate functional safety, practitioners
must collect evidence that establishes that a system performs as expected under
certain assumptions. The expected system behavior is typically captured through
functional correctness requirements. In the case of CPS, evidence typically takes
the form of test cases that are executed both on a model of the system and/or on
the actual system. One of the challenges in producing such evidence is how to
automatically generate test cases which are representative of the infinite
execution space of CPS. Search-based test generation (SBTG) is a class of
methods that can automatically generate test cases for CPS while being guided by
the functional requirements. As SBTG methods try to discover test cases that
invalidate, i.e., falsify, the requirements, they also collect validating, i.e.,
satisfying, test cases that can be used as evidence. This work introduces a
method that can assess whether enough test cases have been executed given a
finite testing budget. The sufficiency of the test suite is assessed by
computing the probability that invalidating system behaviors may exist but have
not yet been discovered. The practitioner can then adjust the number of test
cases generated until a desired degree of confidence on the probability is
achieved. Hence, our method not only works as an automated test case generation
algorithm, but also as a method that provides formal functional performance
guarantees on the system. Future directions will investigate extensions of our
method to stochastic CPS.

## Citation

```biblatex
@article{10219561,
  author={Pedrielli, Giulia and Khandait, Tanmay and Cao, Yumeng and Thibeault, Quinn and Huang, Hao and Castillo-Effen, Mauricio and Fainekos, Georgios},
  journal={IEEE Transactions on Automation Science and Engineering}, 
  title={Part-X: A Family of Stochastic Algorithms for Search-Based Test Generation With Probabilistic Guarantees}, 
  year={2023},
  volume={},
  number={},
  pages={1-22},
  keywords={Optimization;Robustness;Behavioral sciences;Level set;Gaussian processes;Closed box;Test pattern generators;Cyber physical systems;automated test generation;probabilistic guarantees;Bayesian optimization;Gaussian processes;statistical learning},
  doi={10.1109/TASE.2023.3297984}}
```

## Links

[Paper](https://ieeexplore.ieee.org/abstract/document/10219561)
[Repo](https://github.com/cpslab-asu/part-x)
[Package](https://pypi.org/project/partx)
