# 2026_SkeletalMuscleAging

This repository contains the code and data analysis tools for age-associated molecular features and their enrichments in the FUSION single nucleus skeletal muscle data

## Contents

This project covers two nextflow pipelines for detecting age-associated molecular features by cell type and sex:
1. Differentially expressed genes (DEGs) using MAST
2. Differenitally accessible chromatin regions (DARs) using GLMMNB

These sets of age-associated molecular features are then tested for the following enrichments:
1. DEGs in KEGG terms using RNA Enrich
2. DARs in KEGG terms using chipenrich
3. DARs in chromatin states using roadmap samples and logistic regression
4. DARs in transcription factor motifs using 3 prior databases and logistic regression
