# Intelligent-plant-disease-detection-and-automated-pesticide-spraying-system-for-agriculture-usingCNN
AI-based plant leaf disease detection system using deep learning, TensorFlow, and OpenCV for accurate crop health analysis. Detects bacterial spot, septoria leaf spot, spider mites, yellow leaf curl virus, and healthy leaves. Includes ESP32-based smart irrigation, relay automation, OLED display, camera monitoring, and IoT connectivity.

## 📌 Overview
The Plant Leaf Disease Detection System is an AI-based smart agriculture project developed to detect plant leaf diseases automatically using deep learning and image processing techniques. The system analyzes plant leaf images captured through a camera and predicts the disease accurately in real time.

This project helps farmers identify plant diseases at an early stage, reducing crop damage and improving agricultural productivity. The system can also automate irrigation control using ESP32 and relay modules.

---

## 🎯 Objectives
- Detect plant leaf diseases automatically
- Improve crop health monitoring
- Reduce manual inspection efforts
- Provide early disease identification
- Automate irrigation systems using IoT

---

## 🦠 Diseases Detected
The model can identify the following conditions:

- Healthy Leaf
- Bacterial Spot
- Septoria Leaf Spot
- Spider Mites
- Yellow Leaf Curl Virus

---

## ⚙️ Technologies Used

### Software
- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Flask (Optional)

### Hardware
- ESP32
- Camera Module
- Relay Module
- Water Pump
- OLED Display
- Wi-Fi Module

---

## 🚀 Features
- Real-time leaf disease detection
- AI-powered image classification
- Automatic irrigation control
- ESP32-based automation
- OLED display output
- Camera monitoring system
- IoT-enabled monitoring
- User-friendly interface

---

## 🛠️ System Architecture

1. Camera captures plant leaf image
2. Image is processed using OpenCV
3. Deep learning model predicts disease
4. Prediction result is displayed
5. ESP32 controls irrigation system
6. OLED displays disease information

---

## 📂 Project Structure

```bash
Plant-Leaf-Disease-Detection/
│
├── dataset/
├── model/
├── images/
├── esp32_code/
├── app/
├── main.py
├── requirements.txt
└── README.md
```

---

## 🧠 Machine Learning Model
The project uses a Convolutional Neural Network (CNN) model trained on plant leaf datasets for disease classification.

### Model Workflow
- Data Collection
- Image Preprocessing
- Model Training
- Disease Prediction
- Result Display

---

## 📷 Input and Output

### Input
- Plant leaf image captured from camera

### Output
- Predicted disease name
- Confidence score
- Pump control action

---

## 🔌 Hardware Connections
- ESP32 connected with relay module
- Relay connected to water pump
- OLED connected using I2C communication
- Camera module for image capturing

---

## 📈 Advantages
- Fast and accurate detection
- Reduces pesticide usage
- Saves water through smart irrigation
- Low-cost implementation
- Easy to use
- Supports precision farming

---

## 🌍 Applications
- Smart Agriculture
- Greenhouse Monitoring
- Crop Disease Analysis
- Automated Farming Systems
- Agricultural Research

---

## ▶️ How to Run the Project

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/Plant-Leaf-Disease-Detection.git
```

### 2️⃣ Install Requirements
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application
```bash
python main.py
```

---

## 📊 Future Enhancements
- Mobile application integration
- Cloud database support
- Multiple crop disease detection
- SMS alert system
- Real-time analytics dashboard

---

## 📸 Project Screenshots
(Add screenshots here)

---

## 👨‍💻 Author
GOKULA KRISHNAN

---

## 📜 License
This project is developed for educational and research purposes.F
