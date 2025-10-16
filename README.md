# Transfer Learning for Pneumonia Detection

### 🧠 Overview
This project classifies chest X-ray images into **Normal**, **Bacterial Pneumonia**, and **Viral Pneumonia** using **Transfer Learning**.  
The goal is to leverage pre-trained CNN models to improve feature extraction and classification performance.

### 📊 Dataset
- Source: [Kaggle Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- Classes: Normal, Bacterial Pneumonia, Viral Pneumonia
- Data preprocessing and augmentation applied to improve model generalization

### 💻 Method
- **Models:** ResNet152V2, InceptionV3 (pre-trained)
- **Techniques:** Transfer Learning, Image Preprocessing, Data Augmentation
- **Training:** Fine-tuned last layers, monitored validation performance for early stopping

### 🚀 Results
| Model       | Test Accuracy | Test F1-score |
|------------|---------------|---------------|
| ResNet152V2 | 88.3%        | 87.5%         |
| InceptionV3 | 81.4%        | 81.3%         |

> ResNet152V2 outperformed InceptionV3, showing more stable validation performance due to deeper and more complex architecture, effectively capturing image features.

