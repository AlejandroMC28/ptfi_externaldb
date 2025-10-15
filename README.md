# Mapping the Origins of Molecular Signals in Food

**Alejandro Mendoza Cantu, Julia M. Gauglitz, Wout Bittremieux**

Integrative analysis of the PTFI dataset, linking ~24,000 molecular features across 500 foods to curated chemical databases.

## Overview

Analysis of xenobiotic compounds, fluorinated substances, and bioactive molecules in food using untargeted LC-MS metabolomics data from the Periodic Table of Food Initiative and external chemical databases.


## Notebooks

- `database_matching.ipynb` - Matching to DrugBank, FCCdb, PubChem, Supernatural, Lotus and Coconut
- `natural_product_matching.ipynb` - Matching to Natural product databases: Supernatural, Lotus and Coconut
- `non_natural_formulas.ipynb` - Finding formulas that do not match to any of the natural product databases in the project.
- `ptfi_analysis.ipynb` 

## Data

PTFI dataset: 500 foods, 24,721 features (900 annotated, 23,821 formula-only)

**Access**: https://pmp.heart.org/ (PTFI online platform)

**Note**: Raw data not included in this repository.

## Requirements

Python 3.12 with: pandas (2.2.3), numpy, matplotlib (3.9.3), seaborn (0.13.2), scikit-learn (1.7.0), scipy, jupyter

## Citation
```
Mendoza Cantu, A., Gauglitz, J.M., Bittremieux, W. (2025). 
Mapping the origins of molecular signals in food by integrative 
analysis of untargeted metabolomics with chemical databases. 
[Manuscript in preparation]
```

## Acknowledgments

PTFI 2024 Data Challenge | Research Foundation – Flanders (FWO G0AGQ24N)

**Contact**: wout.bittremieux@uantwerpen.be