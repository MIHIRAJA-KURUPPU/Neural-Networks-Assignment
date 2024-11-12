# Neural-Networks-Assignment

This repository contains the code and results for implementing various neural network architectures in PyTorch, as part of an assignment. The assignment includes building a single dense layer network with manual backpropagation, implementing LeNet-5 for MNIST classification, and using transfer learning with ResNet18 on the Hymenoptera dataset.

## Project Overview

### 1. Single-Layer Dense Network with CIFAR-10
   - **Network Modifications**: Added a hidden layer with 100 nodes and a sigmoid activation function.
   - **Loss Function**: Changed to cross-entropy loss.
   - **Training**: Ran the network for 10 epochs and reported training and test accuracies.
   - **Manual Backpropagation**: Calculated gradients manually for weight and bias updates.

### 2. LeNet-5 Network on MNIST Dataset
   - Implemented the LeNet-5 architecture using PyTorch, specifically designed for image classification on the MNIST dataset.
   - **Training and Testing**: Trained for 10 epochs and tracked both training and test accuracy.

### 3. Transfer Learning with ResNet18 for Hymenoptera Dataset
   - **Fine-Tuning**: Fine-tuned ResNet18 on the Hymenoptera dataset.
   - **Feature Extraction**: Used ResNet18 as a feature extractor by freezing pre-trained layers and adding a new classifier.
   - **Results**: Recorded classification accuracies for both fine-tuning and feature extraction methods.

## Project Structure

- `dense_network.py`: Implements the single dense layer network with a middle layer and cross-entropy loss for CIFAR-10.
- `lenet5_mnist.py`: Contains the code for the LeNet-5 network architecture on MNIST.
- `transfer_learning.py`: Fine-tuning and feature extraction methods with ResNet18 for the Hymenoptera dataset.

## Getting Started

### Prerequisites
- Python 3.x
- PyTorch
- torchvision
- matplotlib

Install dependencies with:
```bash
pip install torch torchvision matplotlib
