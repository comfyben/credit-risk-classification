# credit-risk-classification

The purpose of the analysis was to create a logistic regression model that predict whether a loan is healthy or high-risk based off facts that affect the borrowers credit. Those factors include the size of the loan, its interest rate, the borrower's income and more. The data we would want to predict would be a summation of all of the borrowers information that would show that this loan is risky and that the borrower is not creditworthy of the loan. 

This model involed using logistic regression, a machine learning model that works with the data that we already have classified. Logistic regression is great at predicting a true or false outcome. It works by first splitting up our data into training and testing chunks. The model is fit to and trained on the training values before using the test chunk to make predictions. Those predictions are then evaluated using a confusion matrix and a classification report. These evaluation methods show us how well our model performed.

## Classifiction Report: Logistic Regression

- accuracy: 0.99
	- this model is very accurate the total number of correct predictions is very close to the total predictions altogether. 

- precison: Healthy Loans 1.00, Risky Loans 0.87
	- here we see that the model's ratio of correct and incorrect predictions for unhealthy loans is much lower than healthy. There is a higher false-positive rate in the unhealthy loans than the healthy

- recall: Healthy Loans 1.00, Risky Loans 0.89
	- similar to precision, recall evaluates the predicted positive values but this time against the total number of actual positive values. Risky loans have a lower number of correctly predicted values than total values of that class. Meaning that the model has  a high false-negative rate with unhealthy loans.

# Summarize

After developing the model by splitting, training, then testing the dataset. The predicitons displayed perfect precison and recall to predict the healthy loans. Howerver, without more repetitions of splitting the dataset, it's hard to say whether or not this is the right one for the job. The at-risk loans are the ones we are mostly trying to understand and predict. Due to the precision and recall being so much lower on the classification report, I would not recommend this model for use. 