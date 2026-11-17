# 2026_HW_iEEG_WM

Analysis scripts for the paper:

> **White matter connection abnormalities in seizure networks: associations with surgical outcome**
> Hao Wang, Jonathan Horsley, Gerard Hall, Fahmida A. Chowdhury, Beate Diehl, John S. Duncan, Andrew W. McEvoy, Anna Miserocchi, Jane de Tisi, Yujiang Wang, Peter N. Taylor.
> *Epilepsia* (2026). https://doi.org/10.1002/epi.70631

## Contents

| Folder | Analysis |
|---|---|
| `result1/` | Result 1: probability of a structural connection being present between involved, not-involved, and not-implanted regions (logistic GLM with patient-clustered standard errors) |
| `result2/` | Result 2: white matter connection abnormality (MD z-scores) across connection types and surgical outcome groups (linear mixed effects model) |
| `result3/` | Result 3: patient-level discrimination of surgical outcome from mean connection abnormality (Wilcoxon rank-sum tests, AUROC) |

Analyses were performed in R (version 4.4.2).

## Data availability

The data used in this study are not publicly available. Data are available from the authors upon reasonable request.

## Contact

Hao Wang, CNNP Lab, Newcastle University (h.wang118@newcastle.ac.uk)
