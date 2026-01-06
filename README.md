# PrognosAI – AI-Driven Predictive Maintenance 🚀

PrognosAI is an **industry-grade predictive maintenance system** that estimates the  
**Remaining Useful Life (RUL)** of turbofan engines using **deep learning (GRU)** models  
trained on the **NASA CMAPSS dataset**.  
The system converts predictions into **actionable maintenance alerts** and visualizes  
engine health through an **interactive Streamlit dashboard**.

---

## 🔧 Key Features

- 🔍 Remaining Useful Life (RUL) prediction for each engine  
- 🚦 Risk classification: **Normal / Warning / Critical**  
- 🏭 Fleet-level health monitoring  
- 🔧 Engine-level drill-down analysis  
- 📊 Interactive Streamlit dashboard  
- 📉 Model performance insights (RMSE)

---

## 🧠 Tech Stack

- **Programming Language:** Python  
- **Deep Learning:** TensorFlow / Keras (GRU)  
- **Data Processing:** Pandas, NumPy  
- **Visualization:** Matplotlib  
- **Dashboard:** Streamlit  

---

## 📊 Dataset

**NASA CMAPSS – Turbofan Engine Degradation Dataset**

- Simulated sensor data from aircraft engines
- Multiple operating conditions (FD001–FD004)
- Widely used benchmark for predictive maintenance research

---

## 📂 Project Structure

```text
prognosAI/
│
├── app.py                     # Streamlit dashboard
├── predictions/               # Model prediction CSV files
│   ├── FD001_predictions.csv
│   ├── FD002_predictions.csv
│   ├── FD003_predictions.csv
│   └── FD004_predictions.csv
│
├── metrics/                   # Model evaluation metrics
│   ├── FD001_metrics.json
│   ├── FD002_metrics.json
│   ├── FD003_metrics.json
│   └── FD004_metrics.json
│
├── models/                    # Trained GRU models
├── scalers/                   # Feature scalers
├── requirements.txt
└── README.md
