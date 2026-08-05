# ❤️ CardioAI – Intelligent Heart Attack Risk Prediction

CardioAI is a modern machine learning web application that estimates an individual's heart attack (cardiovascular disease) risk using clinical health measurements. The application combines a Logistic Regression model with an interactive dashboard to provide an easy-to-understand risk assessment and a personalized AI-generated health explanation.

This project was developed as an educational machine learning application using the NHANES cardiovascular dataset and deployed with Streamlit.

---

## 🚀 Features

* ❤️ Heart attack risk prediction using Machine Learning
* 📊 Risk probability displayed with an interactive gauge chart
* 📈 Feature contribution analysis showing how each health factor influences the prediction
* 🤖 AI-generated health explanation based on patient measurements
* 🎨 Modern medical dashboard with responsive UI
* ⚡ Fast predictions using a trained Logistic Regression model
* 📱 Fully responsive Streamlit web application

---

## 🧠 Machine Learning Model

**Algorithm**

* Logistic Regression

**Dataset**

* NHANES (National Health and Nutrition Examination Survey)

**Input Features**

* Age
* Body Mass Index (BMI)
* Systolic Blood Pressure
* Diastolic Blood Pressure
* Total Cholesterol
* C-Reactive Protein (CRP)
* Waist Circumference

**Output**

* Estimated probability of cardiovascular (heart attack) risk
* Risk category:

  * 🟢 Low Risk
  * 🟠 Moderate Risk
  * 🔴 High Risk

---

## 📊 Technologies Used

* Python
* Streamlit
* Scikit-learn
* Pandas
* NumPy
* Plotly
* Joblib

---

## 🤖 AI Health Explanation

After prediction, CardioAI analyzes the patient's clinical values and generates an easy-to-understand explanation highlighting:

* Blood pressure status
* BMI assessment
* Cholesterol level
* Inflammation (CRP)
* Waist circumference
* General lifestyle recommendations

This explanation is intended to improve user understanding and does **not** replace professional medical advice.

---

## 📁 Project Structure

```text
CardioAI/
│
├── app.py
├── requirements.txt
├── models/
│   ├── heart_attack_model.pkl
│   └── feature_names.pkl
└── README.md
```

---

## ⚠ Disclaimer

This application is developed for educational and research purposes only.

It is **not** a medical device and should **not** be used for diagnosis, treatment, or clinical decision-making. Always consult a qualified healthcare professional for medical advice.

---

## 👨‍💻 Author

Developed by **Habeeb**

B.Sc. Computer Science

Machine Learning • Data Science • AI
