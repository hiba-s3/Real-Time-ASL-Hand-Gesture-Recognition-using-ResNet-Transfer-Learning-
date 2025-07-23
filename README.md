# 🤟 Real-Time ASL Hand Gesture Recognition using ResNet (Transfer Learning)

## 📌 Overview

This project implements a **real-time hand gesture recognition system** for **American Sign Language (ASL)** using a **ResNet-based transfer learning approach**. The model is trained to classify static hand gestures from the ASL alphabet and is deployed in real-time using a webcam interface.

---

## 🧠 Model Details

- **Architecture**: ResNet18
- **Technique**: Transfer Learning (fine-tuning on ASL dataset)
- **Framework**: PyTorch
- **Input**: Webcam frames or image files
- **Output**: Predicted ASL class label (A–Z, excluding dynamic signs)

---

## 🗂 Dataset

- **Source**: ASL Alphabet Dataset (Kaggle / Custom-preprocessed)
- **Classes**: A–Z (except `J` and `Z` which involve motion)
- **Images**: Grayscale or RGB images of hand gestures

> 🔒 The dataset used for training is publicly available and widely used in gesture recognition tasks.

---

## 🚀 Real-Time Inference

- Captures frames from your webcam
- Applies preprocessing and ResNet model prediction
- Displays the predicted ASL letter in real time

### 🖥️ To Run:

```bash
python real_time_predict.py
