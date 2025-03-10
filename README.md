# credit-risk-classification

## Analysis Overview 
the purpose of this activity is to build a model that can identify the creditworthiness of borrowers by using a dataset of historical lending activity from a peer-to-peer lending services company.
data source: Resource/lending_data.csv

**1. Split the Data into Training and Testing Sets**

  	1. Open the starter code notebook and use it to complete the following steps:
  	2. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
  	3. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
  	4. Split the data into training and testing datasets by using train_test_split.


**2. Create a Logistic Regression Model with the Original Data**

	1. Fit a logistic regression model by using the training data (X_train and y_train).
	2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
	3. Evaluate the model’s performance by doing the following:
		1. Generate a confusion matrix.
		2. Print the classification report.

## Analysis report
How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels
