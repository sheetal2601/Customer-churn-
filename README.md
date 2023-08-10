# Customer-churn-
predicting whether a particular customer will switch to another telecom provider or not


steps :
Missing value imputation
Outlier treatment
Dummy variable creation for categorical variables
Test-train split of the data
Standardisation of the scales of continuous variables
After all of this was done, a logistic regression model was built in Python using the function GLM() under statsmodel library. This model contained all the variables, some of which had insignificant coefficients. Hence, some of these variables were removed first based on an automated approach, i.e. RFE and then a manual approach based on VIF and p-value.

 

Apart from this also calculated confusion matrix and accuracy and saw how accuracy was calculated for a logistic regression model.
