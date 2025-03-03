# Brain Tumor Classification with CNNs

This repository contains an implementation of Convolutional Neural Networks (CNNs) for detecting brain tumors using medical images. The models are trained on a dataset of grayscale MRI scans and classified into two categories: **Tumor** and **No Tumor**.

## Features
- **Multiple CNN architectures**: Implemented and compared six different CNN models with varying complexity.
- **Data preprocessing**: Includes normalization, augmentation, and dataset splitting.
- **Model optimization**: Uses techniques like learning rate scheduling, early stopping, and checkpoint saving.
- **Visualization tools**: Accuracy and loss graphs for model evaluation.

## Installation
To run the project, ensure you have the following dependencies installed:

```bash
pip install tensorflow numpy pandas matplotlib scikit-learn
