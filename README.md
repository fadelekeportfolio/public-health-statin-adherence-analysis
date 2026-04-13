# 🫀 Statin Medication Non Adherence: 
# An Early Intervention Intelligence Tool

Supporting healthcare teams to identify patients 
at risk of discontinuing cardiovascular medication 
before clinical intervention becomes urgent.

## Developer
Felicita Adeleke
Health Analytics Portfolio Project 2026

## The Clinical Problem
Statin medication is prescribed to prevent heart 
attacks and strokes. Yet a significant proportion 
of patients quietly discontinue treatment without 
any clinical team noticing until it is too late.

This project addresses a gap in routine healthcare 
intelligence. Using publicly available prescription 
data from 890,000 patients this analysis identifies 
which patient groups are most at risk of treatment 
discontinuation and translates those findings into 
an accessible risk stratification tool for 
healthcare professionals.

## Personal Motivation
Losing people close to me to cardiovascular disease 
made me ask a question that stayed with me. How many 
patients quietly stop taking their heart medication 
and does anyone in the healthcare system notice 
before it is too late? This project is my attempt 
to use data to close that gap.

## What This Tool Does
This interactive risk stratification tool allows 
healthcare professionals to input five patient 
characteristics and instantly receive a predicted 
risk score and risk band. No technical knowledge 
is required. The tool is designed to support 
clinical prioritisation and earlier intervention 
planning rather than replace professional 
clinical judgement.

## Key Intelligence Findings
- Patients aged 30 to 44 have the highest 
  non adherence rate at 43.0% representing 
  the highest priority group for targeted 
  adherence support
- Patients collecting their first prescription 
  have a 40.0% non adherence rate. The largest 
  single improvement occurs between the first 
  and second prescription representing the 
  most critical window for clinical outreach
- Non adherence falls consistently from 40% 
  at first prescription to just 6% by the 
  tenth prescription confirming that habit 
  formation is a key protective factor
- Older patients aged 90 and above showed 
  the strongest adherence at just 22.8% 
  non adherence rate
- Statin intensity showed negligible effect 
  on adherence behaviour suggesting side 
  effects are not the primary driver of 
  discontinuation

## Clinical Recommendations
1. Target younger patients aged 30 to 44 
   proactively as a standard component of 
   their care pathway
2. Introduce structured outreach at the 60 
   to 90 day mark after treatment initiation 
   to support patients through the highest 
   risk window
3. Use risk scores for prioritisation not 
   classification directing limited clinical 
   resources toward patients most likely 
   to benefit from support
4. Validate findings against UK NHS 
   prescription data before operational 
   deployment within an NHS trust

## Analytical Approach
Historical prescription claims data covering 
890,000 patients was analysed to understand 
medication behaviour patterns. A balanced 
logistic regression model was developed to 
generate patient level risk scores. Model 
outputs were translated into an interactive 
Streamlit application and structured reporting 
outputs suitable for Power BI dashboard 
development.

## Performance Summary
- Non adherent patient detection rate: 68%
- Discriminatory power: AUC 0.623
- Training population: 973,511 records
- Validation population: 417,220 records

## Tools and Technologies
- Python: Pandas, NumPy, Scikit-learn, 
  Seaborn, Matplotlib
- Risk stratification tool: Streamlit
- Performance reporting: Power BI
- Version control: GitHub

## Files in This Repository
- felicita_adeleke_statin_adherence_analysis.ipynb: 
  Full analytical notebook
- app.py: Interactive risk stratification tool
- balanced_logistic_model.pkl: Saved analytical model

## Data Source
Publicly available anonymised prescription claims 
data from the Czech Republic 2017 to 2020 used 
for research and portfolio demonstration purposes.

## Clinical Disclaimer
This tool is designed to support clinical 
prioritisation and should not replace 
professional clinical judgement. Validation 
against UK NHS prescription data is recommended 
before operational deployment.
