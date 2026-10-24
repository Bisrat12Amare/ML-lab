lab 1 :Data Exploration & Foundational Math

This project covers data cleaning, summary statistics, data visualization, correlation, vector dot products, 
and feature scaling using Python, Pandas, NumPy, and Matplotlib inside a Jupyter Notebook.



📁 What's Inside
The Jupyter Notebook includes all the lab tasks completed step by step:
- **Part A:** Inspecting and cleaning data (fixing missing values, outliers like 50 hours, and impossible values like -10 attendance).
- **Part B:** Summarizing data (calculating mean, median, and standard deviation, plus written observations).
- **Part C:** Visualizing data (creating a final score histogram and a study hours vs. score scatter plot).
- **Part D:** Finding the Pearson correlation and answering critical thinking questions about lurking variables.
- **Part E:** Doing vector operations and dot product predictions using NumPy (`y = w · x + b`).
- **Part F:** Standardizing features and explaining why distance-based algorithms like KNN require scaling.

How to Run the Code
1. Clone this repository or download the `.ipynb` file.
2. Open it in **Jupyter Notebook** or upload it to **Google Colab**.
3. Run the cells sequentially to see the data cleaning, outputs, and generated plots.

 
ML Lab 2: Support Ticket Resolution Prediction

 Project objective
This project compares regression models for predicting software support ticket resolution time in hours using a synthetic dataset.

 Dataset
The dataset contains ticket complexity, code lines changed, team experience, reopening status, and resolution time.

 Models
- Dummy Regressor
- Linear Regression
- Polynomial Regression (degrees 2 and 3)
- Ridge Regression
- Lasso Regression

 Evaluation
Models are evaluated using MAE, MSE, RMSE, and R². Cross-validation is used to compare polynomial degrees and select regularization parameters.

Files
- `ML_Lab_3.ipynb`: notebook containing data inspection, training, evaluation, plots, and conclusions.
- `lab_ticket_resolution.csv`: dataset used in the experiment.

## Important limitation
The dataset is synthetic. Feature availability and potential data leakage must be considered before using the model for real predictions.


Author
Bisrat Amare 
