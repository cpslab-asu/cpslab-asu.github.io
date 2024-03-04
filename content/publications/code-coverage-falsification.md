+++
title = 'Search Based Testing for Code Coverage and Falsification in Cyber-Physical Systems'
description = 'Python source code instrumentation to improve coverage of generated tests.'
date = 2023-08-26
draft = false
+++

## Abstract

State of the art test case generation tools vary in the way they exploit
knowledge of the system under test. While experimental results demonstrate that
such knowledge can improve the efficiency of the test case generation process,
how to (automatically) retrieve and integrate such information in test
generation is non-trivial. Especially, in the case of Cyber-Physical Systems
(CPS), the problem is more challenging since CPS have not only software
requirements but also physical functional requirements. In this work, we
instrument a system's source code to extract run-time information related to the
behavior of the system to determine the path taken through the source code
itself. Given our focus on CPS, this information enables us to compute a metric
representing the total coverage of the system behaviors for a series of inputs.
We present the framework to instrument the code, and our method for using the
instrumented code to calculate coverage-related robustness. We also demonstrate
how to integrate this approach into a search to generate tests that can manage
the trade-off between code coverage and identification of functionally unsafe
behaviors (falsification). Our results show that our approach is more efficient
than Uniform Random sampling in covering CPS operating modes (code). In
addition, we show that our approach promotes better falsifications when
violating inputs are present in a, possibly small, subset of the CPS states.

## Citation

```biblatex
@inproceedings{10260576,
  author={Thibeault, Quinn and Khandait, Tanmay and Pedrielli, Giulia and Fainekos, Georgios},
  booktitle={2023 IEEE 19th International Conference on Automation Science and Engineering (CASE)}, 
  title={Search Based Testing for Code Coverage and Falsification in Cyber-Physical Systems}, 
  year={2023},
  volume={},
  number={},
  pages={1-8},
  keywords={Measurement;Codes;Instruments;Source coding;Cyber-physical systems;Software;Robustness},
  doi={10.1109/CASE56687.2023.10260576}}
```

## Links

[Paper](https://ieeexplore.ieee.org/abstract/document/10260576)
[Repo](https://github.com/cpslab-asu/branch-statement-analyzer)
[Package](https://pypi.org/project/branch-statement-analyzer)
