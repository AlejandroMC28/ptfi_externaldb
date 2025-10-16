# Mapping the origins of molecular signals in food by integrative analysis of untargeted metabolomics with chemical databases

**Alejandro Mendoza Cantu, Julia M. Gauglitz, Wout Bittremieux**

Integrative analysis of the PTFI dataset, linking ~24,000 molecular features across 500 foods to curated chemical databases.

## Overview

Analysis of the first 500 foods from the Periodic Table of Food Initiative discovery database using external chemical databases to contextualize the findings.

## Notebooks

- **`database_matching.ipynb`** - Matching PTFI features to external databases (DrugBank, FCCdb, PubChem)
- **`natural_product_matching.ipynb`** - Matching to natural product databases (LOTUS, COCONUT, SuperNatural 3)
- **`non_natural_formulas.ipynb`** - Identifying non-natural product formulas

Analysis workflow (executed in PTFI environment):

1. **`ptfi_data_prep.html`** - Data processing and transformation to long format
2. **`ptfi_external_db_matches.html`** - External database matching and visualization (DrugBank, FCCdb, Agrochemical PubChem)
3. **`ptfi_therapeutic_categories.html`** - DrugBank therapeutic categories analysis
4. **`ptfi_f_analysis.html`** - Fluorinated xenobiotics analysis
5. **`ptfi_producers.html`** - Putative Novel producer discoveries

## Data

**PTFI dataset**: 500 foods, 24,721 features (900 annotated, 23,821 formula-only)

**Access**: https://pmp.heart.org/ (PTFI online platform)

**Note**: Raw PTFI data is only accessible through the PTFI platform and is not included in this repository.

## Database requirements

This analysis requires external chemical databases (not included):

- **LOTUS**: [lotus.naturalproducts.net](https://lotus.naturalproducts.net/)
- **COCONUT**: [coconut.naturalproducts.net](https://coconut.naturalproducts.net/download)
- **DrugBank**: [drugbank.ca](https://www.drugbank.ca/) (requires registration)
- **SuperNatural 3**: Natural products database
- **PubChem**: Agrochemicals subset

## Requirements

Python 3.12 with:
```
pandas==2.2.3
numpy
matplotlib==3.9.3
seaborn==0.13.2
scipy
pymongo
lxml
jupyter
```


## Key findings

- Contextualization of the PTFI dataset through external dataset matching
- Distinct xenobiotic fingerprints across food categories  
- Dietary transfer of bioactive compounds
- Putative novel producer discoveries for bioactive natural products

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