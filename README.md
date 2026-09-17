# High Performance Computing

Graded assignments and weekly work for PHAS0102 — sparse linear algebra, iterative solvers
and performance optimisation in Python.

**PHAS0102, 4th year · University College London (2023)**

![Python](https://img.shields.io/badge/Python-3.x-blue)
![NumPy](https://img.shields.io/badge/NumPy-Numba-013243)
![Topic](https://img.shields.io/badge/topic-sparse%20solvers-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview

The module's through-line is that a correct algorithm is not the same as a usable one. Each
assignment takes a numerical method, implements it, verifies it against a known result, and
then measures where the time and memory actually go.

## Assignments

| Assignment | Content |
| --- | --- |
| 1 | Profiling and optimising a slow function — assert-based correctness testing, timing, plotting |
| 2 | Solutions to the time-harmonic wave equation |
| 3 | Implementing a **CSR sparse matrix** from scratch, with validity checks against a reference |
| 4 | Solving a **finite element system** — matrix and vector assembly, then solution |

## Weekly work

| Week | Content |
| --- | --- |
| 1–2 | Assert testing, timing methodology, function storage |
| 3–4 | Matrix routines — memory and time cost analysis |
| 5 | **GMRES** — basic use and experimentation |
| 6 | **Conjugate gradient** via SciPy, and the SPAI preconditioning technique |
| 7 | Matrix construction exercises |

## Author

Harvey Bermingham — MSci Physics, University College London

## License

Released under the MIT License. See [LICENSE](LICENSE).
