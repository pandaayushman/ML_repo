# 🎭 Real-Time Facial Emotion Detection using Deep Learning

## 📌 Overview

This project implements a **Real-Time Facial Emotion Detection System** using **Deep Learning and Computer Vision**. The system analyzes facial expressions captured from a live camera feed and classifies them into different human emotions such as **Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise**.

The model is trained using the **FER2013 dataset**, which contains thousands of labeled facial expression images. A **Convolutional Neural Network (CNN)** is used to learn facial features and accurately predict the emotional state of a person in real time.

This project demonstrates how **Artificial Intelligence can interpret human emotions** and can be applied in various domains such as **human-computer interaction, mental health monitoring, security systems, and smart user interfaces**.

---

## 🚀 Features

* 🎥 **Real-time emotion detection** using webcam
* 🧠 **Deep Learning model (CNN)** trained on FER2013 dataset
* 📊 **Prediction confidence display**
* 😀 Detects **7 human emotions**
* ⚡ **Fast and lightweight inference**
* 📈 Visualization of model performance using **accuracy and loss curves**
* 📊 **Confusion Matrix evaluation**

---

## 🧠 Emotions Detected

The model classifies facial expressions into the following categories:

* 😡 Angry
* 🤢 Disgust
* 😨 Fear
* 😄 Happy
* 😐 Neutral
* 😢 Sad
* 😲 Surprise

---

## 🗂 Dataset

The project uses the **FER2013 (Facial Expression Recognition 2013)** dataset.

Dataset characteristics:

* 35,000+ grayscale facial images
* Image size: **48 × 48 pixels**
* 7 emotion classes
* Training and testing dataset split

---

## 🏗 Model Architecture

The model is built using **TensorFlow/Keras** and consists of:

* Convolutional Layers (CNN)
* Batch Normalization
* Max Pooling Layers
* Dense Layers
* Dropout Regularization
* Softmax Output Layer

This architecture allows the network to **extract facial features effectively and reduce overfitting**.

---

## ⚙️ Technologies Used

* Python 🐍
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

---

## 📊 Model Performance

The trained CNN model is evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

These metrics help analyze the **classification performance across different emotions**.

---

## 📷 Real-Time Emotion Detection

The trained model is integrated with **OpenCV's face detection** to capture live video from the camera. The system detects faces, processes them, and predicts emotions in real time.

---

## 💡 Applications

Facial Emotion Detection can be used in:

* Human–Computer Interaction
* Mental Health Monitoring
* Smart Surveillance Systems
* Customer Feedback Analysis
* Online Education Engagement Analysis
* Gaming and Entertainment Systems

---

## 🔮 Future Improvements

Possible improvements to the project include:

* Using **Transfer Learning (ResNet / MobileNet)** for higher accuracy
* Deploying the model as a **web application**
* Real-time **emotion analytics dashboard**
* Supporting **multiple face tracking**

---

## 👨‍💻 Author

Developed as part of a **Machine Learning / AI project** demonstrating real-time facial emotion recognition using deep learning techniques.

