# 🏥 Medical Image Diagnosis System

A deep learning system that automatically detects diseases 
from medical images using CNN (ResNet-50) with Grad-CAM 
visual explanations.

## 🎯 What it does
- 🫁 Chest X-Ray → Detects Pneumonia
- 🧠 Brain MRI → Detects Tumors  
- 🩺 Skin Image → Detects Melanoma

## 📊 Results
| Metric | Score |
|--------|-------|
| Accuracy | 97% |
| AUC-ROC | 0.9724 |
| Pneumonia Recall | 95.4% |

## 🔥 Key Features
- ResNet-50 pretrained backbone
- Transfer Learning (ImageNet → Medical)
- Grad-CAM heatmaps for explainability
- Handles class imbalance
- Full evaluation pipeline

## 🛠️ Tech Stack
- PyTorch
- ResNet-50
- Grad-CAM
- OpenCV
- scikit-learn
- Google Colab (T4 GPU)

## 📁 Project Structure
```
medai-diagnosis/
├── medai_diagnosis.ipynb   # Main notebook
├── requirements.txt         # Dependencies
└── README.md               # This file
```

## 🚀 How to Run
1. Open `medai_diagnosis.ipynb` in Google Colab
2. Upload chest_xray dataset to Google Drive
3. Run all cells in order

## 📈 Grad-CAM Results
The model highlights exactly which lung regions 
contain pneumonia — making it explainable and 
clinically trustworthy.