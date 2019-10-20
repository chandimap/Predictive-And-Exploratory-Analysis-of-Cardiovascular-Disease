# Predictive-And-Exploratory-Analysis-of-Cardiovascular-Disease

This Cardiovascular Disease Dataset contains 12 columns. 
Age represents the number of days a person has been alive.
For gender, 1 means the person is a female, 2 means male.
Height and weight are self-explanatory. 
ap_hi represents the systolic blood pressure which is when the heart is contracting.
ap_lo is the diastolic blood pressure when the heart muscle relaxes. 
Cholesterol column ranges from 1-3, where 1 is normal levels, 2 is above normal, and 3 is well above normal. 
Glucose follows the same scale as well. 
Smoking and alcohol indicate whether a person drinks or not. 

 The target class "cardio" equals 1, when a patient has cardiovascular disease, and it's 0 if a patient is healthy.


"id" column has dropped in the analysis since it does not provide any additional information.

08 Classifiers used to predict if a patient has this disease or not. In the final analysis, XGBoost was selected as the best classifier by comparing the performance of classifiers.


