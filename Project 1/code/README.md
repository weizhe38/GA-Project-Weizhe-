{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "c8d09e47",
   "metadata": {},
   "source": [
    "<img src=\"http://imgur.com/1ZcRyrc.png\" style=\"float: left; margin: 20px; height: 55px\">\n",
    "\n",
    "# Project 1: Standardized Test Analysis"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "6bc7d841",
   "metadata": {},
   "source": [
    "## Problem Statement:"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "9050a613",
   "metadata": {},
   "source": [
    "The new format for the SAT was released in March 2016. As an employee of the College Board - the organization that administers the SAT - you are a part of a team that tracks statewide participation, to understand the reasons for low participation rates in certain states, and to make recommendations about how the College Board might work to increase the participation rates.\n",
    "\n",
    "The College Board, an organization that administers the SAT, looks at statewide SAT test participation rates.\n",
    "\n",
    "Identify states with low SAT participation rates from 2017 to 2019 and provide recommendations to the College Board on how to improve them."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c19090e3",
   "metadata": {},
   "source": [
    "## Data Dictionary:"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "00632f52",
   "metadata": {},
   "source": [
    "**Dataset name: df_final**\n",
    "\n",
    "|Feature|Type|Dataset|Description|\n",
    "|---|---|---|---|\n",
    "|**state**|*integer*|df_final|US state name.| \n",
    "|**act_score_year**|*float*|df_final|Composite ACT score: the average of a candidate's four section scores (English, Math, Reading, Science) from 2017 to 2019. Each sections are graded separately from 1 to 36. |\n",
    "|**act_part_year**|*float*|df_final|The participation rate for ACT tests per year, from 2017 to 2019.| \n",
    "|**sat_score_year**|*integer*|df_final|Total SAT score of two sections for candidate (Evidence-Based Reading and Writing, Math) from 2017 to 2019. Each section is graded separately from 200 to 800. Total SAT score ranges from 400 to 1600|\n",
    "|**sat_part_year**|*float*|df_final|The participation rate for SAT tests per year, from 2017 to 2019.| "
   ]
  },
  {
   "cell_type": "markdown",
   "id": "62beefbe",
   "metadata": {},
   "source": [
    "## Key Takeaway:"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "f0f417dc",
   "metadata": {},
   "source": [
    "- SAT and ACT participation rates are inversely correlated, as generally students will choose either to do SAT or ACT. However there are cases where students choose to do both SAT and ACT tests, to improve their chances of applying to a college of their choice.\n",
    "\n",
    "\n",
    "- Inverse correlation between SAT score and participation rates. States with lower participation rates tend to have better SAT scores. Higher participation rates means a greater proportion of average college bound students taking the SAT test, which lowers the average SAT scores. States with high average SAT scores and low participation rates, could indicate that an average student from the state is less confident or willing to take the SAT test."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "a94f2414",
   "metadata": {},
   "source": [
    "## Recommendations:"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "155f5c4d",
   "metadata": {},
   "source": [
    "- States to target: North Dakota/Wyoming/South Dakota.\n",
    "\n",
    "- Increase outreach programs to schools in states with low SAT participation, targeting states with low SAT related resources such as test centres.\n",
    "\n",
    "- Educate on SAT test requirements, and inform on how widely SAT results are accepted in US colleges.\n",
    "\n",
    "- Provide additional teaching resources and materials to improve confidence of students in states with high SAT scores, but low participation rates"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.12"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
