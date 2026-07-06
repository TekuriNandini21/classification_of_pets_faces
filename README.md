# Pet Face Classification using MobileNetV2

This project classifies 37 different breeds of pet faces using the Oxford-IIIT Pet Dataset. Instead of training a CNN from scratch, it leverages Transfer Learning with a pre-trained **MobileNetV2** model.

## 🚀 Project Overview
- **Dataset:** Oxford-IIIT Pet Dataset (Processed directly on Kaggle)
- **Model Architecture:** MobileNetV2 (Base frozen) + GlobalAveragePooling2D + Dense Layers
- **Framework:** TensorFlow / Keras
- **Input Size:** 224x224 pixels

## 📊 Key Highlights
- Preprocessed and normalized image features entirely within the cloud.
- Reached high batch validation accuracy quickly by utilizing pre-trained ImageNet weights.
- Successfully saved the final trained architecture as a `.keras` file.
