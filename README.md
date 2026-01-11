
# 🌾 Crop Yield Prediction System using Random Forest & Geospatial Data

A **production-grade, end-to-end Machine Learning web application** that predicts crop yield for Indian agriculture using **Random Forest regression**, real-world datasets from **data.gov.in**, and a **live deployed web interface** accessible to anyone via a public link.

🔗 **Live Demo (Recruiter-Ready):**  
👉 https://crop-yield-prediction-system-using.onrender.com/

---

## 📌 Project Motivation

Agriculture is one of the most critical sectors in India, yet crop yield prediction is affected by multiple uncertain factors such as rainfall, fertilizer usage, land area, and seasonal variations.  
This project demonstrates how **machine learning can be applied to real government data** to build a decision-support system that is:

- Data-driven  
- Scalable  
- Interpretable  
- Production-deployed  

This repository showcases not only ML modeling but also **real-world deployment, backend engineering, and system design**.

---

## 🚀 Project Overview

The Crop Yield Prediction System allows users to:
- Select crop, season, and state
- Provide environmental and agricultural inputs
- Obtain real-time yield predictions
- Understand feature influence on predictions
- Download results in Excel format

The application follows the complete ML lifecycle:
**data ingestion → preprocessing → modeling → evaluation → deployment**.

---

## 🧠 Machine Learning Design

### 🔹 Learning Type
- Supervised Learning  
- Regression Problem  

### 🔹 Algorithm: Random Forest Regressor

Why Random Forest?
- Handles non-linear relationships effectively  
- Performs well on structured/tabular datasets  
- Resistant to overfitting  
- Robust to noisy real-world data  

### 🔹 Target Variable
- Crop Yield (tonnes per hectare)

---

## 📊 Dataset Description

- **Source:** data.gov.in (Government of India Open Data Portal)
- **Type:** Historical agricultural records
- **Scope:** State-level crop data

### 🔹 Input Features
- Crop  
- Season  
- State  
- Area under cultivation  
- Annual rainfall  
- Fertilizer consumption  
- Pesticide usage  

### 🔹 Data Processing
- State name normalization for geospatial consistency  
- Input validation and missing value checks  
- One-hot encoding for categorical variables  
- Standard scaling for numerical features  

---

## ⚙️ Model Pipeline

1. Data validation and normalization  
2. Feature selection and transformation  
3. Train-test data split  
4. Pipeline-based preprocessing  
5. Random Forest training  
6. Performance evaluation (R², MSE)  
7. Model serialization using Pickle  

The trained model is reused during inference for efficient predictions.

---

## 📈 Model Interpretability

To increase transparency, the system exposes **feature importance**, allowing users to:
- Understand which parameters influence yield the most
- Gain trust in ML predictions
- Perform comparative analysis across inputs

---

## 🌍 Geospatial Integration

- Normalized state-level data compatible with GeoJSON
- Enables region-specific predictions
- Designed for future map-based visualization extensions

---

## 🖥️ Web Application Capabilities

- User-friendly web interface
- Real-time ML inference
- Input validation and error handling
- Excel (.xlsx) report generation
- Public deployment on cloud infrastructure

The application is accessible without installation, making it ideal for recruiter evaluation.

---

## 🛠️ Technology Stack

### 🔹 Backend & ML
- Python  
- Flask  
- Scikit-learn  
- Pandas  
- NumPy  

### 🔹 Deployment
- Render (Cloud platform)
- Gunicorn (Production WSGI server)

### 🔹 Data
- Government Open Data (data.gov.in)

---

## ⚙️ Local Setup Instructions

### Clone Repository
```bash
git clone https://github.com/gautam0222/Crop-Yield-Prediction-System-using-Random-Forest-Geospatial-Data.git
cd Crop-Yield-Prediction-System-using-Random-Forest-Geospatial-Data
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run Application
```bash
python app.py
```

Visit:
```
http://localhost:5000
```

---

## 📊 Practical Use Cases

- Crop yield forecasting  
- Agricultural research & analysis  
- Decision support systems  
- ML portfolio demonstration  
- Government & policy data analysis  

---

## 🧪 Validation & Reliability

- Server-side input validation  
- Dataset integrity checks  
- Robust error handling  
- Graceful failure recovery  

---

## 🚧 Future Enhancements

- Integration with live weather APIs  
- District-level predictions  
- Deep learning–based yield models  
- Interactive geospatial dashboards  
- Mobile-first UI  

---

## ⚠️ Disclaimer

This project is intended for **educational and analytical purposes only**.  
Predictions are based on historical data and should not be used as the sole basis for real-world agricultural decisions.

---

## 👨‍💻 Author

**Gautam Sukhani**  
Machine Learning | Data Science | Full Stack Development  

---

## ⭐ Acknowledgement & Support

If you find this project valuable:
- ⭐ Star the repository  
- 🔀 Fork and enhance  
- 📝 Share feedback  

This project highlights **end-to-end ML engineering and deployment expertise**, not just model training.
