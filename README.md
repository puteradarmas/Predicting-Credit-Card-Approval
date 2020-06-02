# Predicting-Credit-Card-Approval

## Background
Everyday, commercial banks receive a lot of new credit card approvals. Not a few of them rejected. Many factors cause this, It might be like high loan balances, low income levels, or too many inquiries on an individual's credit report, etc. Manually analyzing these applications is mundane, error-prone, and time-consuming . Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. I will try to build an automatic credit card approval predictor using machine learning techniques.


The dataset this project have used is from UCI Machine Learning Repository

### Why Logistic Regression
We know lot of predictive analysis, one of them is Logistic Regression that I use on this project, but why?
As we can see the dependent varible here is binary and Logistic Regeression is the appropiate predictive analysis when it comes like this. It describe data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent variables.

On this project, Logistic Regression is the best choice for telling if the customer get the Credit Card Approval from the Bank.

### Learning Opportunities
First I need to know how to import and then manipulating the data that include inspecting the value and check the dtypes. There's several missing data, so imputation technique is required. The data need some preprocessing before it Can be use for data fitting. After that, data fitting technique is required and measuring method to know how well our model is.

#### Module Dependencies
- numpy
- sklearn
- pandas
