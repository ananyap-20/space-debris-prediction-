# 🛰️ Space Debris Risk Prediction

A Machine Learning-powered web app that predicts the **risk category of space debris** based on key physical and environmental parameters like size, velocity, altitude, solar activity, and more.

Developed using **Streamlit**, **scikit-learn**, and visualized with **Seaborn** and **Matplotlib**.

---

## 🚀 Demo

🌐 Live App (optional): *Coming soon or deploy on Streamlit Cloud*

---

## 📦 Features

- Predicts space debris risk level (binary classification)
- Intuitive slider-based UI using Streamlit
- Visual correlation heatmap for feature insights
- Loads real orbital debris dataset (`space_debris_binary_risk.csv`)
- Handles model input errors with feature-matching

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Streamlit** – Web App UI
- **scikit-learn** – ML model (Random Forest)
- **Pandas** – Data manipulation
- **Matplotlib / Seaborn** – Visualization
- **Joblib** – Model serialization

---


---

## ⚙️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/ananyap-20/space-debris-prediction.git
cd space-debris-prediction

pip install -r requirements.txt

streamlit run main.py


