# DL_UU
Deep Learning Course (1RT720) - Hand-in Assignments
===================================================

This repository contains my complete submissions for **Hand-in Assignment 1** and **Hand-in Assignment 2** in the Deep Learning course (1RT720).

Author: Upali Bera  
Dates: February 2026 (Assignment 1) & March 2026 (Assignment 2)

### Overview

The project demonstrates the implementation of neural networks for handwritten digit classification on the **MNIST** dataset (60,000 training + 10,000 test images).

- **Assignment 1**: Implemented a fully connected neural network **from scratch using only NumPy**.
- **Assignment 2**: Built upon the first assignment using **PyTorch**, progressing to convolutional networks, Adam optimizer, residual connections, and regularization techniques.

Both assignments achieved strong performance, exceeding the course requirements.

### Key Features & Achievements

**Assignment 1 (NumPy from scratch)**
- He initialization, ReLU & Sigmoid activations + derivatives
- Forward & backward propagation with cross-entropy loss + softmax
- Mini-batch gradient descent
- Linear model (91.36% test accuracy)
- Multi-layer network [784-128-64-10]:
  - ReLU: **96.84%** test accuracy
  - Sigmoid: **98.07%** test accuracy
- Weight visualization for the linear model

**Assignment 2 (PyTorch)**
- Re-implementation of the fully-connected network
- **Convolutional Neural Network** (3 conv layers + max pooling): **98.86%** test accuracy
- Adam optimizer: **99.17%** test accuracy
- Residual connections (deeper networks with stable training)
- Regularization with Batch Normalization (**99.20%** best test accuracy) and Dropout
- Confusion matrix and misclassification analysis

All models were trained with mini-batch SGD/Adam, and learning curves were generated using the provided `training_curve_plot` utility.

### Technologies Used
- **Python 3**
- **NumPy** (Assignment 1 - pure implementation)
- **PyTorch** + CUDA (Assignment 2)
- Matplotlib (visualizations)
- Google Colab (training with T4 GPU)

### Repository Structure
