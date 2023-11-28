# capstone
This repo will house all working files and notes on my captstone project

## An Analysis of crime in NYC

To identify root causes and predict crime in New York (5 boroughs)

Questions to answer

Can you predict a categorical type and severity of crime based on day of week, weather and location? (Log Regression, KNN, Decision Trees)
- Why is this useful: Can help provide information to residents about safety

What underlying demographic features (excluding race/ethnicity) are most heavily correlated crime (type and frequency)? (Log regression)
- Why is this useful: Can help provide local public organizations areas to improve (e.g. education, shelter, healthcare, jobs) 

Relationships of type/severity of crime with age groups and why? (Linear regression)
- Why is this useful: “Customer” segmentation to develop a targeted approach for action

##

Sprint 1: 
- For this submission, defined the question, introduced datasets and discussed initial observations

Sprint 2: 
- For this submission, I used variables in the arrests data alone to see if we can predict the type of crime based on burrough, age group, sex and day of week. 
- Given this is a limited list of variables so did not expect a good result
- Next step would be to use the demographic data (now that we were able connect lat lon and community district) to see if the model can be more robust.

Spring 3:
- For this submission, merged the arrests dataset with demographic and age datasets by community district
- Ran logistic regression for each type of crime to get variables that were most impacting
- Ran classification models (logistic / decision tree) using independent variables and got an 10+ percent improvement in accuracy scores
- For next steps:
-   Plot out decision tree
-   Identify additional attributes that would move the needle on model accuracy and add precision and recall
-   Run grid search to identify best model type and hyperparameters
- For demo day create a tool to be able to predict type of crime by a number of selections and an interactive tableau map
