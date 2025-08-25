# Telco Customer Churn Analysis

## 📌 Project Overview
Customer churn is a major concern for telecom companies, as retaining existing customers is often more cost-effective than acquiring new ones.  
This project focuses on analyzing **customer churn data** using machine learning and visualization techniques to identify the key factors that drive churn and to build predictive models.

The objectives are:
- Understand customer behavior through exploratory data analysis (EDA).
- Identify important factors contributing to churn.
- Build predictive models to forecast customer churn.
- Provide insights that can help businesses reduce churn rates.

## ⚙️ Tech Stack
- **Programming Language:** Python 3  
- **Libraries Used:**  
  - Pandas, NumPy – Data preprocessing & manipulation  
  - Matplotlib, Seaborn – Data visualization  
  - Scikit-learn – Machine learning modeling  
  - Jupyter Notebook – Development environment  

## 📂 Project Structure
├── Telco_Customer_Churn_Analysis.ipynb # Main analysis notebook
├── data # Dataset folder
├── results/ # Outputs: charts, checkpoints
├── README.md # Project documentation

## 📊 Key Insights
 - Customers with month-to-month contracts are more likely to churn than those with yearly contracts.
 - High monthly charges significantly increase the risk of churn.
 - Customers paying via electronic checks exhibit higher churn rates.
 - Tenure length has an inverse relationship with churn — the longer the tenure, the lower the churn probability.
 - Machine learning models like Logistic Regression and Random Forest provided strong predictive performance.

## 📈 Results & Visuals
 - The analysis includes:
 - Correlation heatmaps of customer attributes.
 - Churn distribution across demographics and service types.
 - Predictive model evaluation with metrics: Accuracy, Precision, Recall, F1-score.
