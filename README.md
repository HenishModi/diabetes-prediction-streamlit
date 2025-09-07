# 🩺 Diabetes Prediction Web App

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.38-orange?logo=streamlit)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.5.2-lightgrey?logo=scikit-learn)

A **user-friendly Streamlit web application** that predicts the likelihood of diabetes based on various health parameters.  
The app leverages a **Random Forest Classifier** trained on real-world diabetes data.

---

## 🔹 Key Features
- Interactive **sliders** for health parameter inputs.  
- Displays **input data in a structured table** for verification.  
- Provides **real-time prediction results** (Diabetic / Non-Diabetic).  
- Shows **prediction probability** for better insight.  
- Clean and intuitive interface.

---

## 🛠 Installation & Setup

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/diabetes-prediction-app.git
cd diabetes-prediction-app
```

2. **Create a virtual environment (optional but recommended):**
```bash
python -m venv venv
# Activate
# Windows
venv\Scripts\activate
# Linux/macOS
source venv/bin/activate
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

---

## 🏃‍♂️ Usage

Run the Streamlit app:
```bash
streamlit run app.py
```

- Adjust sliders to input health data.  
- Click **Predict** to see results.  
- Input data is displayed along with prediction and probability.

---

## 🧩 Project Files

| File | Description |
|------|-------------|
| `app.py` | Streamlit application code |
| `model_diab_rfc.pkl` | Pre-trained Random Forest model |
| `requirements.txt` | Python dependencies |
| `README.md` | Project documentation |

---

## 📸 Screenshot

*Include a screenshot or GIF of the app here to showcase the interface.*

---

## 💡 Future Enhancements
- Sidebar for a cleaner UI.  
- Deploy online via **Streamlit Cloud** or **Heroku**.  
- Integrate multiple ML models for improved accuracy.  
- Add historical trend analysis for patient data.

---

## ⚖️ License

Open-source and free to use.

