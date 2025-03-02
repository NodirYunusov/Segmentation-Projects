# Insect Segmentation using Deep Learning

## Overview
This project focuses on **semantic segmentation of insects** using deep learning. The model has been trained to accurately segment insects from various backgrounds, achieving high performance on both training and validation datasets.

## Dataset
The dataset consists of images containing insects with corresponding ground truth masks. It includes diverse insect species in different environmental conditions to improve generalization.

## Model Architecture
- **Backbone:** DeepLabV3+
- **Framework:**  PyTorch
- **Loss Function:**  Cross-Entropy
- **Optimizer:** Adam

## Performance Metrics
| Metric              | Training  | Validation |
|---------------------|----------|------------|
| IoU (Intersection over Union) | 0.90 | 0.85 |
| Pixel Accuracy | 0.98 | 0.96 |
| Loss | 0.028 | 0.084 |




## Future Improvements
- Enhance dataset diversity for better generalization
- Experiment with different architectures (e.g., Transformer-based models)
- Implement real-time segmentation for deployment
