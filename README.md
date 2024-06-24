Diabetes Prediction Using Neural Networks
Overview
This project aims to predict the onset of diabetes based on various health metrics using a neural network model. The dataset contains information such as pregnancies, glucose levels, blood pressure, and other health indicators. The model is built and trained using TensorFlow/Keras, achieving a test accuracy of approximately 77%.

Dataset
The dataset used in this project includes the following features:

Pregnancies
Glucose
BloodPressure
SkinThickness
Insulin
BMI
DiabetesPedigreeFunction
Age
Outcome (target variable)

Installation
To run this project, you need to have Python installed along with the necessary libraries. You can install the required libraries using pip:
pip install pandas numpy scikit-learn tensorflow


Here's a summary of the steps followed in the code:

Data Loading and Preprocessing:

Load data into a pandas DataFrame.
Split data into features (X) and target (y).
Split the data into training and testing sets.
Standardize the features.
Model Building:

Build a sequential neural network model with TensorFlow/Keras.
Compile the model with Adam optimizer and binary crossentropy loss.
Model Training:

Train the model on the training set with a validation split.
Evaluate the model on the test set.
Predictions and Evaluation:

Make predictions on the test set.
Compare predicted outcomes with actual outcomes.
Print model training and test accuracies.


This project demonstrates the use of neural networks for predicting diabetes based on health metrics. The model achieved a reasonable accuracy, and further tuning and feature engineering could potentially improve the performance.
