# ONGB Research Files
Public Schools around Oakland have had trouble with students and their attendance rates. Through the Oakland Natives Give Back institute, I helped track and predict students who were at the risk of becoming absent based on their past data, so that schools can attack these students and give them help before it's too late.

## Features
These files take an in-depth analysis into the the excel files given, analysis on the types of features that are most likely to cause absenteeism and a prediction model using Random-Forest and XGBoost to help solve these issues.

# Visualizations
Heatmap of Features given:
![download](https://github.com/user-attachments/assets/72e6d789-5674-47a8-a04a-136eb5f782f0)
As seen here, previous history of being absent has the highest correlation with absenteeism today, followed by GPA.

Fluency by School
![download](https://github.com/user-attachments/assets/5e137fc5-ef16-47de-819a-fd752fc4a9c7)
This shows how different schools' attendance rates based on their fluency in the English language, which shows that students who are already comfortable with English (in orange) score lower attendance on average

# Model: XGBoost
XGBoost, which stands for Extreme Gradient Boosting, is a scalable, distributed gradient-boosted decision tree (GBDT) machine learning library.

The model showed around an 80% classification correct rate when it came to absenteeism, showing rate of importance mostly being the attendance rate of the previous year and an ROC Curve of around 0.85.
![download](https://github.com/user-attachments/assets/a9a4e284-2f8e-4089-a87b-4d037529d744)
![download](https://github.com/user-attachments/assets/cf1939f3-5a86-4659-bf10-6045deb9a0db)
![download](https://github.com/user-attachments/assets/bc6809de-c686-4708-8a9b-2ba28fa2f4c8)