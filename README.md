## Name : Piyush Bamnia
## Company : CODTECH IT SOLUTIONS
## ID : CT08DS8826
## Domain : Data Science
## Duration : OCTOBER 5th, 2024 to NOVEMBER 5th, 2024
## Mantor :  Neela Santhosh Kumar

## Model Building Overview
Objective: The goal of the model building phase is to develop a predictive model that can accurately estimate house prices based on the provided features.

### Steps Involved:

#### Feature Selection:

Features such as area, bedrooms, bathrooms, stories, mainroad, guestroom, basement, hotwaterheating, airconditioning, parking, prefarea, and furnishingstatus are selected as predictors.

#### The target variable is price.

#### Train-Test Split:

The dataset is split into training and testing sets using an 80-20 ratio. This split ensures that the model is trained on a portion of the data and its performance is evaluated on unseen data.

#### Model Building:

A Linear Regression model is chosen for its simplicity and interpretability.

The model is trained using the training data (X_train and y_train).

#### Predictions:

The trained model is used to predict house prices on the testing set (X_test).

These predictions are compared with the actual prices (y_test) to evaluate the model's performance.

#### Model Evaluation:

Mean Squared Error (MSE): Measures the average squared difference between the predicted and actual values. A lower MSE indicates a better fit.

R-squared (R²): Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables. Values closer to 1 indicate a better fit.

#### Visualizing Performance:

A scatter plot of actual vs predicted house prices is generated. This plot helps visualize the model's accuracy and identify any systematic errors.

#### Results:

The model's performance is quantified using MSE and R², providing insights into its predictive accuracy OF 73%.

The scatter plot of actual vs predicted prices offers a visual confirmation of the model's performance.
