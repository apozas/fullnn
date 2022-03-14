[![DOI](https://www.zenodo.org/badge/367431180.svg)](https://www.zenodo.org/badge/latestdoi/367431180)

## Computational appendix of *[Full network nonlocality](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.128.010403)*
#### Alejandro Pozas-Kerstjens, Nicolas Gisin and Armin Tavakoli

This is a repository containing the computational appendix of the article "*Full network nonlocality*. Alejandro Pozas-Kerstjens, Nicolas Gisin, and Armin Tavakoli. [Phys. Rev. Lett. 128, 010403 (2022)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.128.010403) [[arXiv:2105.09325](https://www.arxiv.org/abs/2105.09325)]." It provides a detailed explanation of how to write the linear programming problems associated to hybrid classical-nonsignaling inflations, and the necessary codes for obtaining the full network Bell inequalities depicted in the manuscript.

All code is written in Python.

Libraries required:
- [mosek](https://www.mosek.com/) for solving the linear programming problems
- [numpy](https://numpy.org/) for numerical manipulations
- [picos](https://picos-api.gitlab.io/picos/) <= 2.2 for setting up the linear programming problems
- [qutip](http://qutip.org/) for quantum mechanical operations
- [sympy](https://www.sympy.org/) for symbolic manipulations

If you would like to cite this work, please use the following format:

A. Pozas-Kerstjens, N. Gisin, and A. Tavakoli, _Full network nonlocality_, Phys. Rev. Lett. **128**, 010403 (2022)

```
@article{fullnn,
  title = {Full Network Nonlocality},
  author = {Pozas-Kerstjens, Alejandro and Gisin, Nicolas and Tavakoli, Armin},
  journal = {Phys. Rev. Lett.},
  volume = {128},
  issue = {1},
  pages = {010403},
  numpages = {6},
  year = {2022},
  month = {Jan},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevLett.128.010403},
  url = {https://link.aps.org/doi/10.1103/PhysRevLett.128.010403}
}
```

