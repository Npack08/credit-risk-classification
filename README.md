# credit-risk-classification
Overview of the Analysis:
The purpose of this analysis was to compare the credit risks associated with borrowers. Labels such as '(0)' healthy loan and '(1)' high risk loan leabels are used in the model to visualize and present the data findings.

The financial data was stored in a csv file. Using panadas, I created a path to view the csv file data in a pandas dataframe. After creating the dataframe I then split the daya into training and testing sets.

Stages of the machine learning process:
*First stage of this process was to prepare the data by creating a path for the csv file and creating a pandas data frame by reading the csv file. The data frame set is then split into X and Y labels. Value counts is then used to check the count of the labels. 

Briefly touch on any methods you used (e.g., LogisticRegression, or any resampling method).
*The LogisticsRegression model is used and the classifier is then established. The model is then split into training and testing data sets by using the train_test_split method using the original data. The training set was the x_train and y_train. 
*Predictions are then made using the testing data. 

Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models. 
* The Balanced Accuracy Score, Confusion Matrix and Classification report are then used to make the predictions.
Machine Learning Model 1:
*Balanced Accuracy Score: 
.9924
*Precision:
Healthy loan (0)= 1.00
High Risk Loan (1) = 0.87
*Recall Score:
Healthy Loan(0) = 1.00
High Risk Loan(1) = 0.89

Machine Learning Model 2:
*Balanced Accuracy score:
.9942
*Precision:
Healthy loan (0)= .99
High Risk Loan (1)= 0.99
*Recall Score:
Healthy Loan (0)= .99
High Risk Loan (1) = 0.99

Summary
My recommendation is the logistic regression model with the resampled training data as it had a higher ballanced accuracy score compared to the model using the original data.

The model using the resampled training data performed the best at prediciting the high-risk loans which is the most important aspect for the problem presented.

Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the 1's, or predict the 0's? )
Performance of each machine learning model would depend on the specific problem trying to be solved. Since this problem is looking at credit risk classifications, then predicting the high risk loans correctly is more important than predicitng the healthy loans. 
