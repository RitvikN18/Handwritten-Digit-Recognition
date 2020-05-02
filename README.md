# Handwritten-Digit-Recognition
Handwritten Digit Recognition on MNIST dataset using tensorflow framework

Dense Neural Networks were used to build the model.

# Packages
1. tensorflow
2. numpy
3. matplotlib
4. pandas

# Architecture
1. Input features: shape = 28*28
2. Dense layer consisting of 128 neurons with relu activation function and a kernel regularizer L2 with weight 0.0001
3. Dropout function to drop 20 percent of the dataset
4. Dense layer consisting of 128 neurons with relu activation function and a kernel regularizer L2 with weight 0.0001 
2. Dense layer consisting of 10 neurons for output with softmax activation function

Optimizer - adam
Loss function - Sparse categorical cross entropy

# Performance
Train accuracy - 98.32%
Test accuracy  - 97.90%
