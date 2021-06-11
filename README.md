# digit-recognition-using-multilayer-percepteron

We will be creating a neural network model for classification of hand-written digits.
The dataset we will be using for this is MNIST dataset which is a collection of black and white images of hand-written digits ranging from 0-9.
The resolution of the images are 28*28. We will be using Pytorch for this task.

Required packages for this assignment: 
<ul>
  <li>torch</li>
  <li>torchvision</li>
  <li>numpy</li>
  <li>matplotlib</li>
  <li>sklearn</li>
  </ul>

## Design a Neural Network to classify the MNIST hand-written images
We will be designing a simple 3 layer neural network which will be trained to classify the handwritten images correctly.

Description of the neural network parameters:
<ul>
  <li>The first hidden size should be 100</li>
  <li>The second hidden layer should be 50</li>
  <li>Dropout probability should be 0.2</li>
  <li>Sigmoid activation function should be used</li>
  </ul>
## Playing with the hyper-parameters
Finding and setting the right set of parameters is a crucial part of deep learning research. Although there are many ways of doing it, you will find it manually for this task In this regard we will be doing the following:
<ul>
  <li>Check the effect of classification accuracy on the the number of neurons in the first hidden layer by changing the number of neurons in the first hidden layer from 2...100.</li>
  <li>Train the model for 10 epochs and plot the accuracy to neuron curve.</li>
## Ploting the accuracy Curves
Another important thing every deep learning practitioner should do is to check whether the loss is decreasing with increased training epochs. This can be checked y plotting the loss and accuracy curves.
