# Neural_Network_Charity_Analysis

## Analysis Overview

The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations using following methods:  preprocessing the data for the neural network model, compile, train and evaluate the model, optimize the model.

## Resources
Data Source: charity_data.csv
Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

## Results

### Data Preprocessing

- The column IS_SUCCESSFUL contains binary data and  considered as the target for our model. 
The model accuracy is under 75%. This is not a satisfying performance to help predict the outcome of the charity donations.

- The  columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model.

- The columns EIN and NAME are identification information and have been removed from the input data.

### Compiling, Training, and Evaluating the Model

- This deep-learning neural network model is made of two hidden layers with 80 and 30 neurons.

- The model accuracy is under 75%. This is not a satisfying performance to help predict the outcome of the charity donation

- To increase the performance of the model, we applied bucketing to the feature ASK_AMT. We increased the number of neurons on one of the hidden layers, then we used a model with three hidden layers.

## Summary

The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is pretty average we could say that the model is not outperforming.
Since we are in a binary classification situation, we could use a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate  a classified output and evaluate its performance against our deep learning model.
