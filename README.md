# S4-Assigment-Solution

Convolution Neural Network to detect the MNIST images.

# Requirements

1. Pytorch Libraries
2. Pytorch Database

# Project Overview

MNIST dataset dataset is available in pytorch torch.utils.data.dataset libraray. CNN model is created to preddict the write image in the dataset.

Features of the model are below:

1. 99.4% validation accuracy
2. Less than 20k Parameters - Parameters to train is less than 10k
3. Training was done for 20 epochs
4. No fully connected layer used for training
5. Global Average Pooling (GAP) used in the network instead of fully connected layer.
