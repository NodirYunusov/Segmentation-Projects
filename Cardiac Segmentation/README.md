# Cardiac Disease Segmentation using Deep Learning

## Overview
This project focuses on **semantic segmentation of cardiac diseases** using deep learning. The model has been trained to accurately segment affected cardiac regions from medical images, achieving high performance on both training and validation datasets.

## Dataset
The dataset consists of medical images with corresponding ground truth masks. It includes various cardiac conditions to improve model generalization.

## Model Architecture
- **Backbone:**  DeepLabV3+
- **Framework:** PyTorch
- **Loss Function:** Cross-Entropy
- **Optimizer:**  Adam

## Performance Metrics
| Metric              | Training  | Validation |
|---------------------|----------|------------|
| IoU (Intersection over Union) | 0.90 | 0.99 |
| Pixel Accuracy | 0.98 | 0.96 |
| Loss | 0.019 | 0.034 |




