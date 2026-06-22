# Crop Recommendation Using Machine Learning and Deep Learning

## Overview

This project presents an IoT-enabled intelligent Crop Recommendation System designed to predict the most suitable crop based on soil nutrients and environmental conditions. The proposed framework integrates Internet of Things (IoT), Machine Learning (ML), Deep Learning (DL), cloud computing, and mobile technologies to provide accurate crop recommendations and smart agricultural decision support.

The system utilizes real-time sensor data, including Nitrogen (N), Phosphorus (P), Potassium (K), soil moisture, pH, temperature, humidity, and rainfall-related parameters to recommend suitable crops among 22 crop categories.

In addition to crop recommendation, the system supports smart irrigation through sensor monitoring, relay control, and water pump automation. The trained models are deployed through the Hugging Face Inference API and integrated into the Amar Jomi mobile application developed using Flutter.

---

## Dataset Description

The dataset consists of soil nutrient and environmental parameters used for crop recommendation.

### Input Features

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Temperature (°C)
* Humidity (%)
* pH
* Rainfall (mm)

### Target Variable

Crop Label (22 Crop Classes)

* Rice
* Maize
* Chickpea
* Kidneybeans
* Pigeonpeas
* Mothbeans
* Mungbean
* Blackgram
* Lentil
* Pomegranate
* Banana
* Mango
* Grapes
* Watermelon
* Muskmelon
* Apple
* Orange
* Papaya
* Coconut
* Cotton
* Jute
* Coffee

---

## Hardware and Software Environment

### Hardware Components

The proposed IoT-enabled crop recommendation system utilizes the following hardware components:

1. ESP32 Microcontroller
2. Capacitive Soil Moisture Sensor
3. NPK Sensor
4. Analog pH Sensor
5. DHT22 Temperature and Humidity Sensor
6. Relay Module
7. 5V Water Pump
8. TTL Converter

### Hardware Functions

| Hardware Component   | Purpose                                             |
| -------------------- | --------------------------------------------------- |
| ESP32                | Data acquisition, communication, and system control |
| Soil Moisture Sensor | Measures soil moisture levels                       |
| NPK Sensor           | Measures Nitrogen, Phosphorus, and Potassium values |
| pH Sensor            | Measures soil acidity and alkalinity                |
| DHT22 Sensor         | Measures temperature and humidity                   |
| Relay Module         | Controls irrigation operations                      |
| 5V Water Pump        | Performs automated watering                         |
| TTL Converter        | Sensor communication and data transmission          |

### Software Environment

* Python 3.x
* Google Colab
* Flutter
* Android Studio
* Supabase
* Hugging Face Inference API
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* PyTorch
* PyTorch TabNet
* SHAP
* Optuna

---

## System Hardware Architecture

The proposed system combines IoT devices, cloud computing, Machine Learning, Deep Learning, and mobile technologies to provide intelligent crop recommendations and smart irrigation support.

### Architecture Flow

Sensors Layer

* NPK Sensor
* Soil Moisture Sensor
* pH Sensor
* DHT22 Temperature and Humidity Sensor

↓

Data Acquisition Layer

* ESP32 Microcontroller
* TTL Communication Module

↓

Cloud Layer

* Supabase Backend
* Real-Time Database Storage

↓

Artificial Intelligence Layer

* Machine Learning Models
* Deep Learning Models
* Hugging Face Inference API

↓

Application Layer

* Amar Jomi Mobile Application
* Flutter-Based User Interface

↓

Output Layer

* Crop Recommendation
* Soil Analysis Results
* Irrigation Decision Support
* Water Pump Control via Relay Module

### Smart Irrigation Support

The relay module and 5V water pump enable automated irrigation support based on real-time soil conditions collected from the deployed sensors.

This architecture provides a complete IoT-enabled smart agriculture ecosystem capable of monitoring environmental conditions, predicting suitable crops, and supporting intelligent irrigation management.

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Machine Learning Model Training
6. Deep Learning Model Training
7. Model Evaluation
8. Model Deployment using Hugging Face API
9. Mobile Application Development using Flutter
10. Comparative Performance Analysis

