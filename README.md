# Jellyfish Image Classification

Deep Learning project for multi-class image classification using Convolutional Neural Networks.

## Objective

Compare different CNN architectures to evaluate their performance on a 12-class image dataset and analyze model behavior in terms of accuracy, loss trends, and overfitting.

## Models Implemented

- AlexNet (trained from scratch)
- GoogLeNet
- ResNet18

## Framework

Python, PyTorch

## Training Setup

- CrossEntropyLoss
- Adam optimizer
- Early Stopping to prevent overfitting
- Logging and saving of model checkpoints (.pth)
- Visualization of training loss and accuracy curves

## Evaluation

Model performance was assessed using:
- Training and validation accuracy
- Loss trends across epochs
- Error analysis and comparison between architectures

## Key Insight

Residual connections (ResNet18) improved training stability compared to earlier architectures, while preprocessing quality significantly impacted final performance.
