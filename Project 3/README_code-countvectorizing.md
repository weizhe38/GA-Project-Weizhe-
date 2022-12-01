<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 15px; height: 80px">

# Project 3: Web APIs & NLP - Count Vectorizing


## Problem Statement

Current classifying model using straightforward keywords such as ‘bootcamp’ and ‘coding’ yields around 79% accuracy.

Build a model with >90% accuracy that helps to identify between those who are looking for bootcamp style learning vs computer science majors/prospective students based on the words they use online.

## Jupyter Notebook Purpose:
#### Notebook contains codes for:
- Count Vectorizing data preprocessing method.
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
|Count Vectorizer|Naive Bayes - Bernoulli|0.84611|0.84215|
|Count Vectorizer|Naive Bayes - Multinomial|0.93214|0.93149|
|Count Vectorizer|Logistic Regression|0.98678|0.93429|
|Count Vectorizer|K-Nearest Neighbours|0.90489|0.83694|