# Driver-Drowsiness-Detection-System
A computer vision-based system that detects driver drowsiness in real time by monitoring eye blink patterns and eye closure duration, and triggers an alert to improve road safety.
# 🚗 Driver Drowsiness Detection and Alert System

## 🌟 Project Overview

Driver fatigue is one of the major causes of road accidents worldwide. This project presents a real-time driver drowsiness detection system that continuously monitors the driver's eye movements using computer vision techniques.

The system detects prolonged eye closure and abnormal blinking patterns to determine whether the driver is becoming drowsy. When signs of fatigue are detected, an audible buzzer alert is triggered to warn the driver and help prevent accidents.

The project demonstrates how artificial intelligence and computer vision can be used to improve road safety through continuous driver monitoring.

---

## 🎯 Objective

The objective of this project is to develop an intelligent driver monitoring system capable of detecting fatigue in real time and providing immediate alerts to reduce the risk of accidents caused by drowsy driving.

---

## 🛠️ Technologies Used

- Python
- OpenCV
- Dlib
- NumPy
- Computer Vision

---

## 🔄 Project Workflow

Camera Capture
        ↓
Face Detection
        ↓
Eye Detection
        ↓
Eye Aspect Ratio (EAR) Calculation
        ↓
Drowsiness Detection
        ↓
Buzzer Alert
        ↓
Driver Safety

---

## ✨ Features

- Real-time face detection
- Eye tracking using facial landmarks
- Eye Aspect Ratio (EAR) calculation
- Detection of prolonged eye closure
- Automatic buzzer alert for driver warning
- Continuous monitoring for improved road safety

---

## 📸 Project Images

### Driver Monitoring System

(Add your project screenshot here.)

```markdown
![Driver Monitoring](images/driver_monitoring.png)
```

### Eye Detection

(Add the eye detection output.)

```markdown
![Eye Detection](images/eye_detection.png)
```

### Drowsiness Alert

(Add the alert output.)

```markdown
![Alert](images/drowsiness_alert.png)
```

---

## 📂 Working Process

1. Capture live video using a webcam.
2. Detect the driver's face in each video frame.
3. Identify facial landmarks and locate both eyes.
4. Calculate the Eye Aspect Ratio (EAR).
5. Monitor blink patterns and eye closure duration.
6. Detect signs of drowsiness when the EAR remains below the threshold.
7. Activate a buzzer alert to wake the driver.
8. Continue monitoring in real time.

---

## 🚀 Applications

- Driver Assistance Systems
- Smart Vehicles
- Fleet Safety Monitoring
- Transportation Safety
- AI-Based Road Safety Systems

---

## 🔮 Future Improvements

- Head pose estimation
- Yawning detection
- Mobile application integration
- Cloud-based driver monitoring
- Deep learning-based fatigue detection
