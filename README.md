# 🗑️ Biodegradable-and-Non-Biodegradable-Waste-Classifier

## **Introduction**
India faces significant challenges in effective waste management, especially in differentiating between **biodegradable** and **non-biodegradable** materials. This project leverages **Artificial Intelligence**—specifically **supervised machine learning** and **deep learning using CNNs**—to automate the classification of waste, reducing the need for manual intervention and improving the efficiency of recycling systems.

---

## 💡 Automated Waste Classification Using Deep Learning  
**College:** Graphic Era Hill University, Dehradun  
**Student:** Abhishek Dabral  

---

## 📘 Project Overview

This AI-based waste detection system classifies waste from images using **deep learning**. Designed to assist in **smart waste segregation**, the system combines **image processing**, **CNN-based object detection**, and **real-time analysis**. Developed as part of a semester mini project, it demonstrates practical implementation of advanced machine learning techniques.

---

## 🛠️ Tools & Technologies
- **Language:** Python  
- **Libraries:** TensorFlow, OpenCV, NumPy, Matplotlib, OS  
- **Model:** Faster R-CNN via TensorFlow Object Detection API  
- **Approach:** Transfer Learning with real-time webcam/video input support  

---

## 🎯 Key Objectives
- Detect and classify waste into six types:
  - **Cardboard, Metal, Glass, Paper, Plastic, Trash**
- Real-time object detection from images or webcam/video input
- Reduce manual effort and improve classification accuracy

---

## ✅ Outcomes
- **91% accuracy** on test dataset (507 images)
- Real-time bounding box detection with class labels
- Capable of detecting **multiple objects per image**
- Average detection time: **~8 seconds per image**

---

## 📈 Challenges & Learnings
- Gained hands-on experience with CNNs, TensorFlow pipelines, and image preprocessing
- Faced dataset limitations: performance dropped with local, unclean waste samples
- Identified need for more **diverse and realistic training data**

---

## 🔭 Future Enhancements
- Enhance dataset with **real-world, cluttered, and dirty waste images**
- Add support for **bulkier and complex waste categories**
- Optimize model for **edge deployment (e.g., smart bins)**
- Experiment with **lightweight models** like SSD-MobileNet for mobile applications

---

## 📂 Repository Contents
- `/models/` – Trained model files and configurations  
- `/data/` – Labeled dataset for training and testing  
- `/notebooks/` – Training, testing, and inference notebooks  
- `/utils/` – Preprocessing utilities and helper scripts  
- `main.py` – Real-time webcam detection and inference script  

---

## 📌 Note
If you’re viewing this project through my **resume**, thank you for visiting!  
Feel free to check out the implementation, experiment with the model, or reach out for collaboration or questions.
