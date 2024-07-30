# House Price Prediction
This project aims to develop a machine learning model to predict house prices using the Boston housing dataset. The model utilizes Python, Scikit-learn, and TensorFlow to perform data preprocessing, model training, evaluation, and deployment.
# Objective
The primary objective of this project is to build a predictive model that can accurately estimate the prices of houses based on various features such as the number of rooms, crime rate, distance to employment centers, and other relevant attributes. This project serves as an example of how to handle regression problems in machine learning using neural networks.
# Features
Data Preprocessing: The dataset is cleaned and preprocessed, including handling missing values and normalizing the features.
Feature Selection: All relevant features are selected and used to train the model.
Model Training: A neural network model is built and trained using TensorFlow and Keras.
Model Evaluation: The model's performance is evaluated using Mean Squared Error (MSE) on a test dataset.
Visualization: Training and validation loss are plotted to visualize the model's learning process.
Model Deployment: The trained model is saved for future use.
# Dataset
The Boston housing dataset consists of 506 samples with 13 features and 1 target variable (MEDV - Median value of owner-occupied homes in $1000's). The dataset includes the following features:

CRIM: Per capita crime rate by town
ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
INDUS: Proportion of non-retail business acres per town
CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX: Nitric oxides concentration (parts per 10 million)
RM: Average number of rooms per dwelling
AGE: Proportion of owner-occupied units built prior to 1940
DIS: Weighted distances to five Boston employment centers
RAD: Index of accessibility to radial highways
TAX: Full-value property tax rate per $10,000
PTRATIO: Pupil-teacher ratio by town
B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black people by town
LSTAT: Percentage of lower status of the population
MEDV: Median value of owner-occupied homes in $1000's (target variable)
