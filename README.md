# EEG-Eye-State-Data-Set-ML-model
EEG Signal Classification Using Random Forest and Neural Networks

# 🧠 EEG Signal Classification using Random Forest and Neural Networks

## 📌 Overview
This project focuses on classifying **EEG (Electroencephalogram) signals** using both **Machine Learning** and **Deep Learning** techniques. EEG signals are complex and noisy, making them suitable for advanced classification models.

Two models were implemented and compared:
- Random Forest Classifier
- Artificial Neural Network (ANN)

The objective is to evaluate their performance and identify the most effective approach for EEG signal classification.

---

## 📂 Dataset
- **Source:** Kaggle – Complete EEG Dataset
- **Selected File:** `s30`
- **Data Type:** Time-series EEG signals
- **Features:** Multiple EEG channel values
- **Labels:** Generated using signal energy thresholding

### Label Generation
Since the dataset does not contain predefined labels:
- Samples with EEG signal energy above the global mean are labeled as `1`
- Samples with EEG signal energy below the global mean are labeled as `0`

---

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Platform:** Google Colab
- **Libraries:**
  - NumPy
  - Pandas
  - Scikit-learn
  - TensorFlow / Keras
  - Matplotlib

---

## ⚙️ Project Workflow
EEG Dataset
↓
Data Preprocessing
↓
Feature Scaling
↓
Label Generation
↓
Model Training
├── Random Forest
└── Neural Network
↓
Evaluation & Comparison


---

## 🧪 Models Implemented

### 🌲 Random Forest Classifier
- Ensemble-based learning method
- Robust to noisy EEG data
- Handles non-linear patterns efficiently

### 🧠 Neural Network
- Feedforward Artificial Neural Network
- ReLU activation in hidden layers
- Sigmoid activation in output layer
- Learns complex non-linear EEG signal patterns

---

## 📊 Results

| Model | Accuracy |
|------|----------|
| Random Forest | **97.81%** |
| Neural Network | **99.63%** |

### Observation
The Neural Network achieved higher accuracy due to its ability to capture complex and non-linear EEG signal patterns.

---

---

### ✅ Next (Optional but Recommended)
I can now generate:
- `requirements.txt`
- Project architecture diagram
- CNN / LSTM upgrade
- Viva questions & answers
