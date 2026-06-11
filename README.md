# MNIST Handwritten Digit Classification using PyTorch

## Overview

Built a feedforward neural network from scratch using PyTorch to classify handwritten digits from the MNIST dataset.

## Architecture

784 → 128 → ReLU → 64 → ReLU → 10

## Training Configuration

- Loss Function: CrossEntropyLoss
- Optimizer: Adam (lr=0.001)
- Epochs: 5
- Batch Size: 64

## Results

- Test Accuracy: 96.93%
- Total Parameters: 109,386

Training Loss:

- Epoch 1: 0.3491
- Epoch 2: 0.1519
- Epoch 3: 0.1046
- Epoch 4: 0.0777
- Epoch 5: 0.0591

## Technologies

- Python
- PyTorch
- Torchvision
