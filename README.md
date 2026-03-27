# Bias-Variance Tradeoff using Polynomial Regression

##  Overview
This project demonstrates the **bias-variance tradeoff** using polynomial regression on a customer segmentation dataset. The objective is to understand how model complexity affects prediction accuracy and generalisation.

---

## Dataset
- Dataset: Customer Segmentation Data  
- Feature (X): Income  
- Target (y): Wine Spending (MntWines)  

The dataset shows a non-linear relationship between income and spending, making it suitable for polynomial regression.

---

## Methods Used
- Polynomial Regression (Degree 1, 3, 10)  
- Train-Test Split  
- Mean Squared Error (MSE)  
- K-Fold Cross Validation  
- Data Visualisation using Matplotlib  

---

## Results

| Model Degree | Train Error | Test Error |
|-------------|------------|------------|
| Degree 1    | 78411.09   | 71295.27   |
| Degree 3    | 56949.34   | 60967.37   |
| Degree 10   | 110975.42  | 119764.02  |

Degree 3 provides the best balance between bias and variance.

---

## Visualisations
The following plots are included in the project:

- Underfitting (Degree 1)  
- Optimal Fit (Degree 3)  
- Overfitting (Degree 10)  
- Bias-Variance Error Curve  

---

## How to Run

1. Clone the repository:

git clone https://github.com/your-username/bias-variance-polynomial-regression


2. Navigate to the project folder:
- cd ML_bias-variance-polynomial-regression


3. Install required libraries:
- pip install -r requirements.txt


4. Run the Jupyter Notebook:
- ML_jupyter_notebook


---

## Report
The full report is available here:
report/ML_individual Report.pdf  


---

## Project Structure

bias-variance-polynomial-regression/
│
├── notebook/
│ └── bias_variance.ipynb
│
├── data/
│ └── customer_segmentation.csv
│
├── report/
│ └── bias_variance_report.pdf
│
├── images/
│ ├── degree1.png
│ ├── degree3.png
│ ├── degree10.png
│ └── error_curve.png
│
├── README.md
├── requirements.txt
└── LICENSE


---

## License
This project is licensed under the MIT License.

---

## Author
AjithKumar Madhu

---

## Conclusion
This project clearly demonstrates:
- Degree 1 → Underfitting  
- Degree 3 → Optimal model  
- Degree 10 → Overfitting  

The best model is the one that balances bias and variance effectively.
