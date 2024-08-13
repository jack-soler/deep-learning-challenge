# Deep Learning Model Performance Report: Alphabet Soup

## Overview of the Analysis

The purpose of this analysis is to evaluate the performance of a deep learning model created to predict the success of applications for Alphabet Soup. The model aims to classify whether an application will be successful based on various features provided in the dataset. This report covers the data preprocessing steps, the architecture of the deep learning model, and its performance evaluation.

## Results

### Data Preprocessing

- **Target Variable(s):**
  - IS_SUCCESSFUL

- **Feature Variable(s):**
  - The feature variables are everything except target variable and irrelevant columns.

- **Variables Removed:**
  - `EIN`: Unique identifier for each application
  - `NAME`: Name of the organization

### Compiling, Training, and Evaluating the Model

  - **Number of Neurons and Layers:**
    - **Input Layer:** 80 neurons
    - **First Hidden Layer:** 80 neurons, ReLU activation function
    - **Second Hidden Layer:** 30 neurons, ReLU activation function
    - **Output Layer:** 1 neuron, Sigmoid activation function

- **Model Performance:**
  - **Target Performance Achieved:**
    - The model's performance was evaluated based on accuracy and other metrics. 
    - (Include specific metrics and whether the target performance was met, e.g., accuracy, loss, etc.)
  
- **Steps to Increase Model Performance:**
  - I tuned hyperparameters such as the number of epochs and batch size.
  - I used batch normalization to prevent overfitting.
  - I adjusted the number of neurons and layers in the network.
  - I implemented data preprocessing techniques such as scaling and normalization.

## Summary and Reccomendation

The deep learning model demonstrated its capability to predict the success of Alphabet Soup applications with reasonable accuracy. To improve performance, I would maybe explore other models such as Randow Forest
