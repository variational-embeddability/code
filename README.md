# Variational generator estimation

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24275762.svg)](https://doi.org/10.5281/zenodo.24275762)

## Setup

```sh
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -e .
```

[Paper commands](paper/README.md) · [Minimal examples](snippets/README.md)

For the manuscript's Ehrenfest rates figure, use the
[Ehrenfest rates-over-time command](paper/README.md#ehrenfest-rates-over-time-manuscript-figure).
Its defaults use the caption's regularisation weights, `mu0=0.001` and `mu1=3`.
The separate Ehrenfest MISE comparison is an additional experiment.

## Tests

```sh
MPLBACKEND=Agg python -m unittest discover -s tests -v
```

## Citation and archived release

Release **v1.2** is archived on Zenodo:
[10.5281/zenodo.24275762](https://doi.org/10.5281/zenodo.24275762).
Use this version-specific DOI when citing this release. The current development
version is maintained at [variational-embeddability/code](https://github.com/variational-embeddability/code).

The code authors are **George Henderson-Walshe, Rua Murray and Philipp Wacker**.
The archived release is distributed under the MIT licence.
