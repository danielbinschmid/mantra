# MANTRA: Manifold Triangulations Assembly

[![Maintainability](https://api.codeclimate.com/v1/badges/82f86d7e2f0aae342055/maintainability)](https://codeclimate.com/github/aidos-lab/MANTRA/maintainability) ![GitHub contributors](https://img.shields.io/github/contributors/aidos-lab/MANTRA) ![GitHub](https://img.shields.io/github/license/aidos-lab/MANTRA)

## Getting the Dataset

The raw datasets, consisting of the 2 and 3 manifolds with up to 10
vertices, can be downloaded under releases. A pytorch geometric wrapper
for the dataset is installable via the following command.

```{python}
pip install "git+https://github.com/aidos-lab/MANTRADataset/#subdirectory=mantra"
```

After installation the dataset can be used with the follwing snippet.

```{python}
from mantra.simplicial import SimplicialDataset

dataset = SimplicialDataset(root="./data", manifold="2")
```

## Folder Structure

## Design Decisions
