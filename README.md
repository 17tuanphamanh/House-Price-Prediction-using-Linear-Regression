House Price Prediction using Linear Regression
This project tackles the classic House Prices - Advanced Regression Techniques problem on Kaggle using various machine learning models, starting with Linear Regression and advancing to Ridge, Lasso, Random Forest, and XGBoost.

Dataset
Source: Kaggle Competition

Files:

train.csv: 1460 rows, 81 features (both numeric and categorical)

test.csv: for final prediction submission

Project Objectives
Predict house prices based on provided attributes

Apply robust preprocessing (missing value imputation, encoding, scaling)

Evaluate model performance using RMSE, R², and cross-validation

Experiment with model improvement techniques to target a Top 10–20% Kaggle public score

Workflow Summary
Load Data: Use pandas to explore and clean.

EDA: Summary stats, correlation check, missing value treatment.

Feature Selection: Top correlated numerical + key categorical.

Preprocessing Pipelines: Numeric scaling, categorical one-hot encoding.

Model Training: Linear Regression as baseline.

Evaluation: Validation split + cross-validation.

Advanced Models: Ridge, Lasso, RandomForest, XGBoost with GridSearchCV.

Submission: Generate predictions on test set.

Key Results
Model	CV RMSE (approx)	Notes
Linear Regression	~36,000	Baseline
Ridge	Improved	Handles multicollinearity
Lasso	Improved	Feature selection via regularization
Random Forest	↑ Performance	Captures non-linearity
XGBoost	↑↑ Top performer	Tuned for best Kaggle submission

Skills Demonstrated
Data preprocessing (imputation, encoding, scaling)

Feature selection & correlation analysis

Pipeline architecture with sklearn

Model evaluation & hyperparameter tuning

Use of joblib, matplotlib, xgboost

Ready-to-submit .csv generator for Kaggle

File Structure

house-price-prediction/
├── train.csv
├── test.csv
├── House_Price_Prediction_Notebook.ipynb
├── linreg_model.pkl
├── submission.csv
└── README.md
Next Steps
Log-transform target variable for better residual distribution

Add polynomial features / interactions

Try ensembling top models (e.g. Ridge + XGBoost)

