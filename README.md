# Detecting Web Attacks with End-to-End Deep Learning

This project implements an end-to-end deep learning solution for detecting web application attacks, including SQL Injection (SQLi) and Cross-Site Scripting (XSS), from URLs. The model achieves a detection accuracy of approximately 98.3%.

## 🚀 Project Overview

Web applications are frequent targets for cyber-attacks due to their accessibility and often inherent vulnerabilities. This project focuses on identifying malicious web requests using deep learning techniques, specifically Convolutional Neural Networks (CNNs), to classify URLs as either benign or indicative of an attack.

## 🔍 Key Features

- **High Detection Accuracy**: Achieves approximately 98.3% accuracy in identifying SQLi and XSS attacks.
- **Deep Learning Model**: Utilizes CNNs for effective feature extraction and classification from URL data.
- **Data Preprocessing**: Implements Word2Vec for encoding URLs into vector representations suitable for deep learning models.
- **Modular Codebase**: Organized into distinct modules for data processing and model training.

## 🧠 Technologies Used

- **Programming Language**: Python
- **Deep Learning Framework**: TensorFlow, Keras
- **Natural Language Processing**: Word2Vec
- **Data Processing**: NumPy, Pandas
- **Model Evaluation**: Scikit-learn

## ⚙️ Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Sharada1809/Detecting-Web-Attacks-with-End-to-End-Deep-Learning.git
Navigate into the project directory:

cd Detecting-Web-Attacks-with-End-to-End-Deep-Learning


## Install the required dependencies:
pip install -r requirements.txt


## 📂 Project Structure
Detecting-Web-Attacks-with-End-to-End-Deep-Learning/
│
├── Code/
│   ├── DataProcess/
│   │   └── data_process.py
│   └── Model/
│       └── keras_v1_One_label.py
│
├── Data/
│   ├── Unique-data/
│   ├── Train&Test/
│   ├── Model-Word2vec/
│   ├── Replace-data/
│   ├── Encode-data/
│   └── Predict/
│
├── Model_Save/
├── requirements.txt
└── README.md

'''
## Sample Outputs

Model Performance Metrics:

Accuracy: 98.3%

Precision: 97.5%

Recall: 96.8%

F1-Score: 97.1%

## SHAP Feature Importance:
Visualization of key features influencing the model's predictions.

