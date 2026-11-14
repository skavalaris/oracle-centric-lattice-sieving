# Oracle-centric perspective on structured quantum search applied to lattice sieving: companion notebooks

This repository contains the three Jupyter notebooks that accompany the paper

> S. P. Kavalaris, V. A. Mardiris and I. G. Karafyllidis, *Oracle-centric perspective on structured
> quantum search applied to lattice sieving*.

The notebooks reproduce the worked examples of Section 6 of the paper. Every number reported in
that section is printed by these notebooks.

| Notebook | Content |
|---|---|
| `Example1.ipynb` | Grover realization of the sieving predicate (global oracle), on a simulator and on IBM quantum hardware |
| `Example2.ipynb` | Quantum-walk realization of the same predicate on the Johnson graph J(6,2) (local oracle) |
| `Example3.ipynb` | Comparison of the two realizations and of the three graphs, from which Table 1 and Fig. 1 of the paper are obtained |

Each notebook is self-contained and is saved with its outputs, so the results can be read without
running it.

## Requirements

The notebooks were tested with Python 3.14 and Qiskit 2.6.1.


pip install -r requirements.txt


They run in Jupyter Notebook or in Google Colab. In Colab, uncomment the `%pip install` line at the
top of each notebook.

## Running on IBM quantum hardware

The hardware cell of `Example1.ipynb` is optional and needs an IBM Quantum Platform account. The
API key is entered in a hidden input field when the cell runs, is used only to connect, and is then
deleted. It is never stored in the notebook. All other cells run on a simulator and need no account.

## License

The code is released under the MIT License (see `LICENSE`).

## Citation

If you use these notebooks, please cite the paper and this repository (see `CITATION.cff`).
