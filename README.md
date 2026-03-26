# 🚦 Smart Traffic Signal System for Ambulance Priority

## 📌 Overview

This project proposes an AI + IoT based smart traffic management system that detects ambulances and automatically creates a **green corridor**.

## 🎯 Objective

To reduce ambulance delay at intersections and improve emergency response time.

---

## 🧠 Technologies Used

* Python
* YOLOv5 (Computer Vision)
* MFCC + MLP (Audio Detection)
* OpenCV
* TensorFlow / Keras
* NodeMCU (ESP8266)
* IoT + Relays

---

## ⚙️ System Architecture

1. Camera + Microphone capture data
2. YOLOv5 detects ambulance
3. MFCC + MLP detects siren
4. Fusion logic confirms detection
5. NodeMCU changes signal to GREEN

---

## 📂 Project Structure

```
src/        → AI models & scripts  
iot/        → NodeMCU code  
docs/       → Project report  
dataset/    → Training data  
```

---

## 🚀 How to Run

### 1. Install dependencies

```
pip install -r requirements.txt
```

### 2. Run main script

```
python fusion_script.py
```

---

## 🔌 Hardware Required

* Camera
* Microphone
* NodeMCU (ESP8266)
* Relay module
* LEDs (traffic simulation)

---

## 📊 Features

✅ Real-time ambulance detection
✅ Multi-modal AI (Vision + Audio)
✅ Low-cost IoT implementation
✅ High accuracy with reduced false positives

---

## 🔮 Future Scope

* Multi-intersection green corridor
* GPS-based prediction
* Smart city integration

---

## 👨‍💻 Authors

* Gokul M
* Sriram S
* Gokularamanan K

---

## 📄 License

MIT License
