# Kaggle-Prj-Open-Problems-Multimodal-Single-Cell-Integration
Kaggle-Prj-Open-Problems-Multimodal-Single-Cell-Integration

-----

#Final Submission Deadline

November 15, 2022

-----

## Goal of the Competition

The goal of this competition is to predict how DNA, RNA, and protein measurements co-vary in single cells as bone marrow stem cells develop into more mature blood cells. 

You will develop a model trained on a subset of 300,000-cell time course dataset of CD34+ hematopoietic stem and progenitor cells (HSPC) from four human donors at five time points generated for this competition by Cellarity, a cell-centric drug creation company.

-----

## Evaluation

We use the Pearson correlation coefficient to rank submissions. For each observation in the Multiome data set, we compute the correlation between the ground-truth gene expressions and the predicted gene expressions. For each observation in the CITEseq data set, we compute the correlation between ground-truth surface protein levels and predicted surface protein levels. The overall score is the average of each sample's correlation score. If a sample's predictions are all the same, the correlation for that sample is scored as -1.0.


- Pearson correlation coefficient

https://en.wikipedia.org/wiki/Pearson_correlation_coefficient

-----
