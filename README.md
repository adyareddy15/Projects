# Job Satisfaction Analysis
**Project Overview**
This project explores the key factors influencing job satisfaction, focusing on work-life balance, work environment, and employee well-being. Using machine learning models and data visualization, we analyze how different demographic and workplace variables impact job satisfaction and provide actionable insights to enhance employee retention.

**Key Objectives**
- Assess the relationship between job satisfaction and factors like work-life balance, stress levels, environment satisfaction, and health status.
- Analyze demographic and department-level effects on job satisfaction.
- Develop predictive models to forecast job satisfaction levels.
- Provide data-driven recommendations to improve employee retention and workplace productivity.

**Dataset**
- Source: Kaggle Employee Survey Dataset
- Contains 5,000+ employee records
- Features include demographics, work environment ratings, health metrics, and job performance data

**Technologies Used**
- Programming: Python (Pandas, NumPy, Scikit-learn)
- Data Visualization: Matplotlib, Seaborn
- Machine Learning: Random Forest, XGBoost, SVM, Logistic Regression
- Statistical Techniques: Correlation analysis, Feature scaling, Age binning

**Key Insights From Exploratory Data Analysis**
- Work-life balance has a 0.7 positive correlation with job satisfaction.
- Stress levels have a -0.6 negative correlation with job satisfaction.
- Employees with less than 10 years and 25+ years of experience show higher satisfaction, while mid-career employees (10-25 years) experience a dip.
- Full time employees in IT & Finance departments report the highest job satisfaction.
- Commute distance negatively affects satisfaction, highlighting the importance of remote work options.

**Machine Learning Models and Performance**
| Model                  | Accuracy | Key Observations |
|------------------------|---------|------------------|
| **Random Forest**      | 49%     | Best performance for majority class, misclassification for minority classes |
| **XGBoost**           | 52%     | Slight improvement, but class imbalance remains an issue |
| **Logistic Regression** | 55%     | High recall for Class 3 but poor performance on minority classes |
| **Support Vector Machine (SVM)** | 57% | Improved recall for Class 3 after feature selection |  

**Key Findings**
- Work-Life Balance and Work Environment are the strongest predictors of job satisfaction across all models.
- Personal well-being factors, such as Sleep Hours and Physical Activity, significantly impact satisfaction and stress levels.
- Class imbalance in the dataset hindered the models' ability to accurately predict lower satisfaction levels, affecting performance on minority classes.

**Recommendations for orgainzations**
- Implement flexible work arrangements to reduce commute-related dissatisfaction.
- Focus on work-life balance initiatives to improve employee retention.
- Provide structured career growth opportunities to address mid-career satisfaction dips.
- Use data-driven insights to enhance employee well-being programs.
