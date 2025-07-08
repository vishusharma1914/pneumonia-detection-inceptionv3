# Pneumonia Detection using InceptionV3

This project uses transfer learning with the InceptionV3 model to detect pneumonia in chest X-ray images using the PneumoniaMNIST dataset.

## Steps
1. Preprocess images (resize to 150x150, convert to RGB)
2. Fine-tune InceptionV3 model
3. Handle class imbalance using class weights
4. Prevent overfitting with dropout and data augmentation
5. Evaluate using Accuracy, F1-score, and AUC

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook pneumonia_detection.ipynb
```

---
Submitted by: **Vishu Sharma**
Date: 08 July 2025
