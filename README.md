# Tumor Perturbation & Multimodal Analysis

This repository contains notebooks for analyzing tumor perturbation, spatial transcriptomics, and multimodal single-cell data, based on recent *Cell* studies and open-source perturbation models.

## Contents

- **`astro-scanpy.ipynb`**
  Scanpy-based single-cell analysis for astrocyte dataset
  Reference: https://scanpy.readthedocs.io/en/stable/index.html
  Output: https://1drv.ms/f/c/be6fca71af648e68/IgBIV_njwPE0RpMlvsCDoxK5Ad6VMCFix7K5hh8vvWWgLFk?e=NxtOEO 

- **`tumor.ipynb`**  
  Tumor perturbation and spatial analysis  
  Reference: https://www.cell.com/cell/fulltext/S0092-8674(25)00197-7

- **`tumor_contrastiveVI.ipynb`**  
  Tumor vs background modeling using contrastiveVI  
  Reference: https://github.com/suinleelab/contrastiveVI/tree/main

- **`FR-Perturb/`**  
  FR-Perturb framework for Perturb-seq effect estimation  
  Reference: https://github.com/douglasyao/FR-Perturb/tree/main

- **`Perturb-Multimodal.ipynb`**  
  Multimodal perturbation analysis (imaging + sequencing)  
  Reference: https://www.cell.com/cell/fulltext/S0092-8674(25)00572-0

## Data

- SSPsyGene (UCSC): https://sspsygene.ucsc.edu/data/
  - astrocyte dataset: https://download.brainimagelibrary.org/0c/bd/0cbd479c521afff9/
  - tumor dataset: https://download.brainimagelibrary.org/0c/bd/0cbd479c521afff9/extras/
