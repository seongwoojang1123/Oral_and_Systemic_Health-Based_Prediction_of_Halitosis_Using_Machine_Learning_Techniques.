# Neural Network and Machine Learning Prediction of Halitosis from Oral and Systemic Health Data

This repository contains the official code for the study  
**"Predicting Subjective Halitosis Using Tabular Health Data and Transformer-based Models"**  
by Yeon-Hee Lee, Seongwoo Jang, Seonggwang Jeon, Tae-Seok Kim, and David Keith.  
The repository includes data preprocessing, model training, evaluation, and visualization modules for predicting subjective halitosis using machine learning and deep learning algorithms.

## Project Overview

Halitosis significantly impacts social interaction and quality of life.  
This project explores the potential of structured clinical data to classify individuals with subjective halitosis.

Key aspects include:
- Feature engineering from oral health data
- Classical ML & Transformer-based model comparison
- AUROC and p-value evaluation across 7 feature conditions

## Repository Structure

- DataSet/ 
   - Contains clinical data used for training

- 1_data_preprocessing.ipynb
   - Data cleaning, SMOTE, label encoding

- 2_data_initial_analyze.ipynb
   - EDA and class imbalance checks

- 3_Feature_Importance_Ranking.ipynb
   - Permutation importance, SHAP, etc.

- 4_Model_Training_TEST.ipynb 
  - Model training (XGBoost, TabTransformer, Stacking)

- README.md
  - This file. Provides an overview of the project and instructions for use.
 
##  Models Used

- **Classical Machine Learning**
  - XGBoost, CatBoost, SVM, Random Forest
- **Neural Network Models**
  - TabNet
- **Transformer-Based Models**
  - TabTransformer, FT-Transformer, SAINT
- **Ensemble**
  - Stacking (Meta-Learner: Logistic Regression)

SMOTE was used to handle **class imbalance**, and models were evaluated using both **10-Fold Cross-Validation (for AUROC with 95% CI)** and **5-Fold CV for DeLong’s test** to assess statistical significance between models.

## Contact

For any inquiries or collaboration opportunities:

- Yeon-Hee Lee: omod0209@gmail.com
- SeongWoo Jang: mook8105@cuk.edu
- Seonggwang Jeon: qq22512@hanyang.ac.kr

## Acknowledgments
- This work was supported by the Department of Orofacial Pain and Oral Medicine, Kyung Hee University Dental Hospital, and the Department of Convergence Information Studies, Korea Cyber University.
