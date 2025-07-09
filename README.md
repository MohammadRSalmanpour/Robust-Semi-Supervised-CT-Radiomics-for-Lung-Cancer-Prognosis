# Robust-Semi-Supervised-CT-Radiomics-for-Lung-Cancer-Prognosis  
**Robust Semi-Supervised CT Radiomics for Lung Cancer Prognosis: Cost-Effective Learning with Limited Labels and SHAP Interpretation**  

## 📌 Overview  
This repository contains the code and supplementary materials for the paper:  
*"Robust Semi-Supervised CT Radiomics for Lung Cancer Prognosis: Cost-Effective Learning with Limited Labels and SHAP Interpretation"*  
by Mohammad R. Salmanpour et al.  

The study proposes a semi-supervised learning (SSL) framework to predict lung cancer prognosis using CT radiomics features, achieving superior performance with limited labeled data. Key contributions include:  

- Leveraging both labeled and unlabeled CT scans from 13 public datasets  
- Benchmarking 56 feature selection/extraction methods and 27 classifiers  
- Demonstrating SSL's robustness via SHAP interpretability and external validation  

## 📂 Repository Structure  
├── Classification_Code/          # Python scripts for supervised (SL) and semi-supervised (SSL) learning  
├── SHAP_Analysis/                # Code for SHAP-based feature importance analysis  
├── Supplemental_File_1.xlsx      # Detailed SL results (metrics, hyperparameters, selected features)  
├── Supplemental_File_2.xlsx      # Detailed SSL results (metrics, hyperparameters, selected features)  
├── README.md                     # This file  
 

## 📊 Key Results  
- SSL outperformed SL: Achieved 0.90±0.01 accuracy (cross-validation) and 0.88±0.01 (external testing)  
- Data efficiency: SSL maintained high performance with only 10% labeled data  
- Top model: FIRF + XGBoost (see `Supplemental_File_2.xlsx`)  

## 📖 Supplemental Files  
**`Supplemental_File_1.xlsx`**:  
- Sheet 1: SL performance metrics (Accuracy, AUC, etc.)  
- Sheet 3: Optimal hyperparameters for SL models  
- Sheet 4: Selected features per FSA/AEA  

**`Supplemental_File_2.xlsx`**:  
- Parallel sheets for SSL results  

## ⁉️ Support  
For questions, contact:  
Mohammad R. Salmanpour: msalman@bccrc.ca  
