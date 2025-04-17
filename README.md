The HepatoInsight Platform integrates two gene expression-driven tools: eHCC-pred for early-stage HCC diagnosis and HCC-MSC for molecular subtype classification (C1-C3), enabling comprehensive precision oncology workflows.

The eHCC-pred was developed to diagnose early HCC with gene expression profiles, which contained mRMR+SVM predictor and MRMD+SVM predictor. The results of MRMD+SVM predictor and mRMR+SVM predictor showed high prediction performance (AUC≥0.92) on both training sets and validation data sets, demonstrating that MRMD+SVM predictor and mRMR+SVM predictor have excellent performance in the diagnosis of early HCC at individual level and they would be helpful for improving clinical decision of HCC diagnosis.

TheHCC-MSC was developed to classify HCC into 3 subtypes (C1-C3) using gene expression profiles, with an XGBoost classifier and Randforest classifier. Both classifiers achieved high overall accuracy (≥0.73) on training and validation sets, demonstrating excellent performance in HCC subtype classification.

Notably, drug response analysis based on molecular subtyping revealed distinct therapeutic sensitivities. The C1 subtype showed marked sensitivity to dasatinib and a superior response rate to PD-1 therapy (75% response rate). The C3 subtype exhibited heightened vulnerability to luminespib (an HSP90 inhibitor) and rapamycin (mTOR inhibitor). Transcatheter arterial chemoembolization (TACE) achieved the highest response rate in this subgroup (75.9% response rate).

HepatoInsight Platform Quick Start Guide

1. Download the software package ( [HepatoInsightPlatform.zip](https://github.com/bioinfoHCC/HepatoInsightPlatform/releases/download/HepatoInsightPlatform/HepatoInsightPlatform.zip)  frome Releases )

1. Extract the archive using tools like 7-Zip or WinRAR

3. Execute the installer:

- Open the Rscript directory
- Run setup.bat by double-clicking
