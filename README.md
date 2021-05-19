# NBA_Analysis

## Overview
We set out with the goal of making the intricate and dynamic data of the National Basketball Association more approachable and understandable by using analytics and machine learning. Then use machine learning to predict future championship teams. 

## Project Description

### Data Pulling
After finding a reliable data source (basketball-reference.com) the 20 years of team data was pulled, cleaned, and consolidated into a workable dataframe that can be analyzed and run through our machine learning program.

### Champion Analysis
After the data had been pulled and cleaned, the group looked to see relationships in the data over the last 20 years to see if a human could determine what makes a champion a champion. After running the data through tableau, Joel, Steve and Abraham created multiple graphs and pushed them to a public workbook

https://public.tableau.com/profile/joel.watkins#!/vizhome/NBA_Champion_Analysis/Story1

### Machine Learning
After we produced the visualizations, we wanted to run the data through a machine learning program that would find the important stats and predict the nba champion for the 2020 season. Using scikit-learn and a neural network we were able to accurately predict the Los Angeles Lakers as the 2020 NBA Champion.

### Website Production
After our machine learning programs were run, we consolidated the results and pushed it to a heroku webpage that outlines our project more in depth. 

https://nba-analysis-ml.herokuapp.com/

