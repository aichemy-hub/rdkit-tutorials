# RDKit Tutorials

Welcome! These notebooks are a hands-on introduction to [RDKit](https://www.rdkit.org), the
open-source toolkit for working with molecules in Python. You don't need to install anything:
every notebook runs in your web browser on Google Colab.

## How to use these notebooks

1. Click an **Open in Colab** button in the table below. (Or open a notebook from the menu on the
   left, then click the **rocket icon** at the top right of the notebook page and choose **Colab**.)
   You'll need to sign in with a Google account.
2. In Colab, choose **File → Save a copy in Drive** so your work is saved.
3. Scroll down to the section called **Setup**, just below the notebook's introduction. Click the
   code cell there (it starts with `# Setup for Google Colab`) and press **Shift + Enter** to run it.
   This installs RDKit and downloads the data files, and takes about 30 seconds. Do this every time
   you open a notebook in Colab.
4. Then work from top to bottom, running each cell with **Shift + Enter**.

Cells marked **Exercise** are for you to try. A hidden solution follows each one. Click
"Solution" to show it, but have a go first!

## Notebooks

| | Notebook | What you'll learn | |
| --- | --- | --- | --- |
| 1 | [Writing SMILES](notebooks/001_ReadingMolecules1.ipynb) | Turning text into molecules, drawing them, atoms and bonds | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dylancjohn/rdkit-tutorials/blob/master/notebooks/001_ReadingMolecules1.ipynb) |
| 2 | [SMARTS and substructure matching](notebooks/002_SMARTS_SubstructureMatching.ipynb) | Searching molecules for functional groups | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dylancjohn/rdkit-tutorials/blob/master/notebooks/002_SMARTS_SubstructureMatching.ipynb) |
| 3 | [RDKit and pandas](notebooks/003_RDKit_pandas_support.ipynb) | Working with tables of molecules and descriptors | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dylancjohn/rdkit-tutorials/blob/master/notebooks/003_RDKit_pandas_support.ipynb) |
| 4 | [Exploring chemical space](notebooks/004_Chemical_space_analysis_and_visualization.ipynb) | Fingerprints, similarity and PCA plots | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dylancjohn/rdkit-tutorials/blob/master/notebooks/004_Chemical_space_analysis_and_visualization.ipynb) |
| 5 | [From molecules to a machine-learning model](notebooks/005_RDKit_Machine_Learning.ipynb) | Predicting blood–brain barrier permeability | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dylancjohn/rdkit-tutorials/blob/master/notebooks/005_RDKit_Machine_Learning.ipynb) |

Each notebook builds on the ones before it, so work through them in order.

## Running on your own computer

If you'd rather work locally, clone the
[GitHub repository](https://github.com/dylancjohn/rdkit-tutorials), install the packages, and
open the notebooks in Jupyter or VS Code:

```bash
pip install rdkit pandas numpy matplotlib scikit-learn jupyter
```
