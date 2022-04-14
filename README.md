# pytorch-phishing-rnn

This was done as part of the project for CS3244: Machine Learning, a module in National University of Singapore (NUS).

The Python notebook contains a trained vanilla Recurrent Neural Network (RNN) that can take in an input URL and predict with high accuracy (roughly 87 ~ 88%) whether it is likely to be a Phishing website or a Non-Phishing website. Each URL is broken down into 16 different attributes and then processed using the network in order to determine the probabilities for each class.

The implementation can (and should) be modified to incorporate state-of-the-arts extensions and improvements in the future in order to increase accuracy of the model, while bearing in mind potential risks of overfitting.
