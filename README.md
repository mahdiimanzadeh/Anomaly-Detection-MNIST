# MNIST Anomaly Detection Project

This project focuses on detecting anomalies in the MNIST dataset using unsupervised learning techniques. The dataset consists of images of the digit "0" along with some anomalous samples from other digits. The goal is to identify these anomalies using three different methods: PCA, GMM, and Autoencoder.

## Project Overview

### Introduction
The dataset provided contains approximately 7000 samples of the digit "0" and 60 anomalous samples from other digits. The task is to develop an unsupervised learning model to detect these anomalies.

### Methods Used
1. **Principal Component Analysis (PCA)**
2. **Gaussian Mixture Model (GMM)**
3. **Autoencoder**

### Instructions
1. **Data Preparation**: The dataset is loaded and preprocessed. Normal samples are separated from anomalous samples.
2. **Model Implementation**:
   - **PCA**: Dimensionality reduction and reconstruction error calculation.
   - **GMM**: Gaussian Mixture Model for likelihood-based anomaly detection.
   - **Autoencoder**: Neural network for reconstruction-based anomaly detection.
3. **Evaluation**: The models are evaluated based on their ability to detect the provided anomalous samples.

### Results Analysis
- **Visualization**: Reconstruction error distribution and log-likelihood scores are visualized.
- **Performance Metrics**: Accuracy and detection rates are calculated for each method.
