# Assignment_1

Loan Approval Prediction Using Ensemble Methods

**Overview**

This repository contains a comprehensive analysis and predictive modelling project based on a synthetic dataset inspired by real-world credit risk data. The project applies machine learning techniques, including ensemble methods, to predict loan approval statuses and evaluate financial risk factors. The models accurately classify loan applications as approved or rejected based on multiple financial and personal features.

**Dataset Description**

The dataset used for this project is a synthetic version derived from the Credit Risk dataset on Kaggle and enriched with additional variables from Financial Risk for Loan Approval data. It contains 45,000 records and 14 variables, combining categorical and numerical features.

**Key Notes:**

   1. Synthetic Data: SMOTENC was applied to simulate new data points and enrich the dataset.
   2. Target Variable: loan_status (1 = Approved, 0 = Rejected).
   3. Instances with potential outliers (e.g., age > 100 years) were carefully addressed during preprocessing.
   
**Machine Learning Models**

The notebook includes the implementation and evaluation of various ensemble learning models:
   1. Bagging:
      Random Forest, Bagging Classifier with Decision Trees.
   2. Boosting:
      Gradient Boosting, XGBoost.
   3. Stacking:
      Combining multiple base models.
   4. Voting: 
      Hard and Soft Voting Classifiers.

**Metrics and Evaluation**

   1. Accuracy, precision, recall, F1 score, and cross-validation results are used to evaluate model performance. 
   2. Visualizations include box plots for cross-validation accuracy and confusion matrices.
      
**Explainability:**  SHAP, LIME

**Setup Instructions**

   1. **Clone the repository:** git clone https://github.com/your-username/credit-risk-loan-approval.git
   2. **Install dependencies:** pip install -r requirements.txt
   3. **Run the Jupyter Notebook:** Jupiter notebook

**Requirements**
   1. **Python:** 3.8+
   2. **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost, shape, lime
   3. **Install all dependencies using:** pip install -r requirements.txt

   
**Results**

   1. Best Model: Identified using cross-validation accuracy and F1 score.

   2. Ensemble techniques, particularly stacking and boosting, provided robust performance.
         
   3. Explainability techniques offered valuable insights into model decisions.



