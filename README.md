# PoseGuard ML Stress Detector
## Real-time Pose + 90% ML Stress Detection

---

## 📋 Overview
Real-time stress detection using **MediaPipe pose analysis** + **90% accurate RandomForest ML model**. Dual prediction system from webcam feeds.

**Key Features:**
- Live webcam pose stress detection
- 90%+ accuracy ML model 
- Photo capture for datasets
- Production-ready pipeline

---

## 📦 Files

---

## 📊 Dataset
**Source:** Kaggle Human Stress Detection (2,338 samples)  
**Features:** 21 physiological/lifestyle indicators  
**Target:** Stress (0=No, 1=Yes)

---

## 🎯 Performance

---

## 🔧 Setup
```bash
pip install mediapipe opencv-python scikit-learn pandas numpy joblib

# Download MediaPipe model
curl -o pose_landmarker.task https://storage.googleapis.com/mediapipe-models/pose_landmarker/pose_landmarker/float16/1/pose_landmarker.task


