# Air Quality Index Prediction Using LSTM

## 📌 Project Overview

**Air Quality Index Prediction Using LSTM** is a deep learning project that predicts the **Air Quality Index (AQI)** using historical air pollution and environmental data.

The project uses a **Long Short-Term Memory (LSTM)** neural network, which is well suited for time-series data. The model learns patterns from historical AQI values and related environmental parameters to predict future air quality.

The goal is to provide an effective way to monitor and forecast air quality using deep learning.

---

live server
https://cdx93u-4n0ufbdgj-arcedawebapps1.vercel.app

## 👨‍💻 Author

**Mahidhar Yadav**
Artificial Intelligence and Data Science Student

---

## 🎯 Objectives

* Predict future Air Quality Index values.
* Analyze historical air quality data.
* Identify patterns and trends in air pollution.
* Apply LSTM for time-series prediction.
* Support better air-quality monitoring and planning.

---

## 🧠 Technologies Used

* **Python**
* **TensorFlow**
* **Keras**
* **LSTM (Long Short-Term Memory)**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**
* **Jupyter Notebook / Google Colab**

---

## 🔄 System Workflow

```text
Historical Air Quality Data
          ↓
Data Cleaning
          ↓
Missing Value Handling
          ↓
Feature Selection
          ↓
Data Normalization
          ↓
Time-Series Sequence Creation
          ↓
LSTM Model
          ↓
Model Training
          ↓
AQI Prediction
          ↓
Performance Evaluation
```

---

## 📊 Dataset

The dataset contains historical air-quality measurements.

Depending on the dataset, features may include:

* PM2.5
* PM10
* NO₂
* SO₂
* CO
* O₃
* Temperature
* Humidity
* AQI

The data is processed and converted into time-series sequences before being provided to the LSTM model.

---

## 🤖 Why LSTM?

**Long Short-Term Memory (LSTM)** is a type of Recurrent Neural Network (RNN) designed to learn patterns from sequential and time-dependent data.

Air quality changes over time and can depend on previous measurements. LSTM can learn these temporal relationships and use them to make future AQI predictions.

---

## 🏗️ Model Architecture

```text
Input Time-Series Data
        ↓
LSTM Layer
        ↓
Dropout
        ↓
LSTM Layer
        ↓
Dropout
        ↓
Dense Layer
        ↓
Output Layer
        ↓
Predicted AQI
```

---

## 📁 Project Structure

```text
Air-Quality-Index-Prediction-LSTM/
│
├── dataset/
│   └── air_quality.csv
│
├── model/
│   └── aqi_lstm_model.h5
│
├── notebooks/
│   └── aqi_prediction.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── train.py
│   └── predict.py
│
├── requirements.txt
│
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Air-Quality-Index-Prediction-LSTM.git
```

### 2. Open the Project

```bash
cd Air-Quality-Index-Prediction-LSTM
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

Example `requirements.txt`:

```text
tensorflow
keras
pandas
numpy
matplotlib
scikit-learn
```

---

## 🚀 How to Run

### Step 1: Prepare the Dataset

Place the air-quality dataset inside the `dataset` folder.

### Step 2: Preprocess the Data

Clean the dataset, handle missing values, normalize the features, and create time-series sequences.

### Step 3: Train the LSTM Model

```bash
python src/train.py
```

The trained model will be saved inside the `model` folder.

### Step 4: Make Predictions

```bash
python src/predict.py
```

The model will generate predicted AQI values based on the input data.

---

## 📈 Model Evaluation

The performance of the LSTM model can be evaluated using:

* **MAE (Mean Absolute Error)**
* **MSE (Mean Squared Error)**
* **RMSE (Root Mean Squared Error)**
* **R² Score**

Actual and predicted AQI values can also be visualized using graphs.

```text
Actual AQI
     │
     │     ╭──╮
     │  ╭──╯  ╰──╮
     │──╯        ╰────
     │
     └──────────────────→ Time

Predicted AQI
     │
     │    ╭───╮
     │ ╭──╯   ╰──╮
     │─╯         ╰────
     │
     └──────────────────→ Time
```

---

## 💡 Applications

This project can be useful for:

* Air pollution monitoring
* Smart city systems
* Environmental analysis
* Public health planning
* Pollution forecasting
* IoT-based air-quality monitoring

---

## 🔮 Future Enhancements

* Real-time AQI prediction.
* Integration with IoT air-quality sensors.
* Weather data integration.
* City-wise AQI forecasting.
* Interactive AQI dashboard.
* Mobile application for AQI alerts.
* Compare LSTM with GRU, RNN, and Transformer models.

---

## ⚠️ Limitations

* Prediction accuracy depends on the quality and quantity of historical data.
* Sudden environmental changes may be difficult to predict.
* Different cities may require different models because pollution patterns vary by location.
* External factors such as weather, traffic, and industrial activity can affect AQI.

---

## 🎓 Project Purpose

This project demonstrates how **Deep Learning and Time-Series Analysis** can be used to forecast air quality.

By applying an **LSTM neural network** to historical environmental data, the system aims to predict future AQI values and support better understanding and monitoring of air pollution.

---

## 👨‍💻 Developed By

**Mahidhar Yadav**
**Artificial Intelligence and Data Science**

> *Using Deep Learning to understand and predict environmental changes.*
