# Neural_Network_Charity_Analysis

## Overview:
Preprocessing data to use for neural network model. Complie, train and evaulate data. Optimize the model.

## Resources:
Charity_data.csv, Jyputer Lab, Tensorflow

## Results: 
Data Preprocessing
What variable(s) are considered the target(s) for your model?
	The columns EIN and NAME are identification information and have been removed from the input data.
What variable(s) are considered to be the features for your model?
	The IS_SUCCESSFUL column is the feature chosen for this dataset.
What variable(s) are neither targets nor features, and should be removed from the input data?
	The EIN and NAME columns will not increase the accuracy of the model and can be removed to improve code efficiency.

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
	I used 4 hidden layers from 120(relu) to 80(relu) to 40(sigmoid) to 20(sigmoid) to 1(linear)
Were you able to achieve the target model performance?
	The target for the model was 75%, but the best the model could produce was 72.7%.
What steps did you take to try and increase model performance?
	Running additional neuron hidden layers.


## Summary: 
The relu and sigmoid activations yielded a 72.7% accuracy, which is the best the model could produce using various number of neurons and layers. 
A good model to recommend is the Random Forest model because Random Forest is good for classification problems. 