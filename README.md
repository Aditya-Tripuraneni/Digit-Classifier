# Digit-Classifier
# SVM and Logistic Regression with PyTorch

## Overview
This project implements **Support Vector Machines (SVM)** and **Logistic Regression** using the **PyTorch** framework to solve a multi-class image classification problem on the **MNIST dataset**. The project focuses on exploring the performance differences between the two models using different loss functions and optimization techniques.

In particular, we experiment with:
- **Logistic Regression** optimized using **Cross Entropy Loss**.
- **Support Vector Machines (SVM)** optimized using **Hinge Loss**.

Additionally, both models are trained using **Gradient Descent Optimizer** to minimize the respective loss functions, allowing for direct comparison of the training efficiency and performance.

---

## Dataset
The project uses the **MNIST dataset**, which contains:
- **60,000 training images** and **10,000 test images** (28x28 pixels).
- The dataset consists of grayscale images of handwritten digits (0-9).

Only a subset of the dataset is used in this project for training and evaluation to focus on model comparison.

---

## Key Features
- Implementation of **Logistic Regression** and **Support Vector Machines (SVM)** from scratch using PyTorch.
- Experimentation with two distinct loss functions:
  - **Hinge Loss** for SVM.
  - **Cross Entropy Loss** for Logistic Regression.
- Both models are optimized using the **Gradient Descent Optimizer**.
- Comparison of model performance on the MNIST dataset, including accuracy and loss metrics.

## Acknowledgments
- Dataset: [MNIST](http://yann.lecun.com/exdb/mnist/)
- Framework: [PyTorch](https://pytorch.org/)
