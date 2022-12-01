<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 15px; height: 80px">

# Project 3: Web APIs & NLP - TF-IDF


## Problem Statement

Current classifying model using straightforward keywords such as ‘bootcamp’ and ‘coding’ yields around 79% accuracy.

Build a model with >90% accuracy that helps to identify between those who are looking for bootcamp style learning vs computer science majors/prospective students based on the words they use online.

## Jupyter Notebook Purpose:
#### Notebook contains codes for:
- TF-IDF data preprocessing method.
- Gridsearch CV (model optimization) on selected Models such as Bernoulli NB, Multinomial NB, KNN, Logistic Regression

## Data Dictionary:

**Dataset name: data_2**

#### Size: 9982 observations, 2 variables
#### Description: Final dataset that contains scrapped data from Reddit.

|Feature|Type|Dataset|Description|
|:---|:---|:---|:---|
|**subreddit**|*integer*|data|Subreddit categories. 0 refers to csMajors, 1 refers to codingbootcamp| 
|**text**|*string*|data|Posts extracted from csMajor and codingbootcamp subreddit|


## Summary on Model Accuracy:

|**Vectorization Method**|**Model**|**Train Results**|**Test Results**|
|:---|:---|:---:|:---:|
|TF-IDF|Naive Bayes - Bernoulli|0.95698|0.92548|
|TF-IDF|Naive Bayes - Multinomial|0.95431|0.92748|
|TF-IDF|Logistic Regression|0.96193|0.94231|
|TF-IDF|K-Nearest Neighbours|0.86762|0.87260|