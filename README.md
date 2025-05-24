# 🔥 SmartGuard: AI-Based Tamper and Fault Detection for EV Chargers

**SmartGuard** is an AI + IoT based safety system designed to monitor, detect, and alert users about fire, smoke, short circuits, and tampering incidents in EV (Electric Vehicle) charging stations.

> Developed by @Sunkesula-Suhel  
> 🎓 Engineering in Technology | 🔬 Researcher | 🌐 [Orcid: 0009-0005-3956]  
> 📫 Reach me: shamsheersuhel@gmail.com

---

## 🚀 Features

- 🔍 Real-time fire/smoke/spark detection via YOLOv8
- 🌡 Simulated sensor data: temperature, current, vibration
- 📊 Anomaly detection using machine learning
- 📤 WhatsApp alerts via Twilio API
- 🖥 Live Streamlit dashboard for real-time monitoring
- 📁 CSV logs + captured alert images

---

## 🗂 Project Structure
SmartGuard-EV-AI/
├── models/ # Trained YOLOv8 model (best.pt)
├── data/ # Sensor logs and images
├── src/
│ ├── alerts/ # WhatsApp alert integration
│ ├── sensors/ # Sensor simulation and anomaly detection
│ ├── vision/ # YOLO-based fire/smoke detection
│ └── dashboard/ # Dashboard logic (optional)
├── smartguard_dashboard.py # Streamlit UI for live monitoring
├── requirements.txt # All dependencies
├── README.md # Project documentation


---

## ⚙️ Setup Instructions

1. Install Python 3.12
2. Install dependencies:

```bash
pip install -r requirements.txt


