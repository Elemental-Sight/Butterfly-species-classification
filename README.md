# 🦋 Butterfly Species Classification

Multi-class butterfly species classification using deep learning. Built with PyTorch and EfficientNet-B7, achieving 93% validation accuracy across 75 species with class imbalance handling and data augmentation.

---

## Overview

This project develops a deep learning-based computer vision system to classify butterfly images into 75 species using over 5,000 labeled images.

The dataset exhibits significant class imbalance, which introduces challenges for model generalization. To address this, class-weighted loss and extensive data augmentation were applied. Multiple convolutional neural network architectures were evaluated through transfer learning, with EfficientNet-B7 achieving the best performance.

---

## Dataset

- 75 butterfly species  
- 5,000+ labeled images  
- Highly imbalanced class distribution  

The dataset is not included in this repository due to size and licensing constraints.

---

## Methodology

### Data Processing
- Image resizing and normalization
- Data augmentation:
  - Random horizontal flip
  - Random crop
  - Color jitter

### Model Training
- Transfer learning from pretrained CNN models
- Class-weighted Cross Entropy Loss to mitigate class imbalance
- Architecture comparison:
  - ResNet50
  - MobileNetV2
  - EfficientNet-B7

### Optimization
- Adam optimizer
- Learning rate scheduling
- Early stopping

---

## Results

| Model | Validation Accuracy |
|------|---------------------|
| ResNet50 | **89%** |
| MobileNetV2 | **85%** |
| EfficientNet-B7 | **93%** |

EfficientNet-B7 demonstrated superior performance and was selected as the final model.

---

## Technologies

- Python  
- PyTorch  
- EfficientNet-B7  
- OpenCV  
- NumPy  
- Matplotlib  

---


