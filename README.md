# StudentPerfomanceCheck

Develop a performance check system for students

### __init__.py, used as a package

### src/components - that will be used in the project

# Step by Step Process - 

###  read a db from any src or file is called data ingestion
### data transform- transorm the data, like OHE, change from category to numerical 
### model train- train the model like linear regression, decision tree, random forest, confusion matrix
### model evaluation- check the model is good or not
### model pusher- push the model to s3 bucket

### src/pipeline - what pipeline? 2 types- training, prediction
### training pipeline- read the data, transform the data, train the model, evaluate the model, push the model
### prediction pipeline- read the data, transform the data, predict the model

### src/utils - used for common functions
### src/exceptions - used for custom exceptions
### src/logger - used for logging, use to log the error in log file(logger)
### src/config - used for configuration