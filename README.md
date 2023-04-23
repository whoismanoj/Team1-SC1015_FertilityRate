# Welcome to Singapore - Fertility Rate Studies

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on Singapore fertility rate (https://www.singstat.gov.sg/find-data/search-by-theme/population/births-and-fertility/visualising-data). For detailed walkthrough, please view the source code in order from:

**UPDATE THIS**
1. [Data Cleaning](https://github.com/xiwen4/SC1015_FertilityRate/blob/main/SC1015%20Part%201%20Data%20Cleaning.ipynb)
2. [Data Basic Visualization](https://github.com/xiwen4/SC1015_FertilityRate/blob/main/SC1015%20Part%202%20Basic%20Visualisation.ipynb)
3. [Exploratory data analysis](https://github.com/xiwen4/SC1015_FertilityRate/blob/main/SC1015%20Part%203%20Data%20Exploration.ipynb)
4. [Prediction and Modelling](https://github.com/xiwen4/SC1015_FertilityRate/blob/main/SC1015%20Part%204%20Prediction%20and%20Modelling.ipynb)
  
## Contributors

- Mai Xiwen - Data Extraction, Data Visualization, Multivariate Analysis
- Tan Xuan Yo -   Data Preparation and cleaning, Data Resampling, Data Extraction, Data Visualization
- Lux Pang Jian Wen - Data Visualization, Linear Regression, Machine Learning and Analysis

## Motivation
Low fertility rates can have various negative consequences for a country, including an aging population, decreased economic growth, and social challenges. As the workforce decreases and the number of retirees increases, healthcare and pension costs may rise, while there may be a shortage of skilled workers. In addition, a shrinking population can affect a country's political and social stability, and change social norms and cultural values. Governments should therefore address this issue and encourage higher fertility rates through policies and programs that support families and child-rearing.

## Problem Definition

The fertility rate in Singapore has been steadily declining over the past few decades, which can lead to an aging population and economic and social challenges. To address this issue, we aim to analyze the factors that contribute to low fertility rates and predict the fertility rate in the next 10 years.

Specifically, we would like to explore the relationship between education level, cost of living, and rate of marriage and how it affects our fertility rate?

Lastly, We would like to predict what is the fertilty rate for the next 10 years.

## Models Used
1. Linear Regression
2. Polynomial Regression

## Conclusion
- Fertility rate decline through the years as the cost of living and women's education level increase
- However for women above 30, there have been an increase in fertility rate since 1990s.
- The increase could be due to various factors, such as rise in education levels among women and a shift towards delaying childbirth until later in life.
- We explored various factors and found that education provides the closest prediction of the fertility rate.
- Using linear regression, we predicted that the fertility rate(FR) will continue to decline in the next 10 years. (from FR:0.99 in year 2024 to 0.79 in year 2033)

## What did we learn from this project?
- Polynomial regression: a curved line to model the relationship between variables of a certain degree. It's useful for non-linear relationships, but can overfit and extrapolate beyond the data.
- Data visualization: We have created data visualizations to communicate insights and findings to better understand the case study.
- Data cleaning: We identified data quality issues such as missing data, duplicated records, or incorrect values. We then did a data cleaning and resampling.

## References

- [<https://www.singstat.gov.sg/find-data/search-by-theme/population/births-and-fertility/visualising-data>]
