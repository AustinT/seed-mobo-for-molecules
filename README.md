# Seed multi-objective BO for molecules

A simple multi-objective BO repo for molecules.

## Installation

Start with a standard python environment with numpy/scipy/pandas/etc,
*and* `rdkit`, *and* `PyTDC` (e.g. via `pip install rdkit PyTDC`).

Then, install `kern_gp` by cloning
`https://github.com/AustinT/kernel-only-GP.git`
and adding the directory to `PYTHONPATH`
(e.g. running `export PYTHONPATH=path/to/kernel-only-GP:$PYTHONPATH`).

## Development

Use pre-commit to enforce formatting, large file checks, etc.

If not already installed in your environment, run:

```bash
conda install pre-commit
```

To install the precommit hooks:

```bash
pre-commit install
```

Now a series of useful checks will be run before any commit.
