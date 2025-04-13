# Facial Expression Recognition (CNN-LSTM)

A deep learning model to classify 7 emotional states from facial images in the MMA dataset, using a hybrid CNN-LSTM architecture.

## 🚀 Features
- Hybrid **CNN-LSTM** architecture for spatiotemporal feature learning
- Processes **48x48x3 RGB images** with normalization
- Tracks multiple metrics: **Accuracy, Precision, Recall, AUC**
- Includes **Batch Normalization** and **Dropout** for regularization
- Generates training progress plots (accuracy/loss curves)

## 📁 Dataset Structure
'''
MMAFEDB/
├── train/
│ ├── anger/ # 4,500 images per class
│ ├── fear/ # ...
│ └── ... # 7 total classes
└── test/
├── anger/ # 700 images per class
└── ... # 7 total classes
'''
**Total:** 31,500 training + 4,900 testing images
