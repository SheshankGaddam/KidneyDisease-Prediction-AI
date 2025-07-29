# KidneyDisease-Prediction-AI
AI-powered Flask web app that predicts the presence of kidney disease using Artificial Neural Networks (ANN) trained on real-world health data. Built during an IBM-supported internship with SmartBridge.

# 🧠 Kidney Disease Prediction using AI (Flask + ANN)

This repository contains the source code and documentation for a machine learning project developed as part of an internship at **SmartBridge in collaboration with IBM**. The project focuses on predicting kidney disease using deep learning techniques (ANN) and provides a user-friendly web interface via Flask.

---

## 📌 Project Overview

Kidney disease is a growing global health concern. This AI-powered solution predicts whether a person is affected by Chronic Kidney Disease (CKD) based on clinical parameters.

> The goal is early detection and better decision-making through automation, accessible via a simple web interface.

---

## 🚀 Features

- Data Preprocessing & Cleaning
- Exploratory Data Analysis & Visualization
- Model Building using **Artificial Neural Networks (ANN)**
- Flask-based API for web deployment
- UI design using HTML/CSS
- Prediction output with 97.5% accuracy
- Hosted integration-ready `.h5` model file

---

## 📂 Modules Implemented

| Module                   | Description |
|--------------------------|-------------|
| **Data Loading**         | Raw health data loaded via Jupyter notebooks |
| **Preprocessing**        | Handling missing values, encoding, scaling |
| **Visualization**        | Correlation maps and plots using matplotlib/seaborn |
| **ANN Classification**   | Custom ANN model trained and evaluated |
| **Model Creation**       | Tuned for accuracy, saved as `.h5` |
| **Flask Integration**    | Backend integration with trained model |
| **UI Development**       | Simple and clean frontend for prediction |

---

## 🧪 Tech Stack

- **Python 3.8+**
- **Pandas / Numpy / Seaborn / Matplotlib**
- **TensorFlow / Keras**
- **Flask**
- **HTML / CSS / Bootstrap (for UI)**

---

## 📈 Model Accuracy

- Training Accuracy: **97.5%**
- False Negatives: Minimal (Based on Confusion Matrix)

---

## 📸 UI Preview

> Screenshots of the UI and model output.
<img width="940" height="476" alt="image" src="https://github.com/user-attachments/assets/62b186d5-bb91-4b18-a7af-02372d084e02" />
<img width="940" height="455" alt="image" src="https://github.com/user-attachments/assets/34033dae-584b-4fc9-b770-0edea1a74688" />


---

## 📍 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/your-username/KidneyDisease-Prediction-AI.git

# Install dependencies
pip install -r requirements.txt

# Run Flask App
python app.py
