# Project Overview
This project involves predicting the sales of 759 firms based on various business attributes using Linear Regression. The objective is to identify key factors influencing firm performance and provide strategic insights for investment decisions.

# Objectives
- Perform Exploratory Data Analysis (EDA) to uncover patterns and relationships in the dataset.
- Identify key drivers of firm sales, such as employment, R&D stock, capital, and patents.
- Develop and evaluate a Linear Regression model to forecast firm sales with high accuracy.
- Provide actionable insights to prioritize investment in high-performing firms, particularly S&P 500 members.

# Dataset Description
The dataset contains 759 firms with the following attributes:
- sales: Firm sales in millions of dollars
- capital: Net stock of property, plant, and equipment
- patents: Number of granted patents
- randd: R&D stock in millions of dollars
- employment: Number of employees (in 1000s)
- sp500: S&P 500 membership indicator
- tobinq: Tobin’s Q ratio
- value: Stock market value
- institutions: Proportion of stock owned by institutions

# Project Workflow
## 1. Data Preprocessing

- Checked for missing values and treated them appropriately.
- Performed outlier detection and removal to ensure data quality.
- Conducted feature scaling to normalize data across different ranges.
## 2. Exploratory Data Analysis (EDA)

- Univariate and bivariate analysis conducted to identify trends.
- Correlation heatmaps and pair plots used to visualize relationships between variables.
## 3. Model Development

- Split data into 70% training and 30% testing sets.
- Developed a Linear Regression model to predict firm sales.
- Evaluated model performance using R² and RMSE metrics.

# Key Findings
- Strong positive correlation between sales and employment, R&D, and capital.
- Firms that are part of the S&P 500 consistently show higher sales compared to non-members.
- Achieved an R² of 100%, indicating a highly accurate model fit.
  
# Recommendations
- Prioritize investment in firms that are S&P 500 members due to their higher predicted sales and stable performance.
- Consider key factors like employment levels, R&D investment, and capital when evaluating firm potential for future investments.

# Technologies Used
- Python: Data processing and modeling
- Pandas, NumPy: Data manipulation
- Matplotlib, Seaborn: Data visualization
- Scikit-Learn: Model development and evaluation
