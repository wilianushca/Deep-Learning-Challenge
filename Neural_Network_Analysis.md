# Report on Neural Network Model Performance

## Overview of the Analysis:

The purpose of this analysis is to develop a deep learning model using a neural network to predict the success of organizations funded by Alphabet Soup. By training the model, the aim was to create a predictive model that can classify the succes in organizations using the funding effectively.

## Results:

### Data Preprocessing:
- **Target Variable**:
  - The target variable for our model is 'IS_SUCCESSFUL', which indicates whether the organization was successful

- **Features**:
  - Features for our model include various metadata about each organization, such as 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', and 'SPECIAL_CONSIDERATIONS'.

- **Variables to Remove**:
  - The 'EIN' and 'NAME' columns were removed from the input data as they are identification columns and do not provide useful information

### Compiling, Training, and Evaluating the Model:

- **Neural Network Model**:
The first hidden layer has 80 neurons, and the second hidden layer has 30 neurons.
The target model performance was close (74%) but not able to achieve the desired 75%.

- **Steps to Increase Model Performance**:
  - Adjusted the number of neurons and layers in the neural network model.
  - Experimented with different activation functions for the hidden layers.

## Summary:
In summary, while the model achieved reasonable accuracy, it fell short of the target performance of 75%. Despite several attempts to optimize the model through adjusting architecture, hyperparameters, and preprocessing techniques, further improvements may be necessary to meet the target. A different approach that could potentially improve classification performance is the implementation of ensemble learning techniques, such as Random Forest. Further experimentation and tuning is recommended to develop a more robust and accurate predictive model for Alphabet Soup's funding decisions.
