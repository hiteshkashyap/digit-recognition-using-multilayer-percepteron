# digit-recognition-using-multilayer-percepteron

We will be creating a neural network model for classification of hand-written digits.
The dataset we will be using for this is MNIST dataset which is a collection of black and white images of hand-written digits ranging from 0-9.
The resolution of the images are 28*28. We will be using Pytorch for this task.

Required packages for this assignment
[*] torch
[*] torchvision
[*] numpy
[*] matplotlib
[*] sklearn

## Design a Neural Network to classify the MNIST hand-written images
We will be designing a simple 3 layer neural network which will be trained to classify the handwritten images correctly.

Description of the neural network parameters:
[*] The first hidden size should be 100
[*] The second hidden layer should be 50
[*] dropout probability should be 0.2
[*] sigmoid activation function should be used

## Playing with the hyper-parameters
Finding and setting the right set of parameters is a crucial part of deep learning research. Although there are many ways of doing it, you will find it manually for this task In this regard we will be doing the following:

[1] Check the effect of classification accuracy on the the number of neurons in the first hidden layer by changing the number of neurons in the first hidden layer from 2...100. [2] Train the model for 10 epochs and plot the accuracy to neuron curve.
## Ploting the accuracy Curves
Another important thing every deep learning practitioner should do is to check whether the loss is decreasing with increased training epochs. This can be checked y plotting the loss and accuracy curves.
