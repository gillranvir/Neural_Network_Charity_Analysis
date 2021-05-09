# Neural_Network_Charity_Analysis
## Overview of the Analysis
The purpose of this analysis was to use machine learning and neural networks for predicting the success of applicants looking to be funded by Alphabet Soup.
## Results
### Data Pre-Processing
* The success outcome variable was used as target for the model, referring to the "IS_SUCCESSFUL" column
* All variable excluding EIN and NAME were considered as features of the model
* EIN and NAME columns were removed from the input data
### Compiling, Training and Evaluating the model
1. Information about Neurons, Layers and Activation Functions
* Number of Hidden Layers: 2
* Number of Neurons in First Hidden Layer: 80
* Number of Neurons in Second Hidden Layer: 30
* Activation Function for Hidden Layers: ReLU
* Activation Function for Outer Layer: Sigmoid
2. Accuracy level of 72.6% was achieved
3. Additional hidden layers were used along with different combinations of neurons and epochs as well as different activation functions.

## Summary
The deep learning model was not able to achieve the desired accuracy level of 75%. Since the outcome is binary in nature, using a Supervised machine learning model could be explored to improve accuracy.
