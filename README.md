# Predicting-Smoking-Drinking-Habits-with-Machine-Learning
## Overview

An R-based analytics pipeline that predicts individuals’ smoking and drinking behaviors using a suite of classification models (Logistic Regression, Decision Trees, Random Forest, MARS, and XGBoost) followed by statistical validation and clustering (K-means). This yields robust lifestyle risk insights.

---

## Repository Structure

- **`IDA_Project.R`**  
  The R script containing the complete workflow:
  1. **Data loading & cleaning**  
  2. **Exploratory Data Analysis**  
  3. **Feature Engineering**  
  4. **Model Training & Evaluation**  
     - Logistic Regression  
     - Decision Tree  
     - Random Forest  
     - MARS (Multivariate Adaptive Regression Splines)  
     - XGBoost  
  5. **Statistical Analysis** (ROC/AUC, cross-validation, Chi-square tests)  
  6. **Clustering with K-Means**  
  Results and plots are displayed inline and saved to the working directory.

- **`IDA_Final_Report_GROUP-16.pdf`**  
  The final project report detailing objectives, methodology, results, and conclusions.

- **`IDA_Project.R`**  
  The R script containing the complete workflow: data loading, preprocessing, exploratory analysis, feature engineering, XGBoost classification, K-means clustering, model evaluation (accuracy, AUC), and statistical tests.


- **`README.md`**  
  This file.

---

## Key Features

- **Multiple Classification Models**  
  - **Logistic Regression** for baseline discrimination.  
  - **Decision Tree** to capture non-linear splits.  
  - **Random Forest** for ensemble robustness.  
  - **MARS** to model complex interactions.  
  - **XGBoost** for high-accuracy gradient boosting.

- **Thorough Statistical Validation**  
  - ROC curves & AUC comparison  
  - Cross-validation accuracy estimates  
  - Chi-square and t-tests for feature significance

- **K-Means Clustering**  
  - Segments individuals into “Low-Risk,” “Moderate-Risk,” and “High-Risk” groups.

- **Insightful Visualizations**  
  - Confusion matrices, variable importance plots, cluster scatterplots

---

## Tech Stack

- **Language**  
  - R (≥ 4.0)

- **Data Wrangling & Visualization**  
  - `tidyverse` (dplyr, tidyr, readr)  
  - `ggplot2`

- **Modeling & Evaluation**  
  - `stats` (glm for Logistic Regression, kmeans)  
  - `rpart` (Decision Tree)  
  - `randomForest` (Random Forest)  
  - `earth` (MARS)  
  - `xgboost` (gradient boosting)  
  - `caret` (training workflows, cross-validation)  
  - `pROC` (ROC, AUC)  
  - `broom` (tidy statistical outputs)

---

## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/smoking-drinking-ml.git
   cd smoking-drinking-ml
