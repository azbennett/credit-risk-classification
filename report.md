# Module 12 Report Template

## Overview of the Analysis of assignment #20 - Credit Risk Classification

* In this project we are using a small sample of histortical banking/credit data to try and use logistic regression models to accurcately predict the credit risk of loans.
* Provided within the data set was historical data for loan size, APR, income, debt to income ratio, how many open accounts, how many bad accounts, and the total debt of the barrower.  
*The primary label we were testing against was the loan status which was flagged as a 0 or 1 - 0 being a healthy low risk account - 1 being higher risk.
* Using two methods of logistic regression analysis I was able to use the sci-kit learn packages to take the data - train it - test it and split it up so we can print out a report showing the accuracy of our methods and results of the regression model.  
* This includes using the train_test_split(), LogisticRegression(), predict(), and finally the accuracy_score() functions to do so.  Finally ending with a classification_report() to  better visualize the end results of the two  loan types and the machine learning results.


## Results

* Machine Learning Model 1:
  * Resulted in a an accuracy value of 99.24%
  * For healthy loans it had a Precision score of 100% and recall score of 100%
  * For higher risk loans we saw a Precision score of 87% and recall score of 89%

* Machine Learning Model 2:
  * Resulted in a an slightly higher accuracy value of 99.5975%
  * For healthy loans it had a Precision score of 100% and recall score of 100%
  * For higher risk loans we saw a Precision score of 87% and recall score of 100%

## Summary

* Due to the higher accuracy, and higher recall scores I am inclined to believe that the re-sampled regression model from model 2 is the better option.  
* Both models had very high accuracy scores - but the numbers do not lie in this case giving a slight edge to model 2.

* Being able to predict loan risks is a vital part of any financial institution.  Even with both models being 99% or higher - the fact is the second method had a higher accuracy rating which could mean saving millions or billions of dollars depending on the size of the institution this is being used in.  

* It is critically important for both the lender and the borrower to be able to give accurate approvals.  This can save money for the lending institution providing the loan or it could let the borrower know that whatever they are planning on purchasing is out of their means. (May not stop them from doing it - as it'll likely just have a higher APR to adjust for the risk value)

