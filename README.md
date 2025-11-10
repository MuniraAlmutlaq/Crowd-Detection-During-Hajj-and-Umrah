# 🕋 Crowd Detection During Hajj & Umrah  
Using Computer Vision to Enhance Safety and Crowd Management

---

## 📌 Project Overview  
Each year, millions of pilgrims visit Makkah for **Hajj and Umrah**, creating extremely dense crowds. Managing these crowds efficiently is crucial for ensuring safety and avoiding dangerous incidents like overcrowding or bottlenecks.

This project uses **Computer Vision and Crowd Detection Models** to:
- Detect and count people in crowded areas
- Estimate crowd density in real time
- Support decision-making for crowd control and safety operations

The project uses **pretrained object detection models** to recognize people in images, particularly aerial or surveillance views from the holy sites.

---

## 🛠️ Workflow Summary

### 1. ✅ Data Collection
- Images representing **different crowd density scenarios** (crowded, not crowded)
- Dataset includes images taken from **CCTV or aerial angles** to mimic real monitoring conditions

### 2. 🧠 Model Used — YOLO (You Only Look Once)
- A state-of-the-art deep learning model for real-time object detection
- Capable of detecting people even in **dense and overlapping** scenarios

### 3. 📊 Output
- Bounding boxes on detected people
- Detection count (number of individuals)
- Crowd density classification (crowded / not-crowded)
