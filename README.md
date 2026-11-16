# Variational generator estimation

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
