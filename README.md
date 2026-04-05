# NAS-Based Ransomware Detection and Monitoring System

## 📌 Overview
This project focuses on protecting Network Attached Storage (NAS) systems from ransomware attacks using machine learning, real-time monitoring, and IoT-based alert mechanisms.

Ransomware encrypts files and demands payment for access. This system detects suspicious behavior early and prevents data loss.

---

## 🚀 Features
- Real-time file monitoring (creation, deletion, modification)
- Machine Learning-based anomaly detection (Isolation Forest)
- File entropy and hash analysis for encryption detection
- Automatic file quarantine system
- Email and dashboard alerts
- IoT integration (ESP32, buzzer, LEDs)
- Threat intelligence integration using AlienVault OTX

---

## 🧠 Technologies Used
- Python
- Flask (Backend & Dashboard)
- Machine Learning (Isolation Forest)
- SHA-256 Hashing
- ESP32 (IoT Alerts)
- NAS Storage System
- AlienVault OTX API

---

## 🏗️ System Architecture
1. Monitoring Layer – Tracks file activities
2. Analysis Layer – Detects anomalies using ML
3. Alert Layer – Sends notifications via dashboard, email, and IoT devices

---

## ⚙️ How It Works
1. Files are monitored continuously in NAS
2. Features like entropy, file changes, and extensions are analyzed
3. Isolation Forest detects anomalies
4. Suspicious files are quarantined
5. Alerts are sent to users

---

## 📊 Key Detection Indicators
- Sudden file renaming
- High entropy (encryption)
- Suspicious file extensions (.locky, .crypt)
- High disk I/O activity

---

## 🔒 Advantages
- Real-time ransomware detection
- Low computational cost
- Multi-layer security (ML + IoT + Threat Intelligence)
- Automatic response system

---

## 📌 Future Enhancements
- Deep learning-based detection
- Cloud integration
- Mobile app alerts
- Advanced visualization dashboard

---

## 👥 Contributors
- Narasimman C
- Vinod Kannaa M
- Vignesh S

---

## 📄 License
This project is for academic and research purposes.
