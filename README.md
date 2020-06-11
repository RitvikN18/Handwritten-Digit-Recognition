# Handwritten-Digit-Recognition
Handwritten Digit Recognition on MNIST dataset using tensorflow framework

Convolutional Neural Networks were used to build the model.

# Packages
1. tensorflow
2. numpy
3. matplotlib
4. pandas

# Architecture
1. Input features: shape = 28*28
2. Convolutional layer with 64 filters, of 3x3 kernel size with relu activation function
3. MaxPooling layer with 2x2 kernel size
4. Convolutional layer with 64 filters, of 3x3 kernel size with relu activation function
5. MaxPooling layer with 2x2 kernel size
6. Dense layer consisting of 128 neurons with relu activation function and a kernel regularizer L2 with weight 0.0001
7. Dropout function to drop 20 percent of the dataset
8. Dense layer consisting of 128 neurons with relu activation function and a kernel regularizer L2 with weight 0.0001 
9. Dense layer consisting of 10 neurons for output with softmax activation function

Optimizer - adam
Loss function - Sparse categorical cross entropy

# Performance
Train accuracy - 98.89%
Test accuracy  - 98.85%
