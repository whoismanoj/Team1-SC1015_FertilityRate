# Welcome to Singapore - Fertility Rate Studies

wip - https://docs.google.com/presentation/d/1xkltPWhsaUnA32IbRDwqRVtUVM07CIhAM8T27MaHz0I/edit?usp=sharing

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on Singapore fertility rate (https://www.singstat.gov.sg/find-data/search-by-theme/population/births-and-fertility/visualising-data). For detailed walkthrough, please view the source code in order from:

**UPDATE THIS**
1. [Data Extraction](https://github.com/nicklimmm/movie-analysis/blob/main/data-extraction.ipynb)
2. [Data Visualization](https://github.com/nicklimmm/movie-analysis/blob/main/data-visualization.ipynb)
3. [Data Resampling and Splitting](https://github.com/nicklimmm/movie-analysis/blob/main/data-resampling-and-splitting.ipynb)
4. [Logistic Regression](https://github.com/nicklimmm/movie-analysis/blob/main/logistic-regression.ipynb)
5. [Neural Network](https://github.com/nicklimmm/movie-analysis/blob/main/neural-network.ipynb)
  
## Contributors

- Mai Xiwen - Data Extraction, Data Visualization, Multivariate Analysis
- Tan Xuan Yo -   Data Preparation and cleaning, Data Resampling, Data Extraction, Data Visualization
- Lux Pang Jian Wen - Data Visualization, Logistic Regression, Machine Learning and Analysis

## Problem Definition

- Analysis abnormality in fertility trend from 1980 - 2022
  - What might be the causes for the stagnated trend from 1985-2005
  - What might be the causes for the fertility spike at 1995
- Are we able to predict what will the fertility rate be from 2023 - 2030?
- Which model will best predict it?

## Models Used

**UPDATE THIS**
1. Logistic Regression
2. Neural Networks

## Conclusion

**UPDATE THIS**
- Popularity and budget have low linear correlation value with ratings (watch out for bandwagons 🤣)
- Popularity of the casts and crews have higher linear correlation value with ratings
- Resampling imbalanced data improved model performance especially on the minority class
- Logistic Regression did not perform well with non-linearly correlated variables
- Neural Networks along with SMOTEENN resampling method consistently did well in predicting good movies after 100 training attempts (around 72% accuracy, 70% recall)
- Yes, it is possible to predict if a movie is good with acceptable amount of accuracy and recall

## What did we learn from this project?

**UPDATE THIS**
- Handling imbalanced datasets using resampling methods and imblearn package
- Neural Networks, Keras and Tensorflow
- Logistic Regression from sklearn
- API Usage
- Other packages such as tqdm, json, requests
- Collaborating using GitHub
- Concepts about Precision, Recall, and F1 Score

## References

- [<https://www.singstat.gov.sg/find-data/search-by-theme/population/births-and-fertility/visualising-data>]
