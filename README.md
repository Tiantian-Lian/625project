# Biostat 625 Final Project: Diabetes Risk Prediction
- Project Description
  
This project compares three machine learning models (Logistic Regression, Random Forest, and XGBoost) for predicting diabetes and prediabetes using the 2015 BRFSS dataset. The dataset contains 70,692 respondents with 21 health indicators.

- Repository Structure
  
Biostat625 Final Report.Rmd - Main report document

Logistic_reg.rmd - Logistic regression analysis

Random_Forest_full.Rmd - Random forest analysis

XGBoost.Rmd - XGBoost analysis

Comparisons.Rmd - Model comparison code and figures

Comparisons_with_parallel.Rmd - Parallel processing version (XGBoost and Random Forest)

Final.Rmd - Analysis with 5-fold CV

pic/ - Folder for all figures and plots

625project_git.Rproj - RStudio project file

- How to Run
  
Clone this repository

Open 625project_git.Rproj in RStudio

Run Biostat625 Final Report.Rmd to generate the complete report

Individual model files can be run separately

- Team Members
  
Tiantian Lian

Meiqi Zhu

Shuchen Wu

Course: Biostat 625 - Fall 2025
Group: 7

- Key Results
  
XGBoost: AUC = 0.834 (best overall)

Logistic Regression: AUC = 0.827 (best interpretability)

Random Forest: AUC = 0.824

- Data Source
CDC BRFSS 2015 dataset (cleaned, balanced version)
