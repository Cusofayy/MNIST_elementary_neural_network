# Optimizing a Neural-Network for MNIST Handwritten Digit Classification Dataset
An implementation of a neural-newtork for MNIST combined with early stopping and dropouts.

# Architecture of the NN
The model is a 3 layer neural network with the followoing architecture:
  + Input layer : 784 nodes (MNIST images size)
  +  First fully-connected layer of 1024 nodes
  +  Second fully-connected layer of 243 nodes
  +  Output layer of 10 nodes, one for each digit

The activation function is ReLU

# Dropouts

Dropout is implemented to the first (0.5) and second (0.2) fully-connected layers


# Training strategy:

Combining the early stoping strategy with a high patience and a low min_delta maximizes the accuracy of the model without fallin in the pit of overfitting.

# Results

98.21% accuracy for a simple 3 layers neural newtork
