# Skin Disease Classification

This project compares classical machine learning and deep learning approaches for multi-class skin disease classification using medical images.

## Overview
- 9 skin-condition classes
- 695 training images, 181 validation images
- Approaches compared:
  - PCA + SVM
  - ResNet18 transfer learning

## Tech Stack
Python, PyTorch, torchvision, scikit-learn, NumPy, matplotlib

## Methods
- Cleaned and validated image dataset
- Applied resizing and normalization
- Built PCA + SVM baseline
- Trained ResNet18 CNN with transfer learning
- Evaluated using accuracy, macro-F1, and confusion matrices

## Results
- PCA + SVM: 0.63 accuracy, 0.62 macro-F1
- ResNet18 CNN: 0.79 accuracy, 0.78 macro-F1

## Key Takeaway
The CNN significantly outperformed the PCA + SVM baseline, showing that learned convolutional features were more effective than handcrafted dimensionality-reduced features for this image classification task.

## How to Run
1. Clone the repo
2. Install dependencies with `pip install -r requirements.txt`
3. Open the notebook and run all cells
