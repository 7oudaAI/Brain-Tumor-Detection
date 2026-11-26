# Brain Tumor Detection

## Project Overview
A Deep Learning project for classifying brain tumors from MRI images using Convolutional Neural Networks (CNN) and Transfer Learning with ResNet50.

## Dataset
- **Source:** [Brain Tumor MRI Dataset – Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- Images are downloaded directly from Kaggle using `kagglehub`.
- Images are resized to 224 × 224 pixels.

## Technologies Used
- Python
- TensorFlow & Keras
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-learn

## Models Implemented
- **Custom CNN:** Built and trained a Convolutional Neural Network for image classification.
- **ResNet50:** Applied Transfer Learning using ImageNet pretrained weights.

## Project Workflow
- Dataset Loading and Preparation
- Training, Validation, and Testing Splits
- MRI Image Visualization
- CNN Model Building and Training
- ResNet50 Transfer Learning
- Model Evaluation and Comparison
- Grad-CAM Visualization for Model Interpretability

## Evaluation
Models were evaluated using:
- Accuracy and Loss
- Precision, Recall, and F1-Score
- Confusion Matrix
- CNN vs. ResNet50 Performance Comparison

## Explainability
Grad-CAM was used with ResNet50 to generate heatmaps and visualize image regions that influenced the model's predictions.

## Key Takeaway
This project demonstrates the application of Deep Learning and Transfer Learning to medical image classification, along with model evaluation and visual explainability using Grad-CAM.
