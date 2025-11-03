# 🌊 **Underwater-Plastic-Pollution-Detection-AI-ML**

This project uses deep learning to detect plastic waste in underwater images.  
A **CNN model** classifies images as **“Plastic Detected”** or **“Clean Ocean.”**  
It supports **sustainability and ocean conservation (SDG 14 – Life Below Water).**

---

## 📘 **Overview**

This project uses **Deep Learning** to automatically detect plastic waste in underwater images.  
A **Convolutional Neural Network (CNN)** model is trained to classify each image as *Plastic Detected* or *Clean Ocean*.  
The goal is to help environmental researchers and organizations monitor marine pollution efficiently, supporting **Sustainable Development Goal (SDG) 14 – Life Below Water**.

---

## 🎯 **Objective**

To develop an **AI-based image classification model** that detects ocean plastic pollution and promotes **environmental sustainability** by assisting in **real-time monitoring of marine waste**.

---

## 🌱 **Problem Statement**

Plastic pollution is a major threat to aquatic life.  
Manual identification of underwater plastic waste is time-consuming and expensive.  
This project proposes an **automated image classification model** that identifies whether an underwater image contains plastic waste, helping track and reduce pollution effectively.

---

## 📂 **Dataset**

**Dataset Source:** [Kaggle – Underwater Plastic Pollution Detection Dataset](https://www.kaggle.com/)

---

## 📁 **Dataset Structure**

dataset/
 ├── train/
 
 │     ├── plastic/
 
 │     └── non_plastic/

 
 └── test/
 
       ├── plastic/
       
       └── non_plastic/

## ⚙️ **Technologies Used**

| Category         | Tools / Libraries  |
| ---------------- | ------------------ |
| Language         | Python 3.9+        |
| Framework        | TensorFlow / Keras |
| Image Processing | OpenCV             |
| Data Handling    | NumPy, Pandas      |
| Visualization    | Matplotlib         |
| Evaluation       | Scikit-learn       |

## 🧠 **Methodology**

1. Data Collection – Download and organize the dataset from Kaggle.
2. Data Preprocessing – Resize all images to 128×128, normalize pixel values, and perform augmentation (rotation, flip, zoom).
3. Model Design – Build a Convolutional Neural Network (CNN) with three convolutional layers and dropout regularization.
4. Training – Train the model for 15 epochs using the Adam optimizer and binary cross-entropy loss.
5. Evaluation – Measure accuracy, visualize training curves, and test on unseen data.
6.Prediction – Test the model on any underwater image to classify it as Plastic Detected or Clean Ocean.

## 📊 **Results**

Training Accuracy: ~90–95%

Validation Accuracy: ~85–90%

Output Classes:

    🟢 Clean Ocean
    
    🔴 Plastic Detected

## 🌎 **Sustainability Impact**

This AI system promotes environmental protection by enabling automated plastic pollution monitoring in oceans and underwater ecosystems.
It helps researchers and NGOs reduce manual effort, conserve resources, and strengthen actions toward SDG 14 – Life Below Water.

## 🧾 **License**

This project is released under the MIT License – free for educational and research use.
