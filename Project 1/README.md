<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 20px; height: 55px">

# Project 1: Standardized Test Analysis

## Problem Statement:
The new format for the SAT was released in March 2016. As an employee of the College Board - the organization that administers the SAT - you are a part of a team that tracks statewide participation, to understand the reasons for low participation rates in certain states, and to make recommendations about how the College Board might work to increase the participation rates.

The College Board, an organization that administers the SAT, looks at statewide SAT test participation rates.

Identify states with low SAT participation rates from 2017 to 2019 and provide recommendations to the College Board on how to improve them.

## Data Dictionary:

**Dataset name: df_final**

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*integer*|df_final|US state name.| 
|**act_score_year**|*float*|df_final|Composite ACT score: the average of a candidate's four section scores (English, Math, Reading, Science) from 2017 to 2019. Each sections are graded separately from 1 to 36. |
|**act_part_year**|*float*|df_final|The participation rate for ACT tests per year, from 2017 to 2019.| 
|**sat_score_year**|*integer*|df_final|Total SAT score of two sections for candidate (Evidence-Based Reading and Writing, Math) from 2017 to 2019. Each section is graded separately from 200 to 800. Total SAT score ranges from 400 to 1600|
|**sat_part_year**|*float*|df_final|The participation rate for SAT tests per year, from 2017 to 2019.| 

## Key Takeaway:

- SAT and ACT participation rates are inversely correlated, as generally students will choose either to do SAT or ACT. However there are cases where students choose to do both SAT and ACT tests, to improve their chances of applying to a college of their choice.
- Inverse correlation between SAT score and participation rates. States with lower participation rates tend to have better SAT scores. Higher participation rates means a greater proportion of average college bound students taking the SAT test, which lowers the average SAT scores. States with high average SAT scores and low participation rates, could indicate that an average student from the state is less confident or willing to take the SAT test.

## Recommendations:
- States to target: North Dakota/Wyoming/South Dakota.
- Increase outreach programs to schools in states with low SAT participation, targeting states with low SAT related resources such as test centres.
- Educate on SAT test requirements, and inform on how widely SAT results are accepted in US colleges.
- Provide additional teaching resources and materials to improve confidence of students in states with high SAT scores, but low participation rates