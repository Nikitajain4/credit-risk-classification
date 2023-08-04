# credit-risk-classification
Supervised Machine Learning
Supervised Machine Learning

In this Credit Risk Classification Assignment,we used Logistic Regression Model.

This type of statistical model (also known as logit model) is often used for classification and predictive analytics. Logistic regression estimates the probability of an event occurring, such as loan paid or not, based on a given dataset of independent variables. Since the outcome is a probability, the dependent variable is bounded between 0 and 1. In logistic regression, a logit transformation is applied on the odds—that is, the probability of success divided by the probability of failure.

In our dataset we have loan size,,interest rate,borrower income,debt to income ratio, total debts and loan status.Based on this , we wanted to predict the loan status based on variable factors.

1.We splited our dataset into Training and Testing Sets.

2.We Created the labels set (y) from the “loan_status” column, and then created the features (X) DataFrame from the remaining columns.

3.Then we again, splited the data into training and testing datasets by using train_test_split.

4.Created a Logistic Regression Model with Original Data .

5.Saved the predictions on the testing data labels by using thre testing feature data and the fitted model.

6.Evaluated the model's performance by generating a Confusion Matrix.

7.Printed the Classification Report.

Results:

Training Classification Report (Model 1)

Accuracy 0.99 Precision 0 - 1.00, 1 - .85 Recall 0 - .99, 1 - .89

Testing Classification Report(Model 2)

Accuracy 0.99 Precision 0 - 1.00, 1 - .87 Recall 0 - 1.00, 1 - .89

Summary

Looking at the two classification reports for the training and test data, it looks as if model performance declined--albeit slightly--on the test data. This is to be expected: this is how well the model is performing on data that the model hasn't seen before. If we're still getting strong precision and recall on the test dataset, this is a good indication about how well the model is likely to perform in real life.
