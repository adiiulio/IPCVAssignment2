# Product Classification in Grocery Stores

This project focuses on classifying grocery store products from natural images taken with a smartphone. The goal is to recognize and categorize items across 43 distinct product classes.

## Approach Overview
The project is divided into two main phases:

### Custom CNN Implementation:
A convolutional neural network was designed from scratch using PyTorch modules to classify product images. Various architecture choices, such as batch normalization, dropout, and global average pooling, were explored through ablation studies.

### Transfer Learning:
A pretrained ResNet-18 model (ImageNet weights) was fine-tuned on the dataset. Multiple learning rate configurations and layer freezing strategies were tested to optimize performance, achieving high accuracy on the validation set.



## Dependencies

- Python 3.8+
- PyTorch
- TorchVision
- NumPy
- Matplotlib
