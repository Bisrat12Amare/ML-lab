# Machine Learning Lab 5
## Classification and Regression

### 1. Project Overview
This project implements two Machine Learning experiments using customer support ticket datasets.

The main objective is to develop, evaluate, and compare different Machine Learning models for classification and regression tasks.

### 2. Experiments

#### Experiment A: Classification
**Objective:** Predict whether a customer support ticket will be escalated.

- Target variable: `escalated`
- Models:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree Classifier
- Evaluation metrics:
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

#### Experiment B: Regression
**Objective:** Predict the time required to resolve a customer support ticket.

- Target variable: `resolution_time_hours`
- Models:
  - Linear Regression
  - Ridge Regression
  - Decision Tree Regressor
- Evaluation metrics:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

### 3. Datasets

The project uses two datasets:

- `classification_escalation.csv`
- `resolution_time_regression.csv`

Both datasets contain customer support ticket information.

### 4. Data Preprocessing

The following preprocessing techniques were implemented:

- Median imputation for missing numerical values.
- Most-frequent imputation for missing categorical values.
- StandardScaler for numerical feature scaling.
- OneHotEncoder for categorical feature encoding.
- ColumnTransformer for applying different transformations to different feature types.
- Pipeline for combining preprocessing and model training.

The `ticket_id` column was excluded from model features.

### 5. Model Training and Evaluation

- Training and testing split: 80% training and 20% testing.
- Classification validation: 5-fold StratifiedKFold.
- Regression validation: 5-fold KFold.
- GridSearchCV for hyperparameter tuning.
- Separate test datasets for final evaluation.

### 6. Outlier Detection

The Interquartile Range (IQR) method was used to identify potential outliers in the regression target variable.

### 7. Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

### 8. How to Run the Project

1. Clone the repository.
2. Open the project in Visual Studio Code.
3. Install the required libraries:

```bash
pip install numpy pandas scikit-learn jupyter
```

4. Open the Lab 5 Jupyter Notebook.
5. Ensure the datasets are located in the `data/` directory.
6. Run all notebook cells sequentially.

### 9. Expected Outcomes

The project demonstrates:

- Building classification and regression models.
- Data preprocessing and feature transformation.
- Cross-validation and model comparison.
- Hyperparameter optimization.
- Model evaluation using appropriate performance metrics.
- Outlier detection and analysis.

### 10. Conclusion

This lab demonstrates a complete Machine Learning workflow involving data preparation, model development, cross-validation, hyperparameter tuning, and performance evaluation for both classification and regression problems.
