# Deep Learning Course - (1RT720)

This repository contains my implementations and reports for **Hand-in Assignment 1** and **Hand-in Assignment 2** in the Deep Learning course (1RT720) at Uppsala University.

The project demonstrates the implementation of neural networks for handwritten digit classification on the **MNIST** dataset (60,000 training + 10,000 test images).

- **Assignment 1**: Implemented a fully connected neural network **from scratch using only NumPy**.
- **Assignment 2**: Built upon the first assignment using **PyTorch**, progressing to convolutional networks, Adam optimizer, residual connections, and regularization techniques.

## Overview

### Assignment 1: Neural Network from Scratch (NumPy)
- Implemented a **fully connected multi-layer neural network** using only **NumPy**.
- Key components:
  - He initialization
  - Forward & backward propagation
  - ReLU & Sigmoid activations + derivatives
  - Softmax + Cross-Entropy loss
  - Mini-batch gradient descent
- Evaluated:
  - Linear model (no hidden layers) → **91.36%** test accuracy
  - Multi-layer networks ([784, 128, 64, 10]) with ReLU (**96.84%**) and Sigmoid (**98.07%**)
- Visualized learned weight templates and training curves.

### Assignment 2: Advanced Architectures in PyTorch
- Re-implemented the fully-connected network in **PyTorch** (faster training on GPU).
- Built a **Convolutional Neural Network** (CNN) achieving **98.86%** test accuracy.
- Explored:
  - **Adam optimizer** → **99.17%** test accuracy
  - **Residual connections** for deeper networks
  - **Batch Normalization** and **Dropout** for regularization (best model: **99.20%** with BN)
- Analyzed confusion matrices and misclassified examples.

### Technologies Used
- **Python 3**
- **NumPy** (Assignment 1 - pure implementation)
- **PyTorch** + CUDA (Assignment 2)
- Matplotlib (visualizations)
- Google Colab (training with T4 GPU)
