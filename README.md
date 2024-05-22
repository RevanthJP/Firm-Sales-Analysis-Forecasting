# Predictive_Model


PROBLEM 1:



EXECUTIVE SUMMARY

You are a part of an investment firm and your work is to do research about these 759 firms. You are provided with the dataset containing the sales and other attributes of these 759 firms. Predict the sales of these firms on the bases of the details given in the dataset so as to help your company in investing consciously. Also, provide them with 5 attributes that are most important.

INTRODUCTION

In this first problem, various steps have been taken in order to predict the sales of 759 firms. Data exploration have been carried out on different variables including capital, patents, R & D stocks, Employment, Stock market value of the firm, etc using data exploration techniques such as univariate analysis, bivariate analysis, graphical representations. Based the data exploration many usual insights have been obtained and also steps are taken to eliminate outliers and missing values. Thus, made sure a clean data is ready for the Linear Regression model. Based on the predicts and insights the Investment firm can plan their future investments across the firms accordingly.

DATA DESCRIPTION

The Description of the variables provided in the dataset given below.
1. sales: Sales (in millions of dollars). 
2. capital: Net stock of property, plant, and equipment.
3. patents: Granted patents. 
4. randd: R&D stock (in millions of dollars). 
5. employment: Employment (in 1000s). 
6. sp500: Membership of firms in the S&P 500 index. S&P is a stock market index that measures the stock performance of 500 large companies listed on stock exchanges in the United States 
7. tobinq: Tobin's q (also known as q ratio and Kaldor's v) is the ratio between a physical asset's market value and its replacement value. 
8. value: Stock market value. 
9. institutions: Proportion of stock owned by institutions. 


PROBLEM 2


EXECUTIVE SUMMARY

You are hired by the Government to do an analysis of car crashes. You are provided details of car crashes, among which some people survived and some didn't. You have to help the government in predicting whether a person will survive or not on the basis of the information given in the data set so as to provide insights that will help the government to make stronger laws for car manufacturers to ensure safety measures. Also, find out the important factors on the basis of which you made your predictions.

INTRODUCTION

In this problem survival rate of the persons coming across car crash has been predicted using Logistic Regression and Linear Discriminant Analysis method. Univariate analysis, Bivariate analysis, descriptive statistics are few of the data analysis and data exploratory techniques has been used. The dataset provided contains various features such as airbag availability, seatbelt usage, etc which were sufficient enough in training the models and making the models predict with higher accuracy. Both Logistic Regression model and Linear Discriminant analysis model has been put into predicting the survival rate and metrics such as confusion matrix, classification report, ROC curve and ROC_AUC score are used here to evaluate the predictions made by each model. Thus, it helped in choosing the best model for this problem scenario.



DATA DESCRIPTION

The following description of each feature in the dataset is provided below:
1. dvcat: factor with levels (estimated impact speeds) 1-9km/h, 10-24, 25-39, 40-54, 55+ 
2. weight: Observation weights, albeit of uncertain accuracy, designed to account for varying sampling probabilities. (The inverse probability weighting estimator can be used to demonstrate causality when the researcher cannot conduct a controlled experiment but has observed data to model).
3. Survived: factor with levels Survived or not survived. 
4. airbag: a factor with levels none or airbag.
5. seatbelt: a factor with levels none or belted. 
6. frontal: a numeric vector; 0 = non-frontal, 1=frontal impact. 
7. sex: a factor with levels f: Female or m: Male. 
8. ageOFocc: age of occupant in years. 
9. yearacc: year of accident.
10. yearVeh: Year of model of vehicle; a numeric vector. 
11. abcat: Did one or more (driver or passenger) airbag(s) deploy? This factor has levels deploy, not deploy and unavailable.
12. occRole: a factor with levels driver or pass: passenger.
13. deploy: a numeric vector: 0 if an airbag was unavailable or did not deploy; 1 if one or more bags deployed. 
14. injSeverity: a numeric vector; 0: none, 1: possible injury, 2: no incapacity, 3: incapacity, 4: killed; 5: unknown, 6: prior death.
15. caseid: character, created by pasting together the populations sampling unit, the case number, and the vehicle number. Within each year, use this to uniquely identify the vehicle.



