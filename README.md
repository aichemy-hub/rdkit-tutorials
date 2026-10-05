# RDKit Tutorials

Tutorials on using the [RDKit](http://www.rdkit.org).

**Course website:** https://dylancjohn.github.io/rdkit-tutorials/

The notebooks run in the browser on Google Colab, so there's nothing to install. Click a badge
below, then run the setup cell at the top of the notebook.

## Course notebooks

| | Notebook | |
| --- | --- | --- |
| 1 | [Writing SMILES](notebooks/001_ReadingMolecules1.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dylancjohn/rdkit-tutorials/blob/master/notebooks/001_ReadingMolecules1.ipynb) |
| 2 | [SMARTS and substructure matching](notebooks/002_SMARTS_SubstructureMatching.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dylancjohn/rdkit-tutorials/blob/master/notebooks/002_SMARTS_SubstructureMatching.ipynb) |
| 3 | [RDKit and pandas](notebooks/003_RDKit_pandas_support.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dylancjohn/rdkit-tutorials/blob/master/notebooks/003_RDKit_pandas_support.ipynb) |
| 4 | [Exploring chemical space](notebooks/004_Chemical_space_analysis_and_visualization.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dylancjohn/rdkit-tutorials/blob/master/notebooks/004_Chemical_space_analysis_and_visualization.ipynb) |
| 5 | [From molecules to a machine-learning model](notebooks/005_RDKit_Machine_Learning.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dylancjohn/rdkit-tutorials/blob/master/notebooks/005_RDKit_Machine_Learning.ipynb) |

## Editing the website

The website is built from the notebooks with [Jupyter Book](https://jupyterbook.org) and is
rebuilt automatically by GitHub Actions on every push to `master`
(see `.github/workflows/deploy-book.yml`). To preview it locally:

```bash
pip install -r requirements-book.txt
jupyter-book build .
```

Then open `_build/html/index.html`. The landing page is `intro.md` and the page order is set in `_toc.yml`.
