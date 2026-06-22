# Crop Recommendation Using Machine Learning and Deep Learning

## Overview

This project presents an intelligent Crop Recommendation System that predicts the most suitable crop based on soil nutrients and environmental conditions. The proposed framework integrates both Machine Learning (ML) and Deep Learning (DL) techniques to provide highly accurate crop recommendations using soil and climatic features.

The system utilizes Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall data to predict the most appropriate crop among 22 crop categories. The project includes data preprocessing, exploratory data analysis, model training, performance evaluation, model deployment, and mobile application integration.

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

**Crop Label (22 Crop Classes)**

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

### Hardware Configuration

* Platform: Google Colab
* Processor: Intel Xeon CPU (Google Colab Runtime)
* GPU: Google Colab GPU Runtime
* RAM: Google Colab High-RAM Environment
* Storage: Google Drive and Google Colab Cloud Storage

### Software Environment

* Python 3.x
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* PyTorch
* PyTorch TabNet
* SHAP
* Optuna
* Flutter
* Android Studio
* Supabase
* Hugging Face API

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

The results demonstrate that both TabNet and Naive Bayes achieved the highest classification accuracy of 99.55%, while Random Forest and the Ensemble model achieved 99.32% accuracy. The comparative analysis highlights the effectiveness of both Machine Learning and Deep Learning approaches for crop recommendation tasks.

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
* Real-time Database Management
* Cloud Data Synchronization

#### Model Deployment

* Hugging Face Inference API
* Real-time Model Serving
* API-Based Prediction System

### Deployment Architecture

User Input → Amar Jomi Mobile Application → Hugging Face API → Trained Crop Recommendation Model → Prediction Result → User Interface

The integration of Flutter, Supabase, and Hugging Face enables real-time crop recommendation through a scalable cloud-based architecture, making the proposed system suitable for practical agricultural applications.

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

```text
Crop-Recommendation-Using-Machine-Learning-and-Deep-Learning/

├── Crop_recommendation.csv
├── Crop_Recommendation_ML_DL_Project.py
├── Crop_Recommendation_ML_DL_Project.ipynb
│
├── figure/
│   ├── class_distribution.png
│   ├── correlation_heatmap.png
│   ├── bubble_plot.png
│   ├── tabnet_roc_curve.png
│   ├── tabnet_confusion_matrix.png
│   └── ensemble_confusion_matrix.png
│
├── README.md
└── LICENSE
```

---

## Repository Contents

* Dataset
* Source Code
* Google Colab Notebook
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


