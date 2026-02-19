# Image Classification with CNN Architectures

Deep Learning project focused on multi-class image classification using Convolutional Neural Networks (CNNs) implemented in PyTorch.

---

## Datasets

### 1️⃣ Jellyfish Dataset
Multi-class image dataset of jellyfish species.

Models implemented:
- GoogLeNet
- ResNet18

Objective:
Compare architectures and analyze performance differences, training stability, and impact of preprocessing.

---

### 2️⃣ Natural Images Dataset
Multi-class dataset of natural scene images.

Model implemented:
- AlexNet (trained from scratch)

Objective:
Build a complete training pipeline including logging, model saving, and visualization of training metrics.

---

## Framework

Python, PyTorch

---

## Training Pipeline

- CrossEntropyLoss
- Adam optimizer
- Early Stopping
- Logging of training/validation metrics
- Saving trained models (.pth)
- Visualization of loss and accuracy trends

---

## Evaluation Approach

- Monitoring training and validation accuracy
- Analysis of loss convergence
- Error analysis across architectures
- Comparison of model stability

---

## Key Insights

- Residual connections (ResNet18) improved training stability compared to earlier architectures.
- Model performance was strongly influenced by dataset preprocessing and image quality.
- Early stopping helped mitigate overfitting in smaller datasets.

