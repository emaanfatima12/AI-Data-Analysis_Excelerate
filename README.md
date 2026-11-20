# Learner Success Prediction

Analysis and prediction of learner success on an online opportunity platform, done during my AI Powered Data Analysis internship (June 2026).

## About the project

The dataset has about 8,500 learner records from 71 countries, covering courses, events, competitions and internships. I explored the data, analysed cohorts, and built models to predict which learners would succeed. I defined "success" as reaching Team Allocated, Started or Rewards Award status.

## What's inside

- `week1_eda/` - exploratory analysis
- `week2_cohort_analysis/` - enrollment, acceptance and dropout analysis
- `week3_modelling/` - model building and validation
- `week4_final_report/` - final findings and recommendations

## Results

I compared Logistic Regression, Random Forest and Gradient Boosting. Gradient Boosting performed best, with an AUC of 0.95 (0.957 in 5-fold cross-validation).

I also compared the predictions with actual results for each program. Some were far off (for example, Business Consulting: 57.7% predicted vs 16.1% actual), so I recommended manual review for those programs instead of relying on the model alone.

## Tools

Python, pandas, NumPy, scikit-learn, Matplotlib

## How to run

```bash
pip install -r requirements.txt
jupyter notebook
```

The dataset is not included because it may contain personal information.
