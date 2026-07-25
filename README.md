# 🌱 Smart Irrigation Prediction using Artificial Neural Networks

![Python](https://img.shields.io/badge/Python-3.11-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📌 Overview

Efficient irrigation is one of the most important challenges in modern agriculture.

This project develops an Artificial Neural Network (ANN) that predicts whether a crop requires irrigation based on environmental conditions.

The model learns patterns from:

- Soil Moisture
- Temperature
- Sunlight Hours
- Humidity
- Rainfall

and predicts:

**Need Water (Yes / No)**

---

## Problem Statement

Farmers often rely on manual inspection before irrigating crops.

Incorrect irrigation results in

- Water wastage
- Reduced crop yield
- Higher operational cost

The objective of this project is to build a deep learning model capable of automatically predicting irrigation requirements.

---

## Dataset Features

| Feature | Description |
|----------|-------------|
| Soil Moisture | Water present in soil |
| Temperature | Ambient temperature (°C) |
| Sunlight Hours | Daily sunlight exposure |
| Humidity | Atmospheric humidity (%) |
| Rainfall | Rainfall received (mm) |
| Need Water | Target Variable |

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Workflow

Dataset

↓

Data Preprocessing

↓

Feature Scaling

↓

Train-Test Split

↓

Artificial Neural Network

↓

Model Training

↓

Model Evaluation

↓

Prediction

---

## ANN Architecture

Input Layer (5 Features)

↓

Dense Layer (16 Neurons, ReLU)

↓

Dropout (20%)

↓

Dense Layer (8 Neurons, ReLU)

↓

Output Layer (Sigmoid)

---

## Training Configuration

Optimizer:

Adam

Learning Rate:

0.001

Loss Function:

Binary Crossentropy

Evaluation Metric:

Accuracy

Epochs:

100

Batch Size:

4

---

## Results

The trained model is evaluated using

- Accuracy
- Confusion Matrix
- Classification Report
- Training Accuracy Curve
- Validation Accuracy Curve

---

## Future Improvements

- Train on a larger agricultural dataset
- Integrate IoT soil sensors
- Deploy using Flask or Streamlit
- Real-time irrigation recommendations
- Cloud deployment

---

## Installation

```bash
git clone https://github.com/yourusername/Smart-Irrigation-ANN.git

cd Smart-Irrigation-ANN

pip install -r requirements.txt

