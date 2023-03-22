# Navie_base_diabetes
based on a  real diabetes  datset which include 8 variables(pregnencies, Glucose, Blood pressure,Skinthickness, Insulin,BMI,DiabetePedigreeFunction, age) and response variable(outcome), I build a model to predict the response variable for other cases.
dataset has missing value, so I used mice and randomforest library to predict the missing value
I use descriptive stattistac tools such histogram to get a basic understanding of the data and the state of the variables
in the second part: Data modeling, the stage begins with a process called Data Splicing, wherein the data set is split into two parts:
Training set: This part of the data set is used to build and train the Machine Learning model.
Testing set: This part of the data set is used to evaluate the efficiency of the model.
finaly, after building the model,I used new case to predict the outcome
