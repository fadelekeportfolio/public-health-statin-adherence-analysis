# 🫀 Statin Non Adherence Risk Tool
A real world health analytics project identifying 
statin patients most likely to discontinue medication 
before clinical teams notice.

## Developer
Felicita Adeleke
Health Analytics Portfolio Project 2026

## Personal Motivation
Losing people close to me to cardiovascular disease 
made me ask a question that stayed with me. How many 
patients quietly stop taking their heart medication 
and does anyone in the healthcare system notice 
before it is too late? This project is my attempt 
to use data to answer that question.

## Project Overview
Using anonymised prescription claims data from 
890,000 patients across the Czech Republic between 
2017 and 2020 this project analyses medication 
adherence patterns and builds a predictive risk 
stratification tool.

## Key Findings
- Patients aged 30 to 44 have the highest non 
  adherence rate at 43.0%
- First prescription patients are most at risk 
  with a 40.0% non adherence rate
- Non adherence falls consistently from 40% at 
  first prescription to just 6% by the tenth
- Age group 90 and above showed the strongest 
  adherence at just 22.8% non adherence rate
- Statin intensity showed negligible effect on 
  adherence behaviour

## Tools and Technologies
- Python: Pandas, NumPy, Scikit-learn, 
  Seaborn, Matplotlib
- Machine Learning: Logistic Regression 
  with class balancing
- Deployment: Streamlit interactive app
- Reporting: Power BI dashboard

## Model Performance
- Balanced Model Recall: 68% of non adherent 
  patients correctly identified
- ROC AUC Score: 0.623
- Training data: 973,511 records
- Test data: 417,220 records

## Files in This Repository
- felicita_adeleke_statin_adherence_analysis.ipynb: 
  Full analysis notebook
- app.py: Streamlit risk stratification app
- balanced_logistic_model.pkl: Saved model file

## Dataset
Publicly available anonymised Czech prescription 
claims data 2017 to 2020 used for research and 
portfolio demonstration purposes only.

## Clinical Disclaimer
This tool is designed to support clinical 
prioritisation and should not replace professional 
clinical judgement.
