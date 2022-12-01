<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 15px; height: 80px">

# Project 3: Web APIs & NLP - Ngram


## Problem Statement

Current classifying model using straightforward keywords such as ‘bootcamp’ and ‘coding’ yields around 79% accuracy.

Build a model with >90% accuracy that helps to identify between those who are looking for bootcamp style learning vs computer science majors/prospective students based on the words they use online.

## Jupyter Notebook Purpose:
#### Notebook contains codes for:
- N-gram data preprocessing method.
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
|Bi-Gram|Naive Bayes - Bernoulli|0.90435|0.86057|
|Bi-Gram|Naive Bayes - Multinomial|0.98464|0.90545|
|Bi-Gram|Logistic Regression|0.94416|0.875|
|Bi-Gram|K-Nearest Neighbours|0.78987|0.61218|
|Tri-Gram|Naive Bayes - Bernoulli|0.96874|0.76883|
|Tri-Gram|Naive Bayes - Multinomial|0.96954|0.77484|
|Tri-Gram|Logistic Regression|0.88204|0.71834|