# Quality Prediction in Mining

##  Project Overview

This project focuses on predicting the quality of mined materials—specifically, the percentage of Silica Concentrate using historical mining data and machine learning algorithms. Developed during a 6-week industrial internship in collaboration with UniConverge Technologies Pvt Ltd (UCT), Upskill Campus (USC), and The IoT Academy, the aim was to assist mining engineers in taking early corrective actions and improve environmental sustainability by reducing impurities in ore concentrate.

---

##  Problem Statement

In mining operations, accurately predicting the level of impurities such as silica in ore concentrate is critical for efficiency, cost reduction, and sustainability. The impurity is measured hourly, and early predictions allow engineers to take timely actions.

### Objectives:

- Predict % Silica Concentrate every minute.
- Forecast how many hours ahead we can accurately predict % Silica Concentrate.
- Predict % Silica Concentrate without using the % Iron Concentrate column (despite their correlation).

---

##  Methodology

### Data Preprocessing
- Cleaned dataset using Excel and Pandas.
- Dropped irrelevant features based on EDA using scatter plots and correlation heatmaps.
- Handled outliers and data type conversions.

### Feature Engineering
- Removed highly correlated or unimportant features.
- Selected top predictive features using domain knowledge and visualizations.

###  Machine Learning Models
Trained and compared the following models:
- Linear Regression
- Decision Tree Regressor
- Lasso Regression
- Ridge Regression
- XGBoost Regressor (final best model)

###  Model Evaluation Metrics
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score
- Root Mean Squared Error (RMSE)

---

##  Tools & Technologies Used

| Category        | Tools Used                              |
|----------------|------------------------------------------|
| Language        | Python                                  |
| Libraries       | Pandas, NumPy, Scikit-learn, XGBoost     |
| Visualization   | Matplotlib, Seaborn                      |
| IDE             | Jupyter Notebook                         |

---

## Test Cases

| Test Case | Description                                                                                   | Outcome |
|----------|-----------------------------------------------------------------------------------------------|---------|
| 1       | Predict % Silica Concentrate every minute                                                     |  Achieved |
| 2       | Forecast % Silica Concentrate several hours ahead                                             | Partially (limited by data granularity) |
| 3       | Predict % Silica Concentrate without using % Iron Concentrate column                          | Achieved with slightly reduced accuracy |

---

##  Results

- Achieved real-time minute-level predictions for % Silica Concentrate.
- Demonstrated the feasibility of omitting % Iron Concentrate as a feature.
- Best model: XGBoost Regressor with optimized hyperparameters via Random Search.

---

##  Learning Outcomes

- Hands-on experience with predictive modeling, feature engineering, and deployment practices.
- Deep understanding of ML pipelines and mining process data.
- Exposure to real-world industrial constraints and regulatory considerations.



