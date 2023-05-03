# Logistic_Regression_TF with TensorFlow


This script demonstrates how to implement a logistic regression model using the TensorFlow library. It covers the following steps:

Importing necessary libraries

Generating a random dataset for logistic regression

Splitting the data into training and testing sets

Normalizing the feature variables

Building and compiling the logistic regression model

Training the model on the training data

Plotting the training and validation loss

Evaluating the model on the test data

Generating model predictions on the test features

Calculating key metrics for evaluating the model's performance

Plotting the confusion matrix

Dependencies

numpy

matplotlib

tensorflow

scikit-learn

seaborn

Steps

Import necessary libraries: Import the required libraries for data manipulation, visualization, and machine learning.

Generate random data: Generate a random dataset for logistic regression with 1000 samples, 4 features, and 2 classes.

Split the data: Split the dataset into 80% training and 20% testing sets.

Normalize the feature variables: Create a normalization layer and adapt it to the training data.

Build and compile the logistic regression model: Build a logistic regression model using the Sequential API from TensorFlow, and compile it with the Adam optimizer and binary cross-entropy as the loss function.

Train the model: Train the model on the training data for 500 epochs, using a validation split of 20%.

Plot the training and validation loss: Visualize the training and validation loss over the epochs.

Evaluate the model: Evaluate the model's performance on the test data and print the loss and accuracy.

Generate model predictions: Generate model predictions on the test features and convert them to integer values.

Calculate key metrics: Calculate the accuracy, confusion matrix, and classification report based on the true and predicted values.

Plot the confusion matrix: Visualize the confusion matrix using a colormap.

Usage

To run this script, make sure you have the required dependencies installed. Execute the script in a Python environment, and the output will display the training and validation loss plot, test results, and the confusion matrix plot.
