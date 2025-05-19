# Exploring-Key-Determinants-of-Halitosis-Through-a-Data-Analysis

This repository contains the official code for the study  
**"Predicting Subjective Halitosis Using Tabular Health Data and Transformer-based Models"**  
by Yeon-Hee Lee, Seongwoo Jang, Seonggwang Jeon, Tae-Seok Kim, and David Keith.  
The repository includes data preprocessing, model training, evaluation, and visualization modules for predicting subjective halitosis using machine learning and deep learning algorithms.

## Repository Structure

Halitosis_Prediction/
├── preprocessing/
│ └── preprocess.py # Data cleaning and feature engineering
├── modeling/
│ ├── train_classical_models.py # XGBoost, Random Forest, Logistic Regression
│ ├── train_transformers.py # TabTransformer, FT-Transformer, SAINT, TabNet
│ └── stacking_ensemble.py # Meta-learning with Logistic Regression
├── evaluation/
│ ├── evaluate_metrics.py # AUROC, Accuracy, F1-Score, Confusion Matrix
│ ├── delong_test.py # Statistical significance testing (p-values)
│ └── attention_analysis.py # Visualization of feature pair attention
├── visualization/
│ └── roc_plot_with_ci.py # ROC curve with 95% CI
├── plots/ # Contains saved ROC curves and heatmaps
├── requirements.txt
└── README.md
