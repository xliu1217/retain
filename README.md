# VAE-RETAIN: AN XAI Model for Temporal Pattern Extraction with Data Imputation

## Description
This project aims to predict if covid-19 patients will need to use the ventilator at last. Our model can output weight for each feature contributing to the final result which could provide a greate sense of explanation to improve patients and doctors understandings. 

## Goal
- Extract the temporal patterns of patients with chrome diseases (our dataset is Covid-19 patients) with weight contributions to the final result.
- Achieve the data imputation to the missing values by modifying VAE model.
- Incorporate VAE model and RETAIN model to generate a end-to-end novel model which is sparsity-aware and provide explainable prediciton results with temporal patterns.

## Data
The data of this project comes from Dell Medical School - Covid-19 dataset which is confidential. We have many csv files which include many medical indications like "RBC Morph", "Albumin Level", "Base Excess Ven" etc. We will pick data related to the use of ventilators to use.

## Reference
- RETAIN Model [https://arxiv.org/pdf/1608.05745.pdf]
- VAE Model [https://arxiv.org/pdf/1312.6114.pdf]



