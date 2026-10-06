# RDKit Tutorials

Welcome! These notebooks are a hands-on introduction to [RDKit](https://www.rdkit.org), the
open-source toolkit for working with molecules in Python. You don't need to install anything:
every notebook runs in your web browser on Google Colab.

**Course website:** https://aichemy-hub.github.io/rdkit-tutorials/

## How to use these notebooks

1. Click an **Open in Colab** button in the table below. (Or, on the course website, open a notebook
   from the menu on the left, then click the **rocket icon** at the top right of the notebook page and choose **Colab**.)
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
| 1 | [Writing SMILES with RDKit](notebooks/01_writing_smiles.ipynb) | Turning text into molecules, drawing them, atoms and bonds | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aichemy-hub/rdkit-tutorials/blob/master/notebooks/01_writing_smiles.ipynb) |
| 2 | [SMARTS and substructure matching](notebooks/02_smarts_substructure_matching.ipynb) | Searching molecules for functional groups | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aichemy-hub/rdkit-tutorials/blob/master/notebooks/02_smarts_substructure_matching.ipynb) |
| 3 | [RDKit and pandas](notebooks/03_rdkit_and_pandas.ipynb) | Working with tables of molecules and descriptors | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aichemy-hub/rdkit-tutorials/blob/master/notebooks/03_rdkit_and_pandas.ipynb) |
| 4 | [Exploring chemical space](notebooks/04_chemical_space.ipynb) | Fingerprints, similarity and PCA plots | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aichemy-hub/rdkit-tutorials/blob/master/notebooks/04_chemical_space.ipynb) |
| 5 | [From molecules to a machine-learning model](notebooks/05_machine_learning.ipynb) | Predicting blood–brain barrier permeability | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aichemy-hub/rdkit-tutorials/blob/master/notebooks/05_machine_learning.ipynb) |

Each notebook builds on the ones before it, so work through them in order.

## Running on your own computer

If you'd rather work locally, clone the
[GitHub repository](https://github.com/aichemy-hub/rdkit-tutorials), install the packages, and
open the notebooks in Jupyter or VS Code:

```bash
pip install rdkit pandas numpy matplotlib scikit-learn jupyter
```

## Credits and licence

This course is maintained by Pablo Graf and Dylan John. Notebooks 1–4 are adapted from the
[RDKit tutorials](https://github.com/rdkit/rdkit-tutorials):

- Notebook 1 from "Reading and writing molecules 1" by Greg Landrum (2016)
- Notebook 2 from "SMARTS substructure matching" by Curt Fischer (2016)
- Notebooks 3 and 4 from "RDKit pandas support" and "Chemical space analysis and visualization" by Samo Turk (2017)

Notebook 5 was adapted from Notebook 3 of Dan Davies' [Intro to ML for Chemists](https://aichemy-hub.github.io/intro_to_ml_for_chemists/) course

As with the original tutorials, this work is licensed under the
[Creative Commons Attribution-ShareAlike 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/).
See [LICENSE](https://github.com/aichemy-hub/rdkit-tutorials/blob/master/LICENSE).
