# ❤️ Heart Disease Prediction

A simple Machine Learning web application that predicts the likelihood of heart disease based on a patient's health information. The project is built with **FastAPI** and uses a **Random Forest Classifier** trained with **Scikit-learn**.

---

## 🚀 Features

- Predict heart disease risk
- Fast and lightweight FastAPI application
- Simple and clean user interface
- Real-time predictions
- Machine Learning model using Random Forest

---

## 🛠️ Tech Stack

- Python
- FastAPI
- Uvicorn
- Scikit-learn
- Pandas
- NumPy
- Joblib
- HTML
- CSS
- Jinja2

---

## 📁 Project Structure

```
heart_disease_prediction/
│── app.py
│── heart_disease_rf.pkl
│── requirements.txt
│── README.md
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

---

## 📊 Input Features

- Age
- Gender
- Weight
- Height
- BMI
- Smoking
- Alcohol Intake
- Physical Activity
- Diet
- Stress Level
- Hypertension
- Diabetes
- Hyperlipidemia
- Family History
- Previous Heart Attack
- Systolic BP
- Diastolic BP

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/heart-disease-prediction.git
```

Go to the project folder

```bash
cd heart-disease-prediction
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate the environment

**Windows**

```bash
.venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
uvicorn app:app --reload
```

Open your browser:

```
http://127.0.0.1:8000
```

---

## 🧠 Machine Learning Workflow

```
Dataset
   ↓
Data Preprocessing
   ↓
Model Training
   ↓
Random Forest
   ↓
Model Saving
   ↓
FastAPI
   ↓
Prediction
```

---

## 📦 Requirements

- fastapi
- uvicorn
- jinja2
- python-multipart
- pandas
- numpy
- scikit-learn
- joblib

---

## 🎯 Future Improvements

- Deep Learning model
- Better UI design
- Model comparison
- Cloud deployment
- Explainable AI

---

## 👨‍💻 Author

**Luna**

AI & Machine Learning Enthusiast

---

⭐ If you like this project, don't forget to **Star** the repository!
