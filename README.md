# deep-learning-challenge
Module 21 Challenge Neural Networks and Deep Learning
1. Overview�of the analysis: Explain the purpose of this analysis.
			The main purpose of this analysis is to apply various models of neural networks on the data set to predict the accuracy of best possible applicants who would be successful in their ventures. 

2. Results: Using bulleted lists and images to support your answers, address the following questions:
o Data Preprocessing
* What variable(s) are the target(s) for your model?
* 	IS_SUCCESSFUL is the main target variable from the dataset provided
* What variable(s) are the features for your model?
* 	All the categorical data created from main dataset minus the �Is_Successful� column, forms the part of features
* What variable(s) should be removed from the input data because they are neither targets nor features?
* 	EIN and Name should be removed as they are non- beneficial data
o Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
* 	In the optimized models, various combinations for these variables have been tried out ranging for 
	for neurons from 8 to 40,
	for layers 2-3-4 layers have been used
	for activation: Relu, Sigmoid, Linear are used interchangeably between the layers 
The objective is to achieve the 75% accuracy in predicting the best fit for funding and as part of optimization  
* Were you able to achieve the target model performance?
* 	No mater how many ever combinations have been used, I was not able to achieve 75% accuracy. 
* What steps did you take in your attempts to increase model performance?
1. Additional columns dropped to increase the efficiency of data focus.
2. Activation method for the output layer changed from Linear to Sigmoid to Relu to see any improvement. 
3. Added more layers and gradually increased the neurons count.  
Summary: Overall the Linear activation model followed by Sigmoid activation models seems to have better accuracy than RELU activation mode. 
Data cleansing of the dataset prior to running the neuron model tests might yield better accuracy results.
