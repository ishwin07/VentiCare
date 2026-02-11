# 🏥 VentiCare – AI-Powered ICU Assistance System

VentiCare is an intelligent ICU support system that helps critical patients communicate using eye blinks and predicts their medical needs using AI.

It combines Computer Vision + Machine Learning to improve response time and reliability in ICU environments.

---

# 1️⃣ The Problem

In ICU settings:

- Some patients cannot speak or move.
- Nurses cannot constantly monitor every small change.
- Traditional blink detection systems give false alerts.
- Patient needs (like oxygen adjustment or repositioning) are detected late.

This can delay medical response.

---

# 2️⃣ The Solution

VentiCare solves this using **two AI modules**:

### 🔹 A) Blink Detection System
- Detects intentional eye blinks using webcam
- Ignores false blinks caused by movement
- Uses motion filtering and adaptive thresholds
- Enables hands-free communication

### 🔹 B) AI Proxy Nurse
- Uses IoT health data (heart rate, oxygen level, BP, ventilator status)
- Learns patterns from previous cases
- Predicts patient needs like:
  - Repositioning
  - Oxygen Adjustment
  - Suctioning
- Gives prediction with confidence score

Together, this enables faster and smarter ICU assistance.

---

# 3️⃣ How It Works

### Step 1: Patient Blink
Camera detects intentional blink.

### Step 2: Stability Check
System ensures no motion or false detection.

### Step 3: IoT Data Analysis
Health vitals are processed.

### Step 4: AI Prediction
Machine learning model predicts likely patient need.

### Step 5: Alert Generated
System shows predicted intervention with confidence score.

---

# 4️⃣ Screenshots

https://github.com/ishwin07/VentiCare/blob/main/blink_detector.png

https://github.com/ishwin07/VentiCare/blob/main/aiNurse.jpeg

---

# 5️⃣ Tech Stack

- Python
- OpenCV
- MediaPipe
- Scikit-learn
- RandomForestClassifier
- IsolationForest
- NumPy
- Joblib

---

# ▶️ How to Run

### Install dependencies:
```bash
pip install opencv-python mediapipe scikit-learn numpy joblib
```

### Run Blink Detection:
```bash
python BlinkDetector.py
```

### Run AI Proxy Nurse:
```bash
python patient_voice_proxy.py
```

---


# 👤 Author

Ishwin  

