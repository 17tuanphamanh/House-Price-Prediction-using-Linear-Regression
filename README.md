
# House Price Prediction – Advanced Regression Project

This repository contains a full end-to-end machine learning project using **Linear Regression** and advanced models to predict house prices, based on the [Kaggle House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) dataset.

## Project Overview

This project demonstrates a typical regression workflow applied to a real-world dataset. It focuses on:

- Thorough data preprocessing
- Feature selection
- Model training and evaluation
- Hyperparameter tuning
- Model comparison and improvement
- Test set prediction for submission

It is designed as a practical showcase of data science and machine learning skills, suitable for third-year students or junior data analysts seeking internship opportunities or building a portfolio.

## Objectives

- Predict house sale prices based on 80+ features.
- Explore and clean missing values properly.
- Build baseline and advanced regression models.
- Compare model performance using validation metrics.
- Submit predictions on Kaggle to evaluate leaderboard ranking.

## Workflow Summary

1. **Load and explore the dataset**  
2. **Feature selection**  
3. **Preprocessing pipeline**  
4. **Model training**  
5. **Evaluation**  
6. **Prediction and submission**

## Results Summary

| Model             | CV RMSE (approx) | Notes                               |
|------------------|------------------|-------------------------------------|
| Linear Regression | ~36,000          | Baseline model                      |
| Ridge             | Lower RMSE       | Better generalization               |
| Lasso             | Good trade-off   | Performs feature selection          |
| Random Forest     | Further improved | Captures non-linear relationships   |
| XGBoost           | Best score       | Tuned for performance, leaderboard-ready |

## Key Skills Demonstrated

- Feature engineering and selection
- Data imputation and preprocessing
- Sklearn pipelines and modular ML design
- Model tuning using `GridSearchCV`
- Tree-based methods and boosting with XGBoost
- Cross-validation and metric interpretation
- Real-world test prediction and submission

## Repository Structure

```
house-price-prediction/
├── train.csv
├── test.csv
├── House_Price_Prediction_Notebook.ipynb
├── linreg_model.pkl
├── submission.csv
└── README.md
```

## Notes

- The project is written in Jupyter Notebook format using Python 3 and scikit-learn.
- XGBoost is used for its high predictive performance.
- The notebook includes visualizations, prediction examples, and pipeline-based design for clarity and reusability.
