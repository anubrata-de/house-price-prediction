<!-- portfolio
title: House Price Prediction
tagline: Regression
category: Machine learning
summary: Predicts house prices from mixed categorical and numerical data for a Kaggle competition, comparing linear, tree and boosted models on R².
tags: Python, scikit-learn, XGBoost, LightGBM, Regression
slug: house-price-prediction
-->

# House Price Prediction

*Regression*

A regression model that predicts house prices from structured tabular data, built for the Machine Learning Practice Kaggle assignment at IIT Madras (Term 3, 2025).

## Approach

- Cleaned the data and handled a mix of categorical and numerical features, with memory-optimised preprocessing.
- Compared Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, XGBoost and LightGBM.
- Chose the best validation model and checked it with 5-fold cross-validation before generating predictions in the submission format.

## Results

- **XGBoost** scored best on the validation split, with **R² 0.94**.
- 5-fold cross-validation gave a more conservative **R² 0.62 ± 0.06**, so the single validation split flattered the model. Cross-validation is the more reliable estimate.

## Files

- [`house_price_prediction.ipynb`](house_price_prediction.ipynb): the full Kaggle notebook, with code and outputs.

---

Part of the BS in Data Science and Applications at IIT Madras. More projects: [anubrata.vercel.app](https://anubrata.vercel.app/projects).
