# 🩺 AI-Powered Pneumonia Detection and Explainable Chest X-ray Analysis Using EfficientNetB0

## 📌 Overview
This project uses Transfer Learning with EfficientNetB0 to classify chest X-ray images into **Normal** and **Pneumonia** categories. It also incorporates Explainable AI using Grad-CAM to visualize the regions of the X-ray that most influenced the model's predictions.

## 🚀 Features
- Deep Learning-based Chest X-ray Classification
- Transfer Learning with EfficientNetB0
- Image Preprocessing & Data Augmentation
- Model Evaluation (Accuracy, Precision, Recall, F1-Score)
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve
- Grad-CAM Heatmap Visualization
- Prediction Confidence Analysis
- Misclassified Image Analysis

## 🛠️ Technologies
- Python
- TensorFlow / Keras
- EfficientNetB0
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 📊 Dataset
Chest X-ray Images (Normal & Pneumonia)

Dataset Structure:
```
dataset/
├── train/
├── val/
└── test/
```

## 📈 Results
- High classification accuracy using EfficientNetB0
- Explainable AI visualization with Grad-CAM
- Comprehensive performance evaluation using multiple metrics

## 📂 Repository Structure
```
Pneumonia_Detection/
│── dataset/
│── model/
│── outputs/
│── train.py
│── evaluate.py
│── predict.py
│── gradcam.py
│── requirements.txt
└── README.md
```

## ⚠️ Disclaimer
This project is developed for educational and research purposes only. It is not intended for clinical diagnosis or medical decision-making.
