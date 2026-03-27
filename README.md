Bias-Variance Tradeoff using Polynomial Regression

Overview
This project demonstrates the bias-variance tradeoff using polynomial regression on a customer dataset. The goal is to analyse how model complexity affects prediction performance.

Dataset
Customer segmentation dataset

Feature: Income

Target: Wine Spending (MntWines)

Methods Used
Polynomial Regression (Degree 1, 3, 10)

Train-Test Split
Mean Squared Error (MSE)
K-Fold Cross Validation

Results
Model Degree	Train Error	Test Error
Degree 1	78411.09	71295.27
Degree 3	56949.34	60967.37
Degree 10	110975.42	119764.02

Degree 3 provides the best balance between bias and variance.

Visualizations
Underfitting (Degree 1)
Optimal Fit (Degree 3)
Overfitting (Degree 10)
Error Curve

How to Run
Clone repository:
git clone https://github.com/your-username/bias-variance-polynomial-regression
Install dependencies:
pip install -r requirements.txt
Run notebook:
jupyter notebook

Report
The full explanation is available in:
report/bias_variance_report.pdf

License

This project is licensed under the MIT License.

Author
AjithKumar Madhu
