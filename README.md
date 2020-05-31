# Predicting-Credit-Card-Approval
Everyday, commercial banks receive a lot of new credit card approvals. Not a few of them rejected. Many factors cause this, It might be like high loan balances, low income levels, or too many inquiries on an individual's credit report, etc. Manually analyzing these applications is mundane, error-prone, and time-consuming . Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. I will try to build an automatic credit card approval predictor using machine learning techniques.


The dataset this project have used is from UCI Machine Learning Repository


#### Module Dependencies
- numpy
- sklearn
- pandas


##### The structure

- FIrst, I import the file and inspect the dataset,
- The data is not perfect, theres a few missing values, I need imputing the missing values,
- The data need some preprocessing, first we need to convert the categorical into numerical values,
- Split the data to  train and test data, then rescaling it,
- The data is ready, fit them logreg and measure it,
- To find the best model, I used GridSearchCV to fing the best parameters and score
- Lastly, compute it and I got the best predict model for Credit Card Approvals
