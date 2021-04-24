# Biostats-750-Final-Project

STUDY OBJECTIVE: to find which predictor variables should be included in the model to predict whether a person will have a heart attack or not

Data visualization --> do this first before diving into performing all methods before!

Useful definitions to know for the data set we're using:

Angina - a type of chest pain caused by reduced blood flow to the heart

Methods to use for data analysis:

Logistic regression on the target variable (as the response, is binary)
Possibly doing LDA and QDA for classification into having heart attack (1) or not (0) classes
Using ridge regression or lasso methods to see if coefficients can be shrunken towards zero

Bootstrap for estimation of accuracy of a parameter estimate (do we have to come up with what the parameter estimate would be?)
Cross validation to estimate skill of logistic regression model on unseen data --> can do validation set approach, LOOCV, and k-fold CV and compare the test errors from the three

Can do best subset selection, forward stepwise selection, and backward stepwise selection --> compare best models picked by each method
-Variable selection methods --> then plug the result of that into logistic regression, LDA, QDA, etc. 

General thoughts:

-13 predictor variables --> we suspect that not all of them will be significant in predicting whether a heart attack will occur or not

