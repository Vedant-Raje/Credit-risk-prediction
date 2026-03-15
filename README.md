# Credit Risk Prediction using Machine Learning

## Project Overview
This project focuses on predicting whether a borrower will **default on a loan** using machine learning techniques. Financial institutions rely on credit risk models to evaluate whether a borrower is likely to repay a loan.

The goal of this project is to analyze borrower financial attributes and build predictive models that classify loan applicants into **default** and **non-default** categories.

---

## Dataset
The dataset used in this project contains financial and demographic attributes of borrowers.

### Features
- **age** – Age of the borrower  
- **employ** – Years of employment  
- **address** – Years at current address  
- **income** – Annual income  
- **debtinc** – Debt-to-income ratio  
- **creddebt** – Credit card debt  
- **othdebt** – Other debts  

### Target Variable
- **default** – Indicates whether the borrower defaulted on the loan.

The dataset contains approximately **700 borrower records**.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Model Performance Comparison

| Model | Accuracy |
|------|---------|
| Random Forest | 76.43% |
| Logistic Regression | 85.71% |
| Support Vector Machine (SVM) | **88.71%** |

--- 

## Key Insights

 - Borrowers with higher debt-to-income ratios show higher probability of default.
 - Income and employment stability influence loan repayment behavior.
 - Machine learning models can effectively classify high-risk borrowers using financial indicators.

---

## Conclusion

 - This project demonstrates how machine learning techniques can be applied to predict credit risk and assist financial institutions in making data-driven lending decisions.
 - Predictive models help lenders identify high-risk borrowers before issuing loans, reducing financial losses.
