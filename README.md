# Digit-Recognition-using-CNN
# CNN-Image_Classification

This repository contains two deep learning projects that use Convolutional Neural Networks (CNNs) to classify images — one for handwritten digit recognition (MNIST) and another for binary classification (Cats vs Dogs). Both models are built and trained from scratch using PyTorch, with the ability to perform real-time predictions on custom images using OpenCV and PIL.
# Introduction
This project focuses on implementing CNN-based image classification models to demonstrate the capabilities of deep learning in computer vision.

Handwritten Digit Classification: Multi-class classification of digits 0–9 using the MNIST dataset.

Dog vs Cat Classification: Binary classification to distinguish between cats and dogs using the Kaggle PetImages dataset.

The models provide an end-to-end workflow from data preprocessing to real-time prediction, making them suitable for learning and deployment purposes.
# Data Sources
MNIST Dataset: 60,000 training and 10,000 testing grayscale images of handwritten digits (28×28 pixels).

Kaggle PetImages Dataset: RGB images of cats and dogs, preprocessed for size consistency and image quality.

Data preprocessing steps included resizing, normalization, handling corrupted images, and converting images to grayscale where necessary.

# Project Overview
Built CNN models from scratch using PyTorch for both multi-class and binary classification.

Applied data preprocessing including resizing, normalization, and augmentation techniques.

Evaluated model performance using accuracy, confusion matrix, precision, recall, and F1-score.

Implemented real-time predictions on custom images using OpenCV and PIL.

Addressed challenges such as corrupted images, class imbalance, noisy samples, and overfitting.

# Results and Insights

Handwritten Digit Classification (MNIST): Achieved 99.15% test accuracy.

Dog vs Cat Classification: Achieved 80.04% test accuracy.

Implemented dropout, batch normalization, and early stopping to prevent overfitting.

Automated data cleaning with OpenCV removed corrupted or empty images from the dataset.

Real-time image prediction feature allows testing on external images for both projects.

# Conclusion

These projects demonstrate the power of CNNs in image classification tasks. Despite challenges such as dataset noise and class imbalance, the models achieved strong accuracy and reliability. The workflow from data preprocessing to real-time prediction shows practical applicability in computer vision problems.

# Future Work

Explore more complex CNN architectures and experiment with transfer learning for improved performance.

Conduct fine-grained analysis of misclassified samples to improve model accuracy.

Integrate models into a web or mobile application for real-world deployment.

Extend the pipeline to classify multiple image categories beyond binary or 10-class classification.
