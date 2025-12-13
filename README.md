# Biostat 625 Final Project: Diabetes Risk Prediction
# Project Description
  
This project compares three machine learning models (Logistic Regression, Random Forest, and XGBoost) for predicting diabetes and prediabetes using the 2015 BRFSS dataset. The dataset contains 70,692 respondents with 21 health indicators.

# Repository Structure
  
### Biostat625 Final Report.Rmd
- Main report document.
  
### Biostat625-Final-Report.pdf
- The pdf version of main report document.

### Comparisons.Rmd
- Final Version of model comparison across Logistic Regression, Random Forest, and XGBoost using the full predictor set.
Generates comparison figures and summary metrics.

### Comparisons_with_parallel.Rmd 
- Final Parallelized version of the model comparison (parallel computing is primarily applied  for Random Forest and XGBoost).

### Logistic_reg.rmd
- Logistic regression analysis, including model selection, diagnostics, and key outputs used in the final report.

### Random_Forest_full.Rmd
- Random forest analysis.

### XGBoost.Rmd
- XGBoost analysis.

### pic/ 
- Folder containing all exported figures and plots used in the report.

### Draft.Rmd 
- Draft / working version of Comparisons.Rmd and can be ignored.

### 625project_git.Rproj 
- RStudio project file.

# How to Run
  
Clone this repository

Open 625project_git.Rproj in RStudio

Run Biostat625 Final Report.Rmd to generate the complete report

Individual model files can be run separately

# Team Members
  
Tiantian Lian

Meiqi Zhu

Shuchen Wu

Course: Biostat 625 - Fall 2025
Group: 7

# Key Results
  
XGBoost: AUC = 0.834 (best overall)

Logistic Regression: AUC = 0.827 (best interpretability)

Random Forest: AUC = 0.824

# Data Source
CDC BRFSS 2015 dataset (cleaned, balanced version)
