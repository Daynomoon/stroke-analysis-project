# Stroke Prediction Statistical Analysis

## Project Status
Completed

## Project Intro / Objective
This project is part of the **AAI-500-02 course** in the Applied Artificial Intelligence program at the University of San Diego.  

Our goal is to perform an **end-to-end statistical analysis** on the Kaggle Stroke Prediction Dataset.  
We focus on hypothesis testing (e.g., age effect, hypertension effect, BMI differences) and compare traditional statistical methods with a machine learning model for validation.  

## Contributors
- Dina Othman  
- Thiago Alvares
  
## Methods Used
- Data Cleaning & Preparation
- Exploratory Data Analysis
- Data visualizations
- Machine learning
- Hypothesis Testing

## Technologies
- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

## Project Description
We analyze the **Stroke Prediction Dataset** (Kaggle, by Fedesoriano).  

- **Size:** ~5,000 rows × 12 features  
- **Variables include:** age, gender, hypertension, heart disease, BMI, glucose level, smoking status, marital status, residence type, etc.  
- **Target:** stroke (0 = No, 1 = Yes)  

**Hypothesis to Explore:**
1. Null Hypothesis (H0): Age has no significant relationship with the likelihood of having a stroke.

Alternative Hypothesis (H1): Age has a significant relationship with the likelihood of having a stroke.  
 

**Analysis Plan:**
- Clean and prepare data (handle missing BMI values, encode categorical features).  
- Conduct statistical hypothesis testing (t-tests, 95% Confidence Interval (CI) Estimation, logistic regression).  
- Compare logistic regression performance with a machine learning model (Random Forest for example).  
- Report results with confidence intervals, p-values, and AUC scores.  


