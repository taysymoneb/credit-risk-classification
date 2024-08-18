# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
   
   The purpose of the analysis is to make predictions for loan applications and potential risk (defaults) using a logistic regression model. The model is used to try and identify loans that are likely to be healthy and loans that are likely to default (high-risk). This is vital for those in the financial field to decrease the risk of losses and make wise decisions when lending to loan borrowers.

* Explain what financial information the data was on, and what you needed to predict.

   The financial information that data was on included the loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt and loan status. The loan status was needed to predict whether an application would be healthy or high-risk.

* Describe the stages of the machine learning process you went through as part of this analysis.
   
   I first loaded the csv file into the notebook and created a pandas dataframe to view its contents, with special focus on the loan status column. Then, I separated the data into features (everything other than loan status) from the y variable (loan status). After, I did a Train-Test Split, where the training set was used to train the model and the testing set evaluated the model performance. Logistic Regression was used as the model and the model was fit using the training data. The trained model was used to make predictions on the test data. Lastly, the performance of the model was evaluated through the use of a confusion matrix and classification report. The confusion matrix provided insights into the number of true positives, true negatives, false positives, and false negatives. In the classification report the precision, recall, F1-score, and support were evaluated to see how accurate the model was in identifying healthy and high-risk loans.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

• Recall: For healthy loans, the model had 100% accuracy. For high-risk loans the model missed 9% and correctly labeled 91% of high-risk loans.

• Precision: For healthy loans, the model predicted every loan correctly (100%) and for high-risk loans the model predicted the 86% were high-risk.

• Accuracy: The model predicted correctly for 99% of the data in the test dataset.

## Summary

Summarize the results of the machine learning model.

The logistic regression model was extremely accurate in predicting healthy loans. This means that the model would be perfectly accurate in predicting loans that would not default. The model was also quite accurate in predicting high-risk loans, but with a slightly lower accuracy percentage. Therefore, logistic regression would be a strong pick for predicting healthy and high risk loans. 




