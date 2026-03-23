# 🚨 Fraud Detection System (Machine Learning + Streamlit)

## 📌 Overview

This project is an **end-to-end machine learning system** designed to detect fraudulent financial transactions. It combines data preprocessing, model training, and an interactive web interface to deliver real-time predictions.

The application allows users to input transaction details and instantly determine whether a transaction is likely fraudulent.

---

## ⚙️ Features

* 🧠 Machine Learning–based fraud detection
* 📊 Real-time prediction using trained pipeline
* 🌐 Interactive web interface built with Streamlit
* 🔄 Handles structured transaction data
* ⚡ Fast inference using serialized model (`.pkl`)

---

## 🧱 Tech Stack

### Backend / Core

* Python
* Pandas
* Scikit-learn
* Joblib

### Frontend / UI

* Streamlit

---

## 🧠 How It Works

1. **Input Collection**
   User provides transaction details:

   * Transaction type
   * Amount
   * Sender/Receiver balances

2. **Data Processing**
   Inputs are structured into a DataFrame matching the training schema.

3. **Model Inference**
   A pre-trained machine learning pipeline is loaded and used to predict fraud probability.

4. **Output Display**
   The system returns:

   * Prediction (Fraud / Not Fraud)
   * Visual feedback via UI

---

## 📂 Project Structure

```
fraud-detection/
│
├── fraud_detection.py          # Streamlit app
├── fraud_detection_pipeline.pkl  # Trained ML model
├── AIML Dataset.csv           # Dataset used for training
├── analysis_model.ipynb       # Model training & experimentation
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/fraud-detection.git
cd fraud-detection
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
streamlit run fraud_detection.py
```

---

## 🧪 Example Use Case

Input:

```
Transaction Type: TRANSFER  
Amount: 5000  
Old Balance (Sender): 10000  
New Balance (Sender): 5000  
```

Output:

```
Prediction: Fraud (1)
```

---

## 📈 Future Improvements

* Add fraud probability score (confidence %)
* Store transaction history (database integration)
* Model explainability (feature importance)
* API version using Flask/FastAPI
* Deployment on cloud (AWS / Render)

---

## 🎯 Key Learnings

* Built a complete ML pipeline from data to deployment
* Integrated model inference into a real-time application
* Gained experience in data preprocessing, classification, and UI integration

---

## 📌 Author

**Jivitesh Sachdev**
Python Backend & Data Developer



