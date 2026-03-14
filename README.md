AgriSentinel AI
AgriSentinel AI is a smart monitoring platform built to help farmers get ahead of crop stress, soil degradation, and pest outbreaks. Instead of waiting for visible damage, we use multispectral imaging and IoT sensors to catch problems while they’re still invisible to the naked eye.
# Why did we build this?
Traditional farming relies on manual "scouting"—literally walking the fields to look for bugs or wilting leaves. By the time a human notices a problem, it's often too late to save the crop without heavy chemicals.
We wanted to build a system that acts as an **early warning system**, using AI to analyze data that humans simply can't see.
---
# What it does
* **Spectral Analysis:** We use multispectral/hyperspectral data to track "invisible" crop stress (like NDVI).
* **Ground Truth:** Real-time IoT sensors monitor soil moisture, pH, and local humidity.
* **Smart Predictions:** * **CNNs** to identify specific diseases from images.
* **LSTMs** to predict pest risks based on weather and history.
* **Random Forest** to analyze soil health and recommend actions.
---
# The Tech Stack
We kept the architecture modular so it's easy to swap out models or hardware:
| Layer | Technology |
| --- | --- |
| **Language** | Python 3.x |
| **AI / Computer Vision** | TensorFlow, PyTorch, OpenCV, Scikit-Learn |
| **Data Handling** | Pandas, NumPy |
| **Backend** | FastAPI (or Flask) |
| **Frontend** | Streamlit / React Dashboard |
| **Hardware** | Soil moisture sensors, DHT22, Multispectral Drone cameras |
---
# Getting Started
1. Clone the repo:
```bash
https://github.com/vijaybhargavchiluveru/agrisentinel-ai.git
cd agrisentinel-ai

```

**2. Set up your environment:**

```bash
pip install -r requirements.txt

```

**3. Fire it up:**

```bash
python app.py

```

---

##What’s next? (Roadmap)
* **Satellite Data:** Moving from drones to large-scale satellite monitoring.
* **Edge AI:** Optimizing models to run on low-power devices in fields with no internet.
* **Mobile App:** Push notifications for farmers so they get alerts directly on their phones.
### The Team 
This project was built by:
* **Vijay Bhargav** – The Model Developer
* **Srinivas** – The IoT & Sensor Guy
* **Aarif** – Frontend & UX Design
* **Jayavardhan** – Architecture & Data Flow
