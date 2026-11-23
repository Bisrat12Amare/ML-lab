# Machine Learning Lab 4
## Binary Classification and Cost-Sensitive Decision Making

**Student:** Bisrat Amare  
**Course:** Machine Learning  
**Project:** Service Ticket Escalation Prediction

### Project Description

This project develops and evaluates binary classification
models to predict whether a service ticket will be escalated.

### Dataset

File: `classification_escalation.csv`

The dataset contains:
- complexity_score
- team_experience_years
- priority
- channel
- customer_tenure_months
- escalated (target variable)

### Models Implemented

1. Majority Class Baseline
2. Logistic Regression
3. Linear Discriminant Analysis
4. K-Nearest Neighbors (KNN)

### Techniques Used

- Missing-value imputation
- Feature scaling
- One-hot encoding
- Stratified train-test splitting
- Classification evaluation metrics
- Confusion matrix
- ROC curve
- Threshold optimization
- Cost-sensitive classification
- Stratified 5-fold cross-validation
- GridSearchCV

### Project Files

- `lab4_classification.ipynb`: Complete implementation,
  analysis, visualizations, and conclusions.
- `classification_escalation.csv`: Dataset.
- `README.md`: Project documentation.

### Execution

Open `lab4_classification.ipynb` in Jupyter Notebook
or VS Code and execute all cells.

### Conclusion

The project demonstrates why classification decisions
should consider the cost of false positives and false
negatives in addition to conventional performance metrics.