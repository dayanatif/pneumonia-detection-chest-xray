# Pneumonia Detection from Chest X-Rays using Deep Learning

## 📌 Project Overview
This project implements a **deep learning model** to classify chest X-ray images into **Normal** or **Pneumonia** categories.  
It uses **transfer learning (ResNet18)**, trained on the popular [Chest X-Ray Pneumonia dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).  
The model is trained with data augmentation, early stopping, and a learning rate scheduler to improve generalization.

---

## 📂 Dataset
The dataset consists of chest X-ray images classified into:
- **Normal**
- **Pneumonia (Bacterial / Viral)**

You can download it from Kaggle:
```bash
kaggle datasets download -d paultimothymooney/chest-xray-pneumonia
