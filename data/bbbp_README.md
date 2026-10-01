# BBBP dataset for notebook 5

`bbbp.csv` is an unmodified copy of the file used by the BBBP task in `workshop-3.ipynb`.

- Source: https://deepchemdata.s3-us-west-1.amazonaws.com/datasets/BBBP.csv
- Downloaded: 2026-10-01.
- Dataset context: https://deepchem.readthedocs.io/en/latest/api_reference/moleculenet.html#bbbp-datasets
- Benchmark paper: Wu et al., *MoleculeNet: a benchmark for molecular machine learning*, https://doi.org/10.1039/C7SC02664A.
- Original file: 2,050 rows; columns `num`, `name`, `p_np`, `smiles`.
- Labels: `p_np=1` for BBB-penetrating and `p_np=0` for non-penetrating, as recorded in this dataset.
- SHA-256: `d07a38487aeac5cee5508413e468043ef3097451d2a112701c2d60be9ec6b662`.

Notebook 5 performs cleaning in memory, reports removed records, and keeps this source file intact. It removes unreadable SMILES, excludes canonical structures with conflicting labels, and keeps one record per remaining canonical structure. Salts and tautomers are not standardised. The main demonstration uses a stratified random split; it is not a reproduction of the MoleculeNet scaffold-split benchmark.
