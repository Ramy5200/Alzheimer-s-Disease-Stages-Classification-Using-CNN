# Alzheimer-s-Disease-Stages-Classification-Using-CNN
This project focuses on using deep learning techniques, specifically Convolutional Neural Networks (CNNs), for classifying stages of Alzheimer's Disease (AD) from MRI images. The model employs DenseNet-169, a CNN architecture, to classify four AD stages
# Overview
This project focuses on using deep learning techniques, specifically Convolutional Neural Networks (CNNs), for classifying stages of Alzheimer's Disease (AD) from MRI images. The model employs DenseNet-169, a CNN architecture, to classify four AD stages:

Non-Dementia
Very Mild Dementia
Mild Dementia
Moderate Dementia
The goal is to automate and improve the accuracy of AD diagnosis, assisting in early detection.

# Dataset
Images: ~6400 MRI images
Classes:
Mild Demented
Very Mild Demented
Non-Demented
Moderate Demented
# Approach
Model: DenseNet-169 (a type of CNN)
Pre-processing: Data augmentation (e.g., rescaling, rotating, zooming, flipping) to expand the dataset.
Training: 77% of the data for training, 23% for testing.
Evaluation: Model performance assessed based on accuracy, precision, and loss metrics.
# Model Architecture
Input Layer for image size.
Convolutional Layers for feature extraction.
Batch Normalization & ReLU to stabilize learning.
Max Pooling to reduce dimensionality.
Fully Connected Layers for classification.
SoftMax Layer for probability output.
# Results
Training Accuracy: 91%
Testing Accuracy: 82%
DenseNet-169 outperformed ResNet-50 in both training and testing.
Example Predictions:
Non-Demented: 81.34%
Mild Demented: 67.83%
Moderate Demented: 95.5%
Very Mild Demented: 64.46%
# Conclusion
DenseNet-169 demonstrates strong performance for classifying AD stages from MRI images.
The model’s high accuracy shows promise for clinical applications in early AD detection.
