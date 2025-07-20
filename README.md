# Customer Churn Prediction Project

This project focuses on predicting customer churn using machine learning on a synthetic customer dataset. The goal is to identify customers at risk of leaving and to simulate targeted campaigns to reduce churn.

---

## Project Overview

- **Data Generation:**  
  Initially, a dataset with 500 customers was created, including features such as age, gender, signup date, last order date, total orders, average order value, total spending, and churn status.  
  To improve model reliability, the dataset size was increased to 1,500 customers, resulting in better representation and improved model performance.

- **Modeling:**  
  Decision Tree and Random Forest classifiers were trained to predict customer churn. Models were evaluated using accuracy, confusion matrix, and classification reports.  
  Dataset balancing techniques were applied to address class imbalance and improve prediction fairness.

- **Campaign Simulation:**  
  Based on churn risk scores from the models, high-risk customers were identified and simulated targeted campaigns were proposed to reduce churn.  
  The effect of campaigns on churn rate was simulated to estimate potential business impact.

---

## How to Use

1. Run the data generation script to create synthetic customer data. You can adjust the `n_customers` parameter to change dataset size (e.g., 500 or 1500).  
2. Train and evaluate churn prediction models on the generated data.  
3. Use the campaign recommendation module to identify high-risk customers and simulate the impact of retention campaigns.

---

## Libraries

- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  
- imbalanced-learn  

---

## Files

- `churn_prediction.py` — main script including data generation, modeling, evaluation, and campaign simulation.

---

## Contact

For questions, reach out to:  
**Müge Çakır**  
[LinkedIn Profile]

---

*Note: This project uses synthetic data for educational and demonstration purposes.*