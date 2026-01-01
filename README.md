# PPG Dataset for COPD Detection Using Deep Learning

This repository provides documentation and reference material for the dataset supporting the manuscript:

**A Hybrid Deep Learning Approach for Chronic Obstructive Pulmonary Disease Diagnosis Using Photoplethysmography Signal**

The repository does not host the full dataset directly due to file size constraints. Instead, it provides dataset access information, structural descriptions, and citation details to support transparency and reproducibility.

---

## Dataset Access

The complete preprocessed photoplethysmography (PPG) dataset is publicly available on Zenodo:

**DOI:** https://doi.org/10.5281/zenodo.18109876  
**Zenodo Record:** https://zenodo.org/records/18109876

Please refer to the Zenodo record to download the full dataset.

---

## Dataset Description

The dataset consists of anonymized photoplethysmography (PPG) signal recordings obtained from clinically screened participants for COPD assessment. The signals were segmented into fixed-length temporal windows and preprocessed using min–max normalization and linear interpolation.

The dataset includes PPG signal segments with the following window lengths:

- 2 seconds  
- 16 seconds  
- 64 seconds  
- 128 seconds  
- 256 seconds  

These segmented signals were used to evaluate deep learning architectures for COPD detection.

All data are provided exclusively as numerical signal arrays. No personally identifiable information, demographic attributes, or sensitive clinical data are included.

---

## Intended Use

This dataset is intended for academic and methodological research in:

- COPD detection and screening studies  
- Deep learning applied to physiological signals  
- Time-series analysis of photoplethysmography data  

The dataset is provided for research and educational purposes only and is **not intended for direct clinical diagnosis or medical decision-making**.

---

## Repository Contents

