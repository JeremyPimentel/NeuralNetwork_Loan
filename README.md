# NeuralNetwork_Loan


## Overview of the analysis:
The purpose of this analysis was to use neural networks to predict loan acceptance/rejection using various paramaters. 




## Results: 
Data Preprocessing
What variable(s) are considered the target(s) for your model?
- Our target was whether or not a loan was successful.

What variable(s) are considered to be the features for your model?
- the features of our model range from application type, affiliation, loan amount, and income. 

What variable(s) are neither targets nor features, and should be removed from the input data?
- Variables that should be removed are variables that cause noise withint the model. This was such for variables labelled as 'Other'.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The number of neurons selected was 8 in the first hidden layer and 5 in the second hidden layer, plus 1 neuron for both input and output. The output function chosen was sigmoid to give a yes or no, output. For the hidden layers, ReLu was chosen to ignore values below zero. 
Were you able to achieve the target model performance?
- We were not able to achieve a target of 75%, our model achieved accuracy close to 55%

What steps did you take to try and increase model performance?
- To improve our performance, we increased the hidden layers to 4, changed the activation functions to leaky ReLu, with the 4th hidden layer using a tanH function. The total neurons increased to 390. We also removed noisy variables. With these changes our model achienved an accuracy score of 63%.

## Summary 
To summarize, our model was first quite scaled back, but our accuracy scores did not surpass 55%. The model was tuned to be more robust, totalling our accuracy to 63%. To further solve our classification issue, we would recommend trying more hidden layers with more neurons and trying differeny functions. Adding more Epochs for the model could also help. 
