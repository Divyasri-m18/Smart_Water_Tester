# 💧 Smart Water Tester & Purifier (IoT + AI)

A real-time **Smart Water Quality Monitoring System** that measures water parameters using IoT sensors and predicts whether the water is **SAFE or UNSAFE** using an AI model.

---

## 🚀 Live Demo (Render Deployment)

🔗 **Live Dashboard:**  
https://smart-water-tester-1.onrender.com

---

## 🧠 Project Overview

This project integrates **IoT, Cloud, AI, and Web Technologies** to continuously monitor water quality and provide instant feedback to users.

---

## ⚙️ Working Principle

### 1️⃣ Sensing Layer
Sensors continuously measure:
- **pH** – Acidity / Alkalinity
- **TDS** – Total Dissolved Solids
- **Turbidity** – Water clarity
- **Temperature** – Heat level

---

### 2️⃣ IoT Layer (ESP32)
- Reads sensor values
- Sends data to **ThingSpeak Cloud** every 15 seconds
- Activates **LED & Buzzer** when unsafe water is detected

---

### 3️⃣ Cloud Layer (ThingSpeak)
- Stores sensor data
- Displays real-time graphs
- Provides API access for dashboard & AI model

---

### 4️⃣ AI Layer
- Trained using **Kaggle Water Potability Dataset**
- Machine Learning model predicts:
  - **SAFE (Potable)**
  - **UNSAFE (Non-Potable)**

---

### 5️⃣ Dashboard Layer
- Built using **Flask + HTML + CSS + JavaScript**
- Fetches live data from ThingSpeak
- Displays:
  - Live sensor readings
  - SAFE / UNSAFE status
  - Historical graphs

---

## 📊 Results

| Water Type | Observed Values |
|-----------|----------------|
| RO Water | TDS: 20–50 ppm |
| Tap Water | TDS: 150–250 ppm |
| Borewell Water | TDS: 300–450 ppm |
| Salt Water | 10000+ ppm ❌ |
| pH Range | 7.2 – 8.4 |

✔ AI model successfully classified unsafe samples with high TDS and turbidity.

---

## 🏆 Achievements

- ✅ Real-time IoT monitoring implemented
- ✅ AI model accuracy ~78%
- ✅ Clean and modern web dashboard
- ✅ Cloud + AI + Alerts integrated
- ✅ Low power and continuous operation

---

## 📸 Project Screenshots

### 🔹 Hardware Setup
![Hardware](assets/hardware.jpg)

### 🔹 Dashboard View
![Dashboard](assets/dashboard.png)

### 🔹 ThingSpeak Graphs
![Graphs](assets/thingspeak.png)

> Upload your images into an **`assets/`** folder in GitHub.

---

## 🧰 Tech Stack

- **Hardware:** ESP32, pH Sensor, TDS Sensor, Turbidity Sensor, DS18B20
- **IoT Cloud:** ThingSpeak
- **AI/ML:** Python, Scikit-learn
- **Backend:** Flask
- **Frontend:** HTML, CSS, JavaScript
- **Deployment:** Render
- **Version Control:** GitHub

---

## 👩‍💻 Team Member

- **Aishwarya R**

---

## 📌 Conclusion

The **Smart Water Tester & Purifier** system provides an efficient and reliable solution for real-time water quality monitoring.  
By combining **IoT + Cloud + AI**, it ensures early detection of unsafe water and improves public health awareness.

---

⭐ If you like this project, give it a star!
