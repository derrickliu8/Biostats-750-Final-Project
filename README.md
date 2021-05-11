# Biostats-750-Final-Project

1) STUDY OBJECTIVE: to find which predictor variables should be included in the model to predict whether a person is more likely or less likely to have a heart attack

Link for helpful info on the dataset: https://www.hindawi.com/journals/cmmm/2017/8272091/tab1/

2) Useful definitions to know for the data set we're using:

Angina - a type of chest pain caused by reduced blood flow to the heart

***Output (response variable we're considering): 0.5 is chosen as a threshold value in terms of probability. It's not about whether or not someone will get a heart attack but more about how likely a person is to get a heart attack. 

3) Methods to use for data analysis:

Logistic regression on the output variable (as the response, is binary)
Possibly doing LDA and QDA for classification into "more likely (1) or less likely (0) to have a heart attack" classes
Using ridge regression or lasso methods to see if coefficients can be shrunken towards zero

Cross validation to estimate skill of logistic regression model on unseen data --> performed 10-fold cross validation

Can do best subset selection, forward stepwise selection, and backward stepwise selection --> compare best models picked by each method
-Variable selection methods --> then plug the result of that into logistic regression, LDA, QDA, etc. 

4) General thoughts:

-13 predictor variables --> we suspect that not all of them will be significant in predicting whether a heart attack will occur or not

