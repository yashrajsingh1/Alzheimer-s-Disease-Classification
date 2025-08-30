Alzheimer’s Disease Classification
Overview

This project focuses on the classification of Alzheimer’s Disease using deep learning techniques. The goal is to develop a model that can analyze MRI brain images and accurately classify the stage of Alzheimer’s disease. Early detection is crucial in slowing disease progression and improving patient care.

Problem Statement

Alzheimer’s disease is a progressive neurological disorder that leads to memory loss and cognitive decline. Detecting it at early stages is challenging but essential for timely intervention. Traditional diagnostic methods are time-consuming and prone to human error.
This project applies Convolutional Neural Networks (CNNs) to automatically classify MRI scans into different stages of Alzheimer’s Disease.

 Dataset

Source: Kaggle – Alzheimer's Synthesized dataset
https://www.kaggle.com/datasets/masud1901/alzheimers-synthesized-dataset

Data includes MRI brain images categorized into multiple classes:

Mild Demented

Moderate Demented

Non Demented

Very Mild Demented

Dataset preprocessing steps:

Image resizing and normalization

Train-test split

Data augmentation for improving model generalization

 Methodology
 Model Used

Convolutional Neural Network (CNN)

Layers: Convolution, MaxPooling, Dropout, Fully Connected

Activation: ReLU, Softmax

Optimizer: Adam

Loss Function: Categorical Crossentropy

 Training

Input: Preprocessed MRI images

Epochs: (fill from your notebook, e.g., 30, 50)

Batch Size: (fill from your notebook, e.g., 32, 64)

 Results & Evaluation

Training Accuracy: ~ (fill from notebook, e.g., 92%)

Validation Accuracy: ~ (fill from notebook, e.g., 89%)

Metrics used: Accuracy, Loss, Confusion Matrix
