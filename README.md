# Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis is to build a binary classification model capable of predicting whether a charity will effectively use the money raised if funded. By leveraging machine learning and neural networks a deep learning model is generated to evaluate potential success. After generating the initial neural network model and measuring its efficacy, various adjustments to its inputs and structure are implemented in order to optimize performance.

## Results

### Data Preprocessing

- The IS_SUCCESSFUL variable is the target of the model
- The following variables are the features of the model:
  - APPLICATION_TYPE
  - AFFILIATION
  - CLASSIFICATION
  - USE_CASE
  - ORGANIZATION
  - STATUS
  - INCOME_AMT
  - SPECIAL_CONSIDERATIONS
  - ASK_AMT
- The following identification variables are neither targets nor features and are dropped from the input data:
  - EIN
  - NAME

### Compiling, Training, and Evaluating the Model

- The initial model is structured as follows:
  - Layers:
    - First hidden layer: 80 neurons with ReLU as the activation function
    - Second hidden layer: 30 neurons with ReLU as the activation function
    - Output layer: 1 neurons with Sigmoid as the activation function
  - 110 neurons were used in the hidden layer, as it's roughly 2.5x the number of input features (43)
  - The ReLU activation function was selected for both hidden layers as all feature values are positive
  - The Sigmoid activation was selected for the output as the model is a binary classifier
  - Model summary:
    - ![nn-original-summary-output](imgs/nn-original-summary.png)

- Were you able to achieve the target model performance?
- What steps did you take to try and increase model performance?

## Summary

Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation

- There is a summary of the results
- There is a recommendation on using a different model to solve the classification problem, and justification
