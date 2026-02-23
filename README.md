Project: Medical Data Visualizer

Introduction
This project aims to find the correlation between variables such as weight, blood pressure and cholesterol with cardiovascular disease. the goal is to use a heatmap to illustrate the correlations.

About the dataset
dataset: cardio_train.csv
key metric:  ap_hi, ap_lo, weight, cholesterol

Summary of the Finding
The heatmap reveals that ap_hi (systolic blood pressure) is the strongest individual predictor of cardiovascular disease with a correlation cofficent of (0.43) followed by ap_lo(diastolic blood pressure) which has a correlation cofficent (0.34). both are moderatelly correlated with cardiovascular disease, meaning their increase increases the liklihood of having cardiovascular disease.
incontrast, the other variables weight and cholesterol have low correlation with cardiovascular disease with correlation cofficents of (0.18) and (0.22). While Weight shows a slightly higher correlation with heart disease (0.18) than BMI (0.16) in this dataset, BMI was engineered as a feature to provide a standardized clinical metric that accounts for height-weight proportions.
