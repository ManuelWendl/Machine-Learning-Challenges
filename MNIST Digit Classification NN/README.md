# Neural-Network-MNIST-Digit-Recognition
This repository gives a good glance on how neuronal networks actually work behind the scenes. 

The task was to build a classifying algorithm in order to reccognize digits from the well known MNIST handwritten digit dataset. 
The algorithms are based on supervised learning, in form of a neural network with multiple hidden layers.

The trainings and test dataset are strictly seperated and both downloaded from http://yann.lecun.com/exdb/mnist/. 

There are two versions of Neural Networks in the repo:
> - Nmist Digit Recognition Basic Neural Network:
    It contains a basic implementation of a neural network, existing of neurons, which are connected by weighted edges. In this basic version no biases are added to         the network. The network architecture is limited to two hidden layers with variable number of neurons. (The default settings are 200 and 60 neurons). The advantage of this basic implementation, is that it has a better readability, inorder to understand the process during forwardfeed and backtracking. 
> - Nmist Digiit Recognition Advanced Neural Network:
    This version contains a network with biases for each neuron. Additionally it is possible to fully custamize the structure of the neural network, such that also     
    deep structures can be used.
    
