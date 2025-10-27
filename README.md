# Frito Lay Case Study

## Executive Summary
This project analyzes employee attrition at Frito-Lay to identify the key factors driving turnover and to build a predictive model for early intervention. Using HR data, I explored demographic, behavioral, and compensation variables to determine which attributes most strongly correlate with employee departures.

## Key Drivers of Attrition
**Overtime:** Employees working frequent overtime were almost twice as likely to leave, indicating workload stress and burnout.
**Job Satisfaction:** Low satisfaction was strongly linked to higher turnover, suggesting a need for improved recognition and development programs.
**Monthly Income:** Lower-paid employees showed significantly higher attrition, highlighting the role of compensation equity.

## Model Performance
Two models were tested — K-Nearest Neighbors (KNN) and Naïve Bayes.
- Naïve Bayes achieved the best results, with 74.7% accuracy, 70.7% balanced accuracy, and a Kappa of 0.32, providing reliable classification and balance between detecting leavers and stayers.
- KNN trailed in accuracy and consistency, though it showed slightly higher sensitivity.

## Key Insights
- While it’s useful to examine variables that aren’t strong correlators, effective modeling requires stronger predictors. I initially explored a broader set of variables — including Job Role, Education Field, and Years with Current Manager — before narrowing down to those with the highest correlation to attrition.
- The strongest predictors of attrition were overtime, job satisfaction, and income level.
- Employees facing burnout, low engagement, or limited financial growth are the highest-risk group.
- Predictive modeling enables data-driven HR decisions, allowing Frito-Lay to proactively address retention risks and reduce turnover costs.

## Sources
Below are sources I used as references for this case study
 - https://topepo.github.io/caret/model-training-and-tuning.html
 - https://www.geeksforgeeks.org/knn-in-r-programming/
 - https://rpubs.com/riazkhan94/naive-bayes-r
 - https://www.r-bloggers.com/2021/12/how-to-split-data-into-train-and-test-in-r/
 - https://www.geeksforgeeks.org/undersampling-in-r/
 - https://stackoverflow.com/questions/74235618/undersampling-by-groups-in-r-to-address-class-and-features-imbalance-issues-in-h
 - https://youtu.be/bWD9Bmrru44?si=5sIyBaRh-7wYa81p
 - All readings
