# JessaBrainData_CNN

This repository uses single-cell RNA sequencing data from pediatric brain tumor samples to classify cancer subtypes based on gene expression profiles of individual cells.
This script trains a convolutional neural netword to predict which cells are likely to exhibit resistance to chemotherapy based on their expression patterns. 

### Data
This script uses the mouse brain single-cell RNA-seq dataset from Jessa et al. (2019)
The dataset contains >65.000 cells (61.595 mouse, 3.945 cryopreserved human cells). 
Link to full text pdf: https://pmc.ncbi.nlm.nih.gov/articles/PMC6885128/

### Run script
In order to run this script, make sure you have PyTorch installed. You also need `anndata` to convert the dataset to AnnData format (`.h5ad`)

`
pip install torch anndata
`

You need to install several R packages to download JessaBrainData from the Bioconductor software:

`Bioconductor`: For accessing the dataset

`SingleCellExperiment`: To handle single-cell data

`reticulate`: for Python-R interface



