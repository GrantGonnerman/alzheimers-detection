# Alzheimer’s Disease Detection

**Deep Learning Image Classification Project** | Detecting Alzheimer’s disease from MRI brain scans to support early medical diagnosis.

## 📋 Project Overview
This project develops a Convolutional Neural Network (CNN) to classify brain MRI images into different stages of Alzheimer’s disease (or healthy). The goal is to build an accurate, automated tool that can assist doctors in early detection and intervention.

## 🎯 Business / Real-World Impact
Early detection of Alzheimer’s can significantly improve patient outcomes through timely treatment and care planning. This project demonstrates the application of deep learning in medical imaging for neurodegenerative disease classification.

## 🗂️ Dataset
- **Source**: Alzheimer’s MRI dataset (loaded from AWS S3)
- **Target**: Multi-class classification (e.g., Non-Demented, Very Mild Demented, Mild Demented, Moderate Demented)
- **Features**: Brain MRI scans (grayscale or RGB images)

## 🔧 Key Techniques & Models
- **Data Preprocessing**: Image loading, resizing, normalization, and data augmentation
- **Exploratory Data Analysis**: Class distribution analysis and sample image visualization
- **Modeling**:
  - Custom Convolutional Neural Networks (CNNs) built with TensorFlow/Keras
  - Multiple convolutional + pooling layers
  - Dropout and regularization to prevent overfitting
  - Hyperparameter tuning
- **Evaluation**: Accuracy, Precision, Recall, F1-score, Confusion Matrix, and Learning Curves

## 📊 Results
- Achieved strong classification performance on the MRI dataset
- Successfully distinguished between different stages of cognitive decline
- Demonstrated the effectiveness of CNNs for medical image analysis

## 📄 Reports
- [Full Project Report (PDF)](Alzheimer%E2%80%99s%20Detection/Reports/Alzheimer%E2%80%99s%20Detection%20Report.pdf)
- [Presentation Slides (PDF)](Alzheimer%E2%80%99s%20Detection/Reports/Alzheimer%E2%80%99s%20Detection%20Slides.pdf)

## 🛠️ Technologies Used
**Python** • **TensorFlow / Keras** • **CNNs** • **Data Augmentation** • **Matplotlib** • **Seaborn** • **pandas**
