# Spaceship Titanic: Data Science Final Project

## Project Overview
This project applies advanced machine learning techniques to the **Spaceship Titanic** dataset, a fictional classification challenge where the goal is to predict whether passengers were transported to another dimension.

The project is part of a final submission for a graduate-level **Machine Learning for Data Science** course.

---

## Files Included

| File Name                    | Description                                        |
|-----------------------------|----------------------------------------------------|
| `DataScienceFinalProject.ipynb` | Final notebook with full EDA, modeling, SHAP, and results |
| `train.csv`                 | Training data with features and labels             |
| `test.csv`                  | Unlabeled test data                                |
| `spaceship_titanic_final_submission.csv` | Final predictions for submission                |
| `spaceship_submission.csv` | Alternative submission format                      |
| `README.md`                 | This file                                          |

---

## Techniques Used

- Data preprocessing and imputation
- Feature engineering (e.g., TotalSpend, Cabin parsing, group-aware features)
- Dimensionality reduction with PCA
- Model comparison: Logistic Regression, Random Forest, XGBoost, Voting Ensemble
- Hyperparameter tuning via GridSearchCV
- Model explainability using SHAP
- Performance metrics: Accuracy, F1-score, Confusion Matrix

---

## Results

- Best Model: XGBoost / Voting Ensemble
- Final Accuracy: 87%
- Top Features: CryoSleep, TotalSpend, Spa, VRDeck

---

## Visual Outputs

- SHAP beeswarm plots
- Model accuracy comparison bar chart
- Confusion matrix heatmaps

---

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
