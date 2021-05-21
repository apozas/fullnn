<!-- [![DOI](https://www.zenodo.org/badge/xxxxxxxxx.svg)](https://www.zenodo.org/badge/latestdoi/xxxxxxxxx) -->

## Computational appendix of *[Full network nonlocality](https://www.arxiv.org/abs/2105.09325)*
#### Alejandro Pozas-Kerstjens, Nicolas Gisin and Armin Tavakoli

This is a repository containing the computational appendix of the article "*Full network nonlocality*. Alejandro Pozas-Kerstjens, Nicolas Gisin, and Armin Tavakoli. [arXiv:2105.09325](https://www.arxiv.org/abs/2105.09325)." It provides a detailed explanation of how to write the linear programming problems associated to hybrid classical-nonsignaling inflations, and the necessary codes for obtaining the full network Bell inequalities depicted in the manuscript.

All code is written in Python.

Libraries required:
- [mosek](https://www.mosek.com/) for solving the linear programming problems
- [numpy](https://numpy.org/) for numerical manipulations
- [picos](https://picos-api.gitlab.io/picos/) for setting up the linear programming problems
- [qutip](http://qutip.org/) for quantum mechanical operations
- [sympy](https://www.sympy.org/) for symbolic manipulations

If you would like to cite this work, please use the following format:

A. Pozas-Kerstjens, N. Gisin, and A. Tavakoli, _Full network nonlocality_, arXiv:2105.09325

```
@misc{fullnn,
author = {Pozas-Kerstjens, Alejandro and Gisin, Nicolas and Tavakoli, Armin},
title = {{Full network nonlocality}},
eprint = {2105.09325},
archivePrefix={arXiv}
}
```

