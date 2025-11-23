# Portuguese Bank Marketing – End-to-End Data Science Project
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/b790d60c-e5c2-43f2-b2ec-2de4cbf8700f" />


This repository contains an end-to-end data science solution built using the Portuguese Bank Direct Marketing Dataset. The project covers exploratory analysis, predictive modeling, and actionable business insights for improving term-deposit subscription campaigns. Dataset info sourced from project documentation.

---

## Project Objectives

### 1. Exploratory Data Analysis (EDA)
- Study customer demographics and campaign behavior  
- Detect trends in monthly performance and socio-economic patterns  
- Handle “unknown” values  
- Feature engineering (log transforms, call behavior metrics)  
- Identify features that drive term deposit subscription  

### 2. Predictive Modeling
Models used:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- LightGBM  

Key techniques:
- SMOTE for handling imbalance  
- Scaling and transformation  
- Evaluation using Recall, Precision, F1-score, AUC  

### 3. Business Insights
- Best-performing months for campaigns  
- Ideal customer targets  
- Call strategy improvements  
- Reducing unnecessary call attempts  
- Boosting conversion rates with data-driven targeting  

---

## Dataset Overview

- 41,188 customer records  
- 20 input variables + 1 target variable (y)  
- Contains demographic details, campaign history, and economic indicators  
- Target variable: whether the customer subscribed to a term deposit  

Dataset originally published in:  
Moro, Cortez & Rita (2014), Bank Marketing Campaign Dataset.

---

## Key Features of This Repository
- Fully documented notebook  
- EDA + preprocessing + model comparison  
- Clear business strategy recommendations  
- Visualizations for insights  
- Academic-submission ready  

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-Learn  
- XGBoost  
- LightGBM  
- Matplotlib, Seaborn  
- SMOTE (Imbalanced Learn)  
- Jupyter Notebook  

---

## Model Performance Summary
Includes comparison of:
- Accuracy  
- Recall  
- Precision  
- F1-score  
- AUC  
- Confusion matrix analysis  

The final model recommended for production is highlighted in the notebook.

---

## Challenges and Solutions
- Handling imbalanced classes  
- Managing “unknown” categorical labels  
- Avoiding leakage from the duration variable  
- Dealing with high VIF / multicollinearity  
- Improving recall for the minority class  

---

## How to Run This Project
1. Clone this repository  
2. Install Python dependencies  
3. Place dataset in the data/ folder  
4. Open and run final_notebook.ipynb  
5. Review reports in /reports  

---

## Author
Naveen Kumar Kathir  
Data Science Enthusiast

---

## ⭐ Show Support
If this project helps you, please give it a star!
