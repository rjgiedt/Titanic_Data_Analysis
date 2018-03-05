# Kaggle Titanic Data Analysis

## Project Summary
This is an analysis of the popular Titanic data set from Kaggle, created for the purposes of illustrating a data science project to persons not familiar with machine learning, for a lab/group lecture. In this data, we are given a variety of information on the passengers of the titanic, including names, ages, sexes, cabin information, ticket numbers and several other parameters. Our job then, is to predict which of these passengers survived and which passengers died. 

The approach in this analysis was to first conduct feature engineering in order to pull relevant data from the information which was provided. This included gaining information such as the passenger's title from their name, or parsing ticket information to see what value can be gained. The script is heavily documented for learners and explanations for each feature can be readily determined. Following feature engineering, I created a Random Forest and XGBoost models to predict survival or death on the entire feature set. The accuracy of these models was ~ 0.80, but with additional work, could likely be improved. 

