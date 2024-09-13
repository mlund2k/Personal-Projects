# Baseball: Performance vs. Attendance

## Objective

**Goal:** Clean and analyze data to determine suitable teams for an advertisement firm, determine which if any key performance indicators lead to an increase in attendance for advertising purposes.

**Business Prompt:** 
1. Its 2015 and the stakeholder wants to invest in advertisements in a baseball stadium, and would potentially like to strike a brand deal with a high performing player on the team, ideally someone of mvp or all star status. Determine the most suitable team based on these metrics.
2. During the analysis, the stakeholder in question is curious as to what, if any, game statistics may impact the turnout of audience for a particular season. Additionally, a visual of audience trends may assist in the stakeholders foresight when making a decision.


## Process

Firstly, the raw data found on [Kaggle](https://www.kaggle.com/datasets/seanlahman/the-history-of-baseball) was a bit messy with missing values, mislabelled columns, and extreneous data.
I started by cleaning the files in Excel with filtering, altering data types, deleting extra columns, and implementing necessary formulas.
The cleaned files to be used can be found here:
- [Appearance Table](https://github.com/mlund2k/Project-1-Baseball-Performance-vs.-Attendance/blob/main/appearances_cleaned_2010-2014.csv)
- [Home Games Table](https://github.com/mlund2k/Project-1-Baseball-Performance-vs.-Attendance/blob/main/home_game_cleaned_2010-2014.csv)
- [Player Award Table](https://github.com/mlund2k/Project-1-Baseball-Performance-vs.-Attendance/blob/main/player_award_cleaned_2010-2014.csv)
- [Players Table](https://github.com/mlund2k/Project-1-Baseball-Performance-vs.-Attendance/blob/main/player_cleaned_2010-2014.csv)
- [Teams Table](https://github.com/mlund2k/Project-1-Baseball-Performance-vs.-Attendance/blob/main/team_cleaned_2010-2014.csv)

For the next step, I chose to join various tables in SQL and create ranked lists for each metric within BigQuery.

A full outlined step by step documentation with SQL queries and explanation can be found through pastebin or github:
- [Github](https://github.com/mlund2k/Project-1-Baseball-Performance-vs.-Attendance/blob/main/proj_notes.txt)
- [Pastebin](https://pastebin.com/7rwxUaxx)

Part 2 of the analysis makes use of R markdown for a more interactive documentation. This can be found in the following links:
- [R Markdown (Kaggle)](https://www.kaggle.com/code/mattlund2k/first-project-baseball-analysis) (Preferred)
- [Github](https://github.com/mlund2k/Project-1-Baseball-Performance-vs.-Attendance/blob/main/proj.pdf) (pdf format)
- [Github](https://github.com/mlund2k/Project-1-Baseball-Performance-vs.-Attendance/blob/main/proj.html) (raw html format)

## End Product

Part 1 Uses Tableau to visualize the data, find the visual online here:
- Inveract with [Tableau Dashboard](https://public.tableau.com/views/BaseballAnalysisfirstproject/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- Or view a [pdf](https://github.com/mlund2k/Project-1-Baseball-Performance-vs.-Attendance/blob/main/Dashboard%201.pdf)

Part 2 Uses ggplot2 in the R tidyverse package to manually construct a visual with code. Find the associated visual as part of the R Markdown:
- [R Markdown (Kaggle)](https://www.kaggle.com/code/mattlund2k/first-project-baseball-analysis)
