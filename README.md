# deep-learning-challenge
Module 21 Challenge

NN Challenge


This Neural Network Model is meant to predict the whether an organization applying for funding is likely to be successful using a number of different features of over 34,000 past organizations that have received funding.

Target variable: IS_SUCCESSFUL
Features: EIN	NAME	APPLICATION_TYPE	AFFILIATION	CLASSIFICATION	USE_CASE	ORGANIZATION	STATUS	INCOME_AMT	SPECIAL_CONSIDERATIONS	ASK_AMT	
The model uses 2 hidden layers with units set to 8, and 5, both using the ‘relu’ activation function.
The model accuracy: 0.7310


I made a second notebook where I tried different settings for activation functions, neuron number,  number of layers, and the cutoff value for the ‘other’ value for  the APPLICATION_TYPE, and CLASSIFICATION columns. The best accuracy I was able to reach was 0.7320. Here are the changes I made on this model:

 application_cutoff was set to 1000 instead of 500,

The number on neurons was reduced to 6, and 3
I reduced the epochs to 80 instead of 100,

The first hidden layer activation function was set to ‘tanh’ instead of ‘relu’.