---

## Machine Learning Models

The following Machine Learning algorithms were implemented and evaluated:

* Decision Tree
* Random Forest
* Naive Bayes
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Logistic Regression
* Gradient Boosting
* Ensemble Model (Random Forest + Naive Bayes + Gradient Boosting)

---

## Deep Learning Models

The following Deep Learning models were implemented and evaluated:

* Artificial Neural Network (ANN)
* Convolutional Neural Network (CNN)
* Long Short-Term Memory (LSTM)
* CNN-LSTM
* TabNet

---

## Experimental Results

| Model               | Accuracy (%) |
| ------------------- | -----------: |
| TabNet              |        99.55 |
| Naive Bayes         |        99.55 |
| Random Forest       |        99.32 |
| Ensemble (RF+NB+GB) |        99.32 |
| Gradient Boosting   |        98.18 |

The results demonstrate that both TabNet and Naive Bayes achieved the highest classification accuracy of 99.55%, while Random Forest and the Ensemble model achieved 99.32% accuracy.

---

## Mobile Application Deployment

To demonstrate the practical applicability of the proposed crop recommendation system, a mobile application named **Amar Jomi** was developed.

### Application Features

* User-friendly mobile interface
* Real-time crop recommendation
* Soil parameter input system
* Instant prediction results
* Cloud-based data management
* Mobile accessibility for farmers and agricultural stakeholders

### Development Technologies

#### Frontend

* Flutter
* Android Studio

#### Backend

* Supabase
* Real-Time Database Management
* Cloud Data Synchronization

#### Model Deployment

* Hugging Face Inference API
* Real-Time Model Serving
* API-Based Prediction System

### Deployment Architecture

User Input → Amar Jomi Mobile Application → Hugging Face API → Trained Crop Recommendation Model → Prediction Result → User Interface

---

## Visualizations and Analysis

The repository contains the following visualizations and experimental results:

* Correlation Heatmap (`correlation_heatmap.png`)
* Class Distribution Analysis (`class_distribution.png`)
* Bubble Plot Analysis (`bubble_plot.png`)
* TabNet ROC Curve (`tabnet_roc_curve.png`)
* TabNet Confusion Matrix (`tabnet_confusion_matrix.png`)
* Ensemble Model Confusion Matrix (`ensemble_confusion_matrix.png`)

These visualizations were generated to evaluate model performance, analyze dataset characteristics, and compare prediction results across different Machine Learning and Deep Learning models.

---

## Repository Structure

Crop-Recommendation-Using-Machine-Learning-and-Deep-Learning/

├── Crop_recommendation.csv

├── Crop_Recommendation_ML_DL_Project.py

├── Crop_Recommendation_ML_DL_Project.ipynb

├── figure/

│ ├── class_distribution.png

│ ├── correlation_heatmap.png

│ ├── bubble_plot.png

│ ├── tabnet_roc_curve.png

│ ├── tabnet_confusion_matrix.png

│ └── ensemble_confusion_matrix.png

├── README.md

└── LICENSE

---

## Repository Contents

* Dataset
* Source Code
* Google Colab Notebook
* IoT Hardware Architecture
* Mobile Application Integration
* Experimental Results
* Figures and Visualizations
* Model Evaluation Results
* Comparative Analysis

---

## How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Open the notebook in Google Colab or run the Python script locally.
4. Load the dataset.
5. Train the Machine Learning and Deep Learning models.
6. Evaluate model performance and generate visualizations.
7. Deploy the model using Hugging Face API.
8. Connect the deployed model with the Amar Jomi mobile application.

---

## Note

If GitHub cannot preview the Colab notebook, please use the `.py` source file or download the `.ipynb` file and open it directly in Google Colab.

---

## Authors

* Md Rakibul Hasan Rezvee
* Ulope Das
* Majeda Akter
* Md Arifuzzaman Soukin

---
