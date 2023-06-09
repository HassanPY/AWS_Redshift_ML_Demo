# AWS_Redshift_ML_Demo

In this tutorial, you use Amazon Redshift ML to create a customer churn model with the CREATE MODEL command, and run prediction queries for user scenarios. Then, you implement queries using the SQL function that the CREATE MODEL command generates.

You can use a simple CREATE MODEL command to export training data, train a model, import the model, and prepare an Amazon Redshift prediction function. Use the CREATE MODEL statement to specify training data either as a table or SELECT statement.

This example uses historical information to construct a machine learning model of a mobile operator’s customer churn. First, SageMaker trains your machine learning model and then tests your model using the profile information of an arbitrary customer. After the model is validated, Amazon SageMaker deploys the model and the prediction function to Amazon Redshift. You can use the prediction function to predict whether a customer is going to churn or not.