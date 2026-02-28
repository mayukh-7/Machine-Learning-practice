# ❤️ Heart Disease Prediction using Machine Learning

> A Machine Learning web application that predicts the risk of heart disease using a trained K-Nearest Neighbors (KNN) model and an interactive Streamlit interface.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early detection can significantly reduce health risks.

This project uses a **Machine Learning model** to predict whether a person is at:

- ⚠️ High Risk of Heart Disease  
- ✅ Low Risk of Heart Disease  

The prediction is based on medical attributes such as age, cholesterol level, blood pressure, chest pain type, and more.

The application is built using **Streamlit**, making it simple and user-friendly.

---

## 🧠 Machine Learning Model

- 🔍 **Algorithm Used:** K-Nearest Neighbors (KNN)
- 📊 **Preprocessing Steps:**
  - One-Hot Encoding for categorical features
  - Feature scaling using StandardScaler
- 💾 Model files:
  - `KNN_heart.pkl`
  - `scaler.pkl`
  - `columns.pkl`

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- Scikit-learn  
- Joblib  
- Streamlit  

---

## 📂 Project Structure

```
Heart-Disease-Prediction/
│
├── app.py                # Streamlit Web Application
├── Heart-Copy1.ipynb     # Model Training Notebook
├── KNN_heart.pkl         # Trained KNN Model
├── scaler.pkl            # Standard Scaler
├── columns.pkl           # Feature Columns Order
└── README.md             # Project Documentation
```

---

## 📊 Features Used for Prediction

The model takes the following inputs:

- Age  
- Gender  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Fasting Blood Sugar  
- Resting ECG  
- Maximum Heart Rate  
- Exercise-Induced Angina  
- Oldpeak (ST Depression)  
- ST Slope  

---

## 🚀 How to Run the Project Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
```

### 2️⃣ Install Required Libraries

```bash
pip install streamlit pandas scikit-learn joblib
```

### 3️⃣ Run the Application

```bash
streamlit run app.py
```

The app will run on:

```
http://localhost:8501
```

---

## ⚙️ How It Works

1. User enters medical details in the Streamlit interface.
2. Input data is converted into structured format.
3. Missing feature columns are handled automatically.
4. Data is scaled using the trained scaler.
5. KNN model predicts the result.
6. The application displays:
   - ⚠️ High Risk  
   - ✅ Low Risk  

---

## 🎯 Future Improvements

- Add multiple ML models for comparison  
- Display model accuracy and evaluation metrics  
- Deploy on Streamlit Cloud  
- Improve UI design  
- Add data visualization dashboard  

---

## ⚠️ Disclaimer

This project is created for educational purposes only.  
It should not be used as a substitute for professional medical advice.

---

## 👨‍💻 Author

**Mayukh Maity**  
Software Engineering Student  
Machine Learning & Full-Stack Enthusiast  

If you like this project, consider giving it a ⭐ on GitHub!