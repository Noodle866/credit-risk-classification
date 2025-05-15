# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

** To test healthy loan data vs high-risk loan data. 

* Explain what financial information the data was on, and what you needed to predict.

** The financial information the data was on is loan size, interest rate, borrower income, debt to income, number of accounts,derogatory marks, total debt, and loan status What you needed to prodict was loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt. 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`). 

** Basic information for the variabels used to predict
    ** "y" loan_status, Length: 77536, dtype: int64
    ** "x" loan_size, interest_rate, borrower_income, debt_to_income num_of_accounts, derogatory_marks, total_debt.

* Describe the stages of the machine learning process you went through as part of this analysis.

** 1. Import libraries, import csv, and create dataframe.
** 2. Separate the data into labels and features.
** 3. Review "y" variables series and "x" dataframe.
** 4. Split the data into training and testing datasets by using `train_test_split`.
** 5. Create a Logistic Regression Model with the Original Data.
** 6. Evaluate The model.
** 7. Answer questions.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

** Methods used: 'LogisticRegression'

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

** accuracy:  f1-score 0.99
** macro avg: precision 0.92 recall 0.97
** weighted avg: precision 0.99 recall 0.99
** healthy loan: precision 1.00 recall 0.99
** high-risk loan: precision 0.84 recall  0.94

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?

** The Logistics regression model seems to preform the best. The way I know it preforms the best is because its the only model we used.  

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

** It is more important to predict the '1''s because a single '1' could effect more than one '0'.

If you do not recommend any of the models, please justify your reasoning.

** I do recommend the model. 