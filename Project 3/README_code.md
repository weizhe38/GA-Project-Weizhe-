<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 15px; height: 80px">

# Project 3: Web APIs & NLP

## Background

With the increase in competition in the space for coding bootcamps, example Hack Reactor (online), Vertical Institute, Rocket Academy, Le Wagon, it affects General Assembly's market share and lowers marketing ROI, which in turn leads to General Assembly being unable to hit enrollment KPIs.

GA marketing is therefore trying to figure out how to better identify the online persona of a bootcamp seeker as opposed to that of a computer science major to aid in targeted advertising. Considering the two topics have quite a bit in common, efforts to further segregate the two targets could yield better advertising ROI.

## Problem Statement

Current classifying model using straightforward keywords such as ‘bootcamp’ and ‘coding’ yields around 79% accuracy.

Build a model with >90% accuracy that helps to identify between those who are looking for bootcamp style learning vs computer science majors/prospective students based on the words they use online.

## Data Dictionary:

**Dataset name: data_2**

#### Size: 9982 observations, 2 variables
#### Description: Final dataset that contains scrapped data from Reddit.

|Feature|Type|Dataset|Description|
|:---|:---|:---|:---|
|**subreddit**|*integer*|data|Subreddit categories. 0 refers to csMajors, 1 refers to codingbootcamp| 
|**text**|*string*|data|Posts extracted from csMajor and codingbootcamp subreddit|


## Conclusion:

- Our model was ablee to achieve an accuracy of ~94% (>90%), beating the baseline model of ~79%, in terms of identifying potential candidates who are interested in coding boot camps.
- In order to maintain and further gain market shares with the rising competition from other boot camp course providers, it is key that GA needs to  act fast through the use of the model, to identify potential candidates.

## Recommendations:

- GA marketing team to focus marketing efforts on showcasing how GA courses can equip a GA student with strong coding technical skills, as keywords with high correlation coefficient from the model, includes "Python", "javascript", "programming", "program", which suggests that people who are interested in joining boot camps, usually look out for courses that equip them with specific coding skillsets. 
- GA marketing team to help to identify more social media platforms (other than reddit) where the model can be deployed to identify potential students who want to join boot camps.

## Moving Forward:

- Data scraping to cover more online platforms that GA may be present in to refine our model. 
- Expand our model's outreach based on other GA courses, to potential students for UX/UI design as well.
- Better labelling and grouping to help the model better understand web lingo. For example, SWE appears often, but this is also a duplicate with software engineer, so potentially these terms could be grouped together for our model.
- Carry out sentiment analysis on comments to determine whether the user is positive or negative regarding the post. As the comments may also have some correlation to the possible conversion of the user.