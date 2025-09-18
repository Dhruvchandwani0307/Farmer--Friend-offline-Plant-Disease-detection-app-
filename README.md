# Farmer--Friend-offline-Plant-Disease-detection-app-
A mobile-based plant disease detection system using CNNs and TensorFlow Lite, deployed in an Android app (Kotlin) for offline leaf disease identification.
# Plant Disease Detection using CNN and Android Application

## Overview
This project implements a mobile-based *plant disease detection system* that leverages *Convolutional Neural Networks (CNNs)* integrated with *TensorFlow Lite* for lightweight deployment on Android devices. The Android application is developed using *Kotlin* and enables real-time plant leaf disease identification directly from the device’s camera.  

The application works *offline* and is designed to assist farmers in early disease detection, even in regions with limited internet connectivity.  

Currently, the app identifies plant diseases through the trained model. (Treatment recommendation functionality is under development.)

---

## Features
- Real-time plant leaf disease detection using a CNN model.  
- Mobile application built with *Kotlin* for Android.  
- Optimized with *TensorFlow Lite* for on-device inference.  
- Works *offline*, ensuring usability in rural areas.  
- Lightweight and suitable for low-end smartphones.  

---

## System Architecture
1. *Data Collection & Model Training*  
   - Dataset sourced from PlantVillage and other repositories.  
   - CNN model trained in Python using TensorFlow/Keras.  
   - Model converted to TensorFlow Lite for mobile deployment.  

2. *Mobile Application (Frontend)*  
   - Developed in Kotlin for Android.  
   - Camera integration to capture leaf images.  
   - Disease classification via embedded TensorFlow Lite model.  

3. *Backend (Offline Database)*  
   - JSON-based local database storing disease classes.  
   - Currently maps detected diseases (future scope: add treatment recommendations).  

---

## Tech Stack
- *Languages:* Python, Kotlin  
- *Frameworks/Libraries:* TensorFlow, TensorFlow Lite, Keras  
- *Tools:* Android Studio, Jupyter Notebook  
- *Platform:* Android (minimum SDK 21+)  

---

## Installation & Usage
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/plant-disease-detection.git
   cd plant-disease-detection
