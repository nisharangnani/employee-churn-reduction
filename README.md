# Employee Churn Reduction
A model that uses association rule mining to determine interesting factors that lead to employee attrition and factors that lead to employees staying at their current firm.

## Dataset
The dataset contains information of about 1200 employees. Each employee has 35 attributes including age, education, distance from home, job role, job involvement, job satisfaction, performance rating, etc. 

## Approach
- Exploratory data analysis
- Data preprocessing (deduplication, handling missing values, data conversion to factors)
- Generating rules using Apriori algorithm by varying support, confidence and ordering them in decreasing order of lift

## Top rules from association mining
- ```{Income = Low, Overtime = Yes} --> Attrition```
- ```{Position = Senior, Overtime = No, Travel = No} --> No attrition```
