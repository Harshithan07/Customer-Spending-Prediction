# Customer Spending Prediction – Regression Modeling Using Purchase Behavior

## ABOUT THE PROJECT:
This project aimed to build predictive models that estimate individual customer spending levels using behavioral features. The dataset captured demographic and transactional attributes related to purchasing history. The project involved training and evaluating multiple regression algorithms to identify key drivers of customer value and recommend data-driven marketing strategies.

## USE CASE EXPLANATION:
Accurately predicting customer spending is critical for businesses in retail and e-commerce to drive personalized marketing, customer segmentation, and lifetime value forecasting. This project addresses the problem of revenue prediction based on profile and behavior features, enabling organizations to target high-value customers more effectively.

## HOW IT IS BUILT AND FULL WORKING:

1. Data Preparation:

- Cleaned missing values and scaled numerical features.

- Handled outliers and normalized skewed distributions.

- Engineered categorical features (e.g., education, marital status).

2. Modeling Workflow:

- Split data into training and test sets (75/25).

- Trained and compared six models:

   1. Linear Regression

   2. k-Nearest Neighbors (k-NN)

   3. Regression Tree

   4. Support Vector Regression (SVR)

   5. Neural Network (MLP Regressor)

   6. Ensemble Model (Voting Averaging)

3. Model Tuning:

- Tuned hyperparameters using GridSearchCV and cross-validation.

- Compared models using Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).

4. Restricted vs Full Feature Comparison:

- Built separate models using a subset of features (purchase history only).

- Evaluated performance differences to assess the predictive value of auxiliary attributes.


## OUTPUT AND RESULTS OR BENCHMARKS:

- Best model: Neural Network (MLP Regressor) with RMSE ≈ 0.504

- Linear Regression offered transparency but showed underfitting.

- SVR was sensitive to feature scaling and kernel choice.

- Restricted models (purchase-only features) performed worse, proving the importance of customer profile and derived features.

- Feature importance analysis highlighted product category spending as primary predictors.


## SKILLS, TOOLS:
Python, scikit-learn, Pandas, NumPy, GridSearchCV, MLPRegressor, DecisionTreeRegressor, KNeighborsRegressor, SVR, regression metrics (RMSE, MAE), matplotlib, seaborn

## KEYWORDS:
Customer analytics, regression modeling, spending prediction, retail forecasting, scikit-learn, ensemble regression, neural networks, behavioral data, model comparison, marketing data science

