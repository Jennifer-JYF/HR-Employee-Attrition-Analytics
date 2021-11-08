# HR-Employee-Attrition-Analytics
# Introduction

This project is a self-learning data science project where i applied machine learning techniques to study the key drivers of employee attrition. Dataset used for employee attrition analysis and modeling in this project is from IBM Watson Analytics Sample Data - HR Employee Attrition & Performance which contains employee data with various information such as personal background, position and employment information etc. with 1,470 data points.

Attrition rate and its contributing factors is one of the most commonly studied topics in Human Resource Management. Although some staff turnover is inevitable in any company, a high attrition rate usually comes with significant financial and time cost to employers. Recruitment, hiring and training of new employees all involve financial costs and a new employee may not be immediately productive in terms of creating profit. The amount of time spent to interview and find a replacement, and the loss of productivity for several months while the new employee gets accustomed to the new role, are indirect costs to the company. These costs can significantly increase if executive-level or highest-paid employees are to be replaced. As such, the costs of replacing employees for most companies are often very significant.An unusually high employee attrition rate is also considered indicative of problems within the company. Uncompetitive pay scales, micromanagement, ineffective human resource management (HRM) practices and unreasonable expectations can all lead to unacceptable levels of staff turnover. Understanding why and when employees are most likely to leave can lead to actions to improve employee retention as well as possibly planning new hiring in advance.

One of the key challenges in employee attrition analysis has been the lack of systematic quantitative analysis techniques for accurate insights and predictions. Now with machine learning as a powerful tool, the relationship between employee attrition and different contributing factors such as work-life-balance, employee's joblevel, monthly income, age etc. can be quantitively measured, providing concrete evidence for analysis of staff turnover and design of employee rentention plans.
# Results
***Heatmap plot showing correlations between different features/input variables:***
![results1](https://user-images.githubusercontent.com/93885043/140683867-81006116-7407-4980-99ba-979d237a0924.JPG)



***Feature Importances plot(employee attrition contributing factors) with XGBoost Machine Learning Model***
![results](https://user-images.githubusercontent.com/93885043/140683767-5731e992-2703-4706-9faf-b6c1e381b5f7.JPG)
***Confusion matrix of XGBoost model (88.04% accuracy)***

![results 3](https://user-images.githubusercontent.com/93885043/140684012-5fc26c9c-79e6-4219-bfba-cb265be18016.JPG)

# Discussion
Comparing the 3 machine learning models(Logistic Regression, Random Forest and XGboost), both Logistic Regression and XGBoost have high accuracy score and AUC score. After fine tunning the hyper-parameters, noticable performace improvement was seen in XGBoost model with accuracy score increased to 88.04% from 87.12% and a 1.8% incease in ROC AUC from 0.7992 to 0.8141. Benefiting from its regularized model formation techqniques, XGBoost has better control over over-fitting and thus returns better modeling and prediction performance compared to other machine learning models.

# Indicators and Retention Plan
The stronger indicators of employee leaving the company include:

Over Time: Employees who work overtime are more likely to leave the company compared those who don't. Hence efforts must be taken to appropriately scope projects upfront with adequate support and manpower so as to appropriately distribute workload and reduce the use of overtime.

Joblevel: Employeed on higher job levels are less likely to leave compared to leave. Employees on lower job levels should be identified as having higher-risk of leaving, measures such as employee retention programs can be implemented to reduce the attrition rate of lower joblevel employees.

Monthly Income: Employees on higher wages are less likely to leave the company. Hence, efforts should be made to gather information on industry benchmarks in the current local market to determine if the company is providing competitive wages, especially for positions/ specialities with lower income.

Age: Employees in relatively young age bracket 25–35 are more likely to leave. Hence, efforts should be made to clearly articulate the long-term vision of the company and young employees fit in that vision, as well as provide incentives in the form of clear paths to promotion for instance.

TotalWorkingYears: The more experienced employees are less likely to leave. Employees who have between 5–8 years of experience should be identified as potentially having a higher-risk of leaving.
