heart_disease_prediction
 This is project is about predicting the heart disease of a person based on the given data.
The dataset consist of 16 columns including target variable.
We read the dataset and preprocess the data to handle missing values.
We perform EDA (Exploratory Data Analysis) to inspect the data and understand the features and thier behaviour.
we desgin various plots to understand the data better.
detect the outliers and handle them.
we check the correlation and understand importance of the features.
select the features on the EDA and correlation.
X, y are split into the train, test data
Model training on the train data.
Evaluate the model performace
Tune hyperparameters
select the best performing model
Create the example dataset to test.
Save the model as pickle file

# API
Load the model pickle file
create FastAPI to expose the predictions.
Test the API endpoint in postman or swagger Ui

#steamlit Ui
create a steamlit UI.
call the API predection to display in UI.
Test the Application.
